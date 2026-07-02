---
title: 'Home'
date: 2023-10-24
type: landing

sections:
  - block: resume-biography
    content:
      username: me
      text: |
        I am a first-year PhD student at **Peking University**. My advisor is [Prof. Chi Zhang (张驰)](https://wellyzhang.github.io/). My research focuses on **generative evaluation** and **agentic reasoning** in open-ended and dynamically generated environments.

        My academic journey began at age 15 in the **Wu Jianxiong Honor College** at Southeast University, followed by a Master’s from **UCAS**, where I served as Student Union President. Prior to returning to academia, I spent four years as a Deep Learning Researcher at **Baidu’s Autonomous Driving Department**, leading the development of retrieval-based planning and self-supervised frameworks.

        My recent work develops **generative and augmented evaluation frameworks** for frontier AI systems, including **UniCode (ICML 2026)** for code reasoning and **MCU (ICML 2025 Spotlight)** for open-ended game agents.

    design:
      spacing:
        padding: [0, 0, 0, 0]
      biography:
        style: 'text-align: justify; font-size: 0.8em;'
      avatar:
        size: medium
        shape: circle

  - block: collection
    content:
      title: Blog
      text: Research notes and essays.
      filters:
        folders:
          - blog
        kinds:
          - page
      sort_by: Date
      sort_ascending: false
    design:
      view: card
      columns: 3
      fill_image: true
      show_date: true
      show_read_time: true
      show_read_more: true
      spacing:
        padding: ['1rem', 0, '6rem', 0]
  
  - block: collection
    content:
      title: Publications
      text: Published papers and preprints.
      filters:
        folders:
          - publications
        kinds:
          - page
      sort_by: Date
      sort_ascending: false
    design:
      view: card
      columns: 3
      fill_image: true
      show_date: true
      show_read_time: false
      show_read_more: true
      spacing:
        padding: ['3rem', 0, '3rem', 0]
---