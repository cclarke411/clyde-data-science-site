---
title: ''
summary: ''
date: 2022-10-24
type: landing

design:
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle
  - block: markdown
    content:
      title: 'About My Work'
      subtitle: ''
      text: |-
        I work at the intersection of data science, machine learning, signal processing, accessibility, and public-interest analytics.

        My recent projects span AI-enabled learning systems, dashboard design for socially relevant decision-making, youth workforce proposal development, and public-health reporting. Across those efforts, I focus on turning complex technical or analytical work into tools, narratives, and systems that people can actually use.

        I am especially interested in dialogue-centered learning, scientific inquiry, and the responsible use of AI to support education, research, and community-facing problem solving.
    design:
      columns: '1'
  - block: collection
    id: projects
    content:
      title: Selected Projects
      text: 'A sample of product, analytics, and proposal-focused work drawn from my recent portfolio.'
      count: 5
      filters:
        folders:
          - projects
    design:
      view: article-grid
      fill_image: false
      columns: 2
      show_date: false
      show_read_time: false
      show_read_more: false
---
