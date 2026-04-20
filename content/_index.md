---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: ''
      # Show a call-to-action button under your biography? (optional)
      #button:
      #  text: Download CV
      #  url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      # Use the new Gradient Mesh which automatically adapts to the selected theme colors
      background:
        gradient_mesh:
          enable: true

      # Name heading sizing to accommodate long or short names
      name:
        size: md # Options: xs, sm, md, lg (default), xl

      # Avatar customization
      avatar:
        size: xl # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        Most robotics research deploys intelligent algorithms on simple hardware. Manufacturing researchers often do the opposite: build specialized machines to avoid complex reasoning systems. My research sits at this intersection of robotic manufacturing systems for the circular economy. These systems require both the adaptability of robotics to deal with the uncertainties of disassembly and remanufacturing and the robustness and throughput of manufacturing to meet industrial demands.

        To solve this, I build robotic manufacturing systems where task-specific, reconfigurable hardware is combined with intelligent planning and control. Neither field alone has the tools for this: you need the adaptability of modern robotic reasoning systems *and* the robustness of customized tools and hardware.

        My long-term goal is to enable autonomous systems that can zero-shot produce arbitrary parts. Given a CAD model, the system designs its tooling, configures its hardware, and then produces the desired parts. This requires advanced in task and motion planning, control, and design optimization algorithms that can reason about CAD models and manufacturing processes. 

        If any of this sounds interesting, please reach out to collaborate 😃
    design:
      columns: '2'
  - block: collection
    id: papers
    content:
      title: Recent Featured Works
      count: 0
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 3
      show_read_time: false
      show_read_more: false
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - events
    design:
      view: card
---
