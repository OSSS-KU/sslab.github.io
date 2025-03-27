---
# Leave the homepage title empty to use the site title
title:
date: 2025-03-27
type: landing

sections:
  - block: hero
    content:
      title: |
        <span style="font-size: 0.8em; color:#9D2235;">
          <strong>System Software</strong>
        </span> <span style="font-size: 0.8em;> Lab.</span><br>
        <span style="font-size: 0.7em;">
          <strong>KOREA UNIVERSITY</strong>
        </span><br>
        <span style="font-size: 0.5em;">
        고려대학교 컴퓨터학과<br>
        <strong>시스템 소프트웨어 연구실</strong>
        </span>
      image:
        filename: sslab_logo.png
      text: |
        <br>
        <span style="font-size: 0.75em;">
        We investigate the <strong>challenges of system software technologies</strong> with the goal of <strong>better performance and efficiency</strong> of computing infrastructures on all scales, from individual computers to massive cloud to planetary scale clusters. Our research efforts cover exciting topics like system optimization techniques, resource efficiency, high-performance computing, and virtualization.
        </span>
  
  - block: collection
    content:
      title: Latest News
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
      columns: '1'
  
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

  # - block: markdown
  #   content:
  #     title:
  #     subtitle:
  #     text: |
  #       {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
  #   design:
  #     columns: '1'
---
