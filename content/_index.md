---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: slider
    id: overview
    content:
      slides:
      - title: CDS Lab at UM
        content: Cloud and Distributed Systems Lab
        align: left
        background:
          image:
            filename: jienigui.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'
      # - title: Lunch & Learn ☕️
      #   content: 'Share your knowledge with the group and explore exciting new topics together!'
      #   align: left
      #   background:
      #     image:
      #       filename: contact.jpg
      #       filters:
      #         brightness: 0.7
      #     position: center
      #     color: '#555'
      # - title: World-Class Semiconductor Lab
      #   content: 'Just opened last month!'
      #   align: right
      #   background:
      #     image:
      #       filename: welcome.jpg
      #       filters:
      #         brightness: 0.5
      #     position: center
      #     color: '#333'
      #   link:
      #     icon: graduation-cap
      #     icon_pack: fas
      #     text: Join Us
      #     url: ../contact/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 2000
  - block: hero
    content:
      title: |
        About CDS Lab
      image:
        filename: jienigui.jpg
      text: |
        **CDS Lab**(Cloud and Distributed Systems Lab) from the Department of Computer and Information Science at University of Macau, led by Prof. Huanle Xu.

  - block: markdown
    content:
      title: "CDS Lab"
      subtitle: 'Cloud and Distributed Systems Lab'
      text: "
      **CDS Lab**(Cloud and Distributed Systems Lab) from the Department of Computer and Information Science at University of Macau, led by Prof. Huanle Xu.
      <br>.....
      "
    design:
      columns: '2'
      spacing:
        padding: ['100px', '0', '100px', '0']
      css_class: 

  # Research Topic
  - block: markdown
    id: research
    content:
      title: "Research Topics"
      text: '
      <br>
      Our research combines ....
      A non-exhaustive list of research topics studied in our group include:
      <br>
      <ul>
        <li>**Microservice analysis and resource management**</li>
          <ul>Investigate the microservice architecture in a  large scale and design efficient resource management algorithms.</ul>
        <li>**Intelligent deep learning in large-scale GPU clusters**</li>
          <ul>Implement intelligent online resource management schemes in heterogeneous/homogeneous GPU clusters to maximise resource efficiency.</ul>
        <li>**Unified scheduling algorithm design for large-scale cloud platforms**</li>
          <ul>Design unified schedulers in large-scale data centers to balance the trade-off between application performance, resource utilisation, and scheduling scalability.</ul>
      </ul>
      '
    design:
      columns: '1'
      spacing:
        padding: ['100px', '0', '100px', '0']
      css_class: 

  # News
  - block: markdown
    id: news
    content:
      title: "News"
      text: '
      **Mar 2025 -** FFT got Accepted by ICS 2025. <br>
      '
    design:
      columns: '1'
      spacing:
        padding: ['100px', '0', '100px', '0']
      css_class: 

  # Members
  - block: people
    id: members
    content:
      title: Members
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
          - Professor
          - Postdoc
          - PhD Student
          - Master Student
          - Research Assistant
          - Visiting Scholar
          - Alumni
      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      show_social: false

  # Publications
  - block: collection
    id: publications
    content:
      title: Publications
      subtitle: "You can also search all the papers [here](./publication)."
      text: 
      filters:
        folders:
          - publication
        publication_type: 
    design:
      view:  card     
      columns: '1'

  # Contact
  - block: contact
    id: contact
    content:
      title: Contact
      coordinates:
        latitude: '22.1325'
        longitude: '113.5437'
      directions: Room 1048 Faculty of Science and Technology University of Macau, E11 Avenida da Universidade Taipa, Macau, China
    design:
      columns: '1'
---
