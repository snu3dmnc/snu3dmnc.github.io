---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        SNU   
        3D Modeling and Navigation Center
      # image:
      #   filename: welcome.jpg
      text: |
        <br>
        <b>3D Modeling of Haedong Advanced Engineering Hall</b><br>
        A demonstration of high-precision 3D modeling and updating of key areas in the Haedong Advanced Engineering Hall using sensors such as LiDAR, stereo cameras, and 360-degree cameras.<br>
        <b>Mobile Robot Navigation</b><br>
        A demonstration of autonomous navigation by a mobile robot between key locations within the Haedong Advanced Engineering Hall.<br>
        
  - block: collection
    content:
      title: Research
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '2'
  
  # - block: markdown
  #   content:
  #     title:
  #     subtitle: ''
  #     text:
  #   design:
  #     columns: '1'
  #     background:
  #       image: 
  #         filename: coders.jpg
  #         filters:
  #           brightness: 1
  #         parallax: false
  #         position: center
  #         size: cover
  #         text_color_light: true
  #     spacing:
  #       padding: ['20px', '0', '20px', '0']
  #     css_class: fullscreen

  # - block: collection
  #   content:
  #     title: Latest Preprints
  #     text: ""
  #     count: 5
  #     filters:
  #       folders:
  #         - publication
  #       publication_type: 'article'
  #   design:
  #     view: citation
  #     columns: '1'

  - block: markdown
    content:
      title: Downloads Datasets
      subtitle:
      text: |
        {{% cta cta_link="./datasets/" cta_text="Open Datasets →" %}}
    design:
      columns: '1'
---
