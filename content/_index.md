---
# Leave the homepage title empty to use the site title
title: ''
summary: 'I am a PhD student in Economics at UC San Diego. My research interests include econometrics, macroeconomics, monetary policy, and financial asset price dynamics.'
image:
  filename: 'authors/me.jpg'
date: 2023-10-24
lastmod: 2026-11-01
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
        size: xxl
        shape: square
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
