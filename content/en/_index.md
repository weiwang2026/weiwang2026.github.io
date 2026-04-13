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
      - title: "Integrating Precision Organic Synthesis, Chemical Biology, and Innovative Drug Discovery"
        content: "Building a Closed-Loop Research Ecosystem for Next-Generation Therapeutic Innovation"
        align: center
        background:
          image:
            filename: top_slides/h1.jpg
            filters:
              brightness: 1
          position: right
          color: '#666'
          
      - title: "Addressing Major Therapeutic Needs in Cancer, Neurodegenerative Diseases, and Aging"
        content: "Developing Original Chemical Tools to Tackle Complex Diseases"
        align: center
        background:
          image:
            filename: top_slides/h2.png
            filters:
              brightness: 1
          position: right
          color: '#666'
          
      - title: "Integrating Precision Organic Synthesis, Chemical Biology, and Innovative Drug Discovery"
        content: "Building a Closed-Loop Research Ecosystem for Next-Generation Therapeutic Innovation"
        align: center
        background:
          image:
            filename: top_slides/h3.jpg
            filters:
              brightness: 1
          position: right
          color: '#666'
          
      - title: "Addressing Major Therapeutic Needs in Cancer, Neurodegenerative Diseases, and Aging"
        content: "Developing Original Chemical Tools to Tackle Complex Diseases"
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
    title: Welcome to Wang Group!
    subtitle: Executive Summary
#    image:
#      filename: research_topic.jpg
    text: |
      
      At the strategic interface of chemistry and biology, the **Wang Group** is dedicated to developing and deploying advanced chemical toolkits to dissect and modulate biological complexity. We have established a robust, integrated research paradigm spanning precision organic synthesis, transformative chemical biology, and AI-augmented drug discovery. Our mission is to engineer disruptive therapeutic strategies to address global health challenges, with a focus on oncology, neurodegeneration, and senescence.
      
      **Research Areas**
      ### Precision Synthetic Methodology
      Harnessing the power of asymmetric catalysis and photoredox chemistry to streamline the divergent construction of structurally complex and biologically privileged scaffolds. We focus on developing high-efficiency synthetic methodologies that provide rapid access to diverse chemical space for drug discovery.
      ### Frontiers in Chemical Biology
      Exploring click chemistry, proximity labeling, and sophisticated biomacromolecule modulation to elucidate and manipulate the underlying molecular logic of physiological and pathological processes. By developing novel chemical probes, we aim to visualize and control protein functions in their native biological environments.
      ### AI-Driven Therapeutic Innovation
      Integrating Artificial Intelligence with rational molecular design to accelerate the development of next-generation Targeted Protein Degradation (TPD) platforms. Notably, the group pioneers the SenoTAC (Senolytic-Targeted Chimera) strategy, providing a leading international framework for the selective clearance of senescent cells and the treatment of age-related diseases.

  
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
