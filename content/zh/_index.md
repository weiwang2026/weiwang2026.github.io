---
# Leave the homepage title empty to use the site title
title:
#type: landing
type: home_index
#subTitle: Animal Physiological Ecology and Conservation


# 顶部轮播图
top_slides:
  block: slider
  design:
    # Slide height is automatic unless you force a specific height (e.g. '400px')
    slide_height: '95vh'
    is_fullscreen: false
    # Automatically transition through slides?
    loop: false
    # Duration of transition between slides (in ms)
    interval: 2000

  content:
    slides:
      - title: "构建贯通精准有机合成、化学生物学与创新药物研发的闭环体系"
        content: "面向化学与生命科学交叉前沿，聚焦原创化学工具开发"
        align: center
        background:
          image:
            filename: top_slides/h1.jpg
            filters:
              brightness: 1
          position: right
          color: '#666'
          
      - title: "服务癌症、神经退行性疾病与抗衰老等重大健康需求"
        content: "面向化学与生命科学交叉前沿，聚焦原创化学工具开发"
        align: center
        background:
          image:
            filename: top_slides/h2.png
            filters:
              brightness: 1
          position: right
          color: '#666'
          
      - title: "构建贯通精准有机合成、化学生物学与创新药物研发的闭环体系"
        content: "面向化学与生命科学交叉前沿，聚焦原创化学工具开发"
        align: center
        background:
          image:
            filename: top_slides/h3.jpg
            filters:
              brightness: 1
          position: right
          color: '#666'
          
      - title: "服务癌症、神经退行性疾病与抗衰老等重大健康需求"
        content: "面向化学与生命科学交叉前沿，聚焦原创化学工具开发"
        align: center
        background:
          image:
            filename: top_slides/h4.png
            filters:
              brightness: 1
          position: right
          color: '#666'
          
          
          
          
          
          
          
          
          
          



heroBlock:
  block: hero
  content:
    title: 宁波东方理工大学化学与化学生物学学院｜王卫课题组（Wang Group）
    subtitle:  
#    image:
#      filename: research_topic.jpg
    text: |
      
      面向化学与生命科学交叉前沿，聚焦原创化学工具开发，构建贯通精准有机合成、化学生物学与创新药物研发的闭环体系，服务癌症、神经退行性疾病与抗衰老等重大健康需求。
      
      **研究方向**
      ### 精准合成方法学
      发展不对称催化、光催化等策略，高效构筑复杂药物分子骨架。
      ### 化学生物学前沿
      基于点击化学与邻近标记等技术，解析生命过程的分子机制并实现功能调控。
      ### AI驱动药物研发
      融合人工智能设计新型靶向蛋白降解剂（TPD），并提出SenoTAC衰老细胞清除策略。


  
heroSlideBlock:
  block: slider
  content:
    slides:
    - title: 
      content: 
      align: center
      background:
        image:
          filename: group_slides/team-view.webp
          filters:
            brightness: 1
        position: right
        color: '#666'  
    # - title: 
    #   content: 
    #   align: left
    #   background:
    #     image:
    #       filename: group_slides/group_photo2.jpg
    #       filters:
    #         brightness: 1
    #     position: right
    #     color: '#666'  
  design:
    # Slide height is automatic unless you force a specific height (e.g. '400px')
    slide_height: '400px'
    is_fullscreen: false
    # Automatically transition through slides?
    loop: false
    # Duration of transition between slides (in ms)
    interval: 2000


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
    page_type: post
  design:
    view: card
    columns: '1'      


publicationsBlock:
  block: collection
  content:
    title: Publications
    count: 5
    filters:
      folders:
        - publication
#      publication_type: 'article-journal'
      publication_type: 
  design:
    view: card
    columns: '1'      

teamsBlock:
  block: markdown
  content:
    title:
    subtitle:  
    text: |
      {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
  design:
    columns: '1'



 
---
