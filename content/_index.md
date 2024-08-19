---
# Leave the homepage title empty to use the site title
title:
date: 2024-08-08
type: landing

sections:

  - block: slider
    content:
      slides:
      - title: '**Yau Group**'
        content: Developing novel statistical machine learning techniques to improve health and wellbeing through collaboration with the biological and medical sciences
        align: left
        background:
          image:
            filename: research.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'
      - title: '**Driven by real-world applications**' 
        content: 'Inspired by real applications, we are creating artificial intelligence technologies that can make a real impact on improving human health.'
        align: left
        background:
          image:
            filename: imc.jpeg
            filters:
              brightness: 0.7
          position: right
          color: '#555'
      - title: '**Global center for world-class research**' 
        content: 'We are based at the Big Data Institute at the University of Oxford.'
        align: left
        background:
          image:
            filename: bdi.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'          
      - title: '**Joining the group**'
        content: 'Find out the latest opportunities to join the research group.'
        align: right
        background:
          image:
            filename: group.JPG
            filters:
              brightness: 0.7
          position: center
          color: '#333'
        link:
          icon: phone
          icon_pack: fas
          text: Join Us
          url: ../contact/

    design:
      columns: '1'
    # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 2000      
---
