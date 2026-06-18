---
title: "Tarlis Tortelli"
summary: ""
date: "2022-10-24"
type: "landing"
sections:
  - block: "resume-biography-3"
    content:
      username: "me"
      text: ""
      button:
        text: "Download CV"
        url: "uploads/resume.pdf"
      headings:
        about: ""
        education: ""
        interests: ""
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: "md"
      avatar:
        size: "medium"
        shape: "circle"
    ce: "section-305256a3"
    As: "section-a5b5be37"
  - block: "markdown"
    content:
      title: "📚 My Research"
      subtitle: ""
      text: |-
        Use this area to speak to your mission. I'm a research scientist in the Moonshot team at DeepMind. I blog about machine learning, deep learning, and moonshots.

        I apply a range of qualitative and quantitative methods to comprehensively investigate the role of science and technology in the economy.

        Please reach out to collaborate 😃
    design:
      columns: "1"
    ce: "section-f6a81086"
    As: "section-02240377"
  - block: "collection"
    content:
      title: "Featured Publications"
      filters:
        folders:
          - "publications"
        featured_only: true
    design:
      view: "article-grid"
      columns: 2
    ce: "section-papers"
    id: "papers"
    As: "section-eb5b91fc"
  - block: "collection"
    content:
      title: "Recent Publications"
      text: ""
      filters:
        folders:
          - "publications"
        exclude_featured: false
    design:
      view: "citation"
    ce: "section-13991899"
    As: "section-7c8fcf62"
---
