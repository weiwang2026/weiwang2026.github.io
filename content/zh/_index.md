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
        content: "打造覆盖原创化学工具开发、机制研究与药物转化的全链条研究平台"
        align: center
        background:
          image:
            filename: top_slides/h1.jpg
            filters:
              brightness: 1
          position: right
          color: '#666'
          
      - title: "服务癌症、神经退行性疾病与抗衰老等重大疾病治疗需求"
        content: "聚焦原创化学工具开发，推动复杂疾病精准干预与治疗创新"
        align: center
        background:
          image:
            filename: top_slides/h2.png
            filters:
              brightness: 1
          position: right
          color: '#666'
          
      - title: "构建贯通精准有机合成、化学生物学与创新药物研发的闭环体系"
        content: "打造覆盖原创化学工具开发、机制研究与药物转化的全链条研究平台"
        align: center
        background:
          image:
            filename: top_slides/h3.jpg
            filters:
              brightness: 1
          position: right
          color: '#666'
          
      - title: "服务癌症、神经退行性疾病与抗衰老等重大疾病治疗需求"
        content: "聚焦原创化学工具开发，推动复杂疾病精准干预与治疗创新"
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
    title: 宁波东方理工大学化学与化学生物学学院｜王卫课题组
    subtitle:  
#    image:
#      filename: research_topic.jpg
    text: |

      本课题组立足化学与生物学交叉前沿，致力于开发与应用先进化学工具，解析并调控复杂生命过程。团队已构建起一套成熟完备的一体化研究体系，涵盖精准有机合成、变革性化学生物学技术与人工智能辅助药物研发。我们的核心使命是研发具有突破性的治疗策略，应对全球性健康难题，重点聚焦肿瘤、神经退行性疾病与细胞衰老领域。
      
      **研究方向**
      ### 精准合成方法学
      依托不对称催化与光氧化还原化学技术，实现结构复杂、具有生物优势骨架的高效发散式构建。课题组专注开发高效合成方法，为药物研发快速拓展多样化化学空间。
      ### 化学生物学前沿
      通过点击化学、邻近标记及复杂生物大分子调控等技术，阐明并干预生理与病理过程的内在分子机制。依托新型化学探针，实现天然生理环境下蛋白质功能的可视化示踪与精准调控。
      ### 人工智能驱动的治疗创新
      将人工智能与理性分子设计相结合，加速新一代靶向蛋白降解（TPD）技术平台研发。团队首创SenoTAC（靶向衰老细胞嵌合体） 策略，为衰老细胞选择性清除及衰老相关疾病治疗建立了国际领先的研究体系。
      

  
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
