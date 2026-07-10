---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2023-10-24
type: landing

# Note: `username` refers to the user's folder name in `content/authors/`

sections:
  - block: resume-biography
    content:
      username: me
      text: ''
    design:
      background:
        gradient_mesh:
          enable: false
      # Avatar customization
      avatar:
        size: large # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: markdown
    content:
      title: 'Education'
      text: |-
        **Ph.D. in Economics**, University of California San Diego — 2025–Present

        **M.Sc. in Economics**, University of Pisa & Sant'Anna School of Advanced Studies — 2021–2023

        **Honors Master in Economics and Management**, Sant'Anna School of Advanced Studies — 2021–2024

        **B.Sc. in International Economics and Management**, Bocconi University — 2018–2021
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Latest Research
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
---
