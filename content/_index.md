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
        size: l # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: markdown
    id: research
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        Most robotics research deploys intelligent algorithms on simple hardware. Manufacturing researchers often do the opposite: build specialized machines to avoid complex reasoning systems. I am interested in exploring what can be achieved when you combine the adaptability of intelligent algorithms with the robustness of industrial hardware.
        My ultimate vision is to enable robotic manufacturing systems that can autonomously produce or repair arbitrary parts. To achieve this, I work on the algorithmic design of robotic manufacturing systems, the development of algorithms for planning and control, and the integration of these into real-world systems.
        
        If any of this sounds interesting, please reach out to collaborate 😃
    design:
      columns: '1'
      css_class: research-wide
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

---
