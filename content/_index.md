---
title: 'Home'
date: 2023-10-24
type: landing
sections:
  - block: resume-biography
    content:
      # Author slug (data/authors/<slug>.yaml)
      username: me
      # 直接在这里写带加粗的内容，它会覆盖 yaml 里的 bio
      text: |
        I am a first-year PhD student at **Peking University** researching **generative evaluation** and **agentic reasoning** within open-ended environments. My academic journey began at age 15 in the **Wu Jianxiong Honor College** at Southeast University, followed by a Master’s from **UCAS**, where I served as Student Union President. Prior to returning to academia, I spent four years as a Deep Learning Researcher at **Baidu’s Autonomous Driving Department**, leading the development of retrieval-based planning and self-supervised frameworks. My latest research, **MCU (ICML 2025 Spotlight)**, establishes generative evaluation frameworks to advance autonomous agents in open-ended domains.
    design:
      spacing:
        padding: [0, 0, 0, 0]
      biography:
        style: 'text-align: justify; font-size: 0.8em;'
      # Avatar customization
      avatar:
        size: medium  # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: collection
    content:
      filters:
        folders:
          - blog
    design:
      spacing:
        padding: ['3rem', 0, '6rem', 0]
---
