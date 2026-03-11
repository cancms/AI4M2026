---
# Leave the homepage title empty to use the site title
title:
type: home_index




# 实验室介绍
heroBlock:
  block: hero
  content:
    title: WELCOME 
#   image:
#      filename: research_topic.jpg
    text: |
      Descrioption
  



# 图片轮播  
heroSlideBlock:
  block: slider

  content:

    slides:

    - title: "" # desc-title1
      content:  "" # desc1
      align: center
      background:
        image:
          filename: group_slides/g1.png
          filters:
            brightness: 1
        position: right
        color: '#666'  

    - title:  "" # desc-title2
      content:  "" # desc2
      align: left
      background:
        image:
          filename: group_slides/g2.png
          filters:
            brightness: 1
        position: right
        color: '#666'  

    - title:  "" # desc-title2
      content:  "" # desc2
      align: left
      background:
        image:
          filename: group_slides/g3.png
          filters:
            brightness: 1
        position: right
        color: '#666'  

  design:
    # Slide height is automatic unless you force a specific height (e.g. '400px')
    # height controlled by css
    
#    slide_height: '500px'
    
    
    is_fullscreen: false
    # Automatically transition through slides?
    loop: true
    # Duration of transition between slides (in ms)
    interval: 1000








newsBlock:
  block: collection
  content:
    title: Latest News
    count: 5
    filters:
      author: ''
      category: ''
      exclude_featured: false
      publication_type: ''
      tag: ''
    offset: 0
    order: desc
    page_type: news
    
#    archive:
#      enable: true
   
  design:
    view: card
    columns: '1'      




---  



