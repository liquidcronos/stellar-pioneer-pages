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
        The central difference between human and animal intelligence is the ability to design tools and actively shape the environment to their needs.

        My research brings this capability to robotic systems. I focus on two tightly coupled pillars: the ability to design their tools and ideal environment such as the cell layout and the ability to phyiscally realize a given design.
        A central challenge here is that design influences behavior and vice versa. Addressing this jointly targets a key bottleneck in robotic manufacturing: not only autonomously programming and adapting the tooling to new tasks.
        One focus of application is circular manufacturing, which is characterized by high uncertainty and fast task changes that need to be handled through intelligent hardware and software.
        
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
