---
title: 'Home'
date: 2023-10-24
type: landing

design:
  background:
    image:
      # Add your image background to `assets/media/`.
      filename: bg-hue.svg

sections:
  - block: biography
    content:
      # The user's folder name in content/authors/
      username: admin
    design:
      biography:
        style: 'text-align: justify; font-size: 0.8em;'
  - block: cta-button-list
    content: Colter J. Uscola is a PhD student at the University of British Columbia, Vancouver. His award-winning research focuses on processes of identity formation and mental health and is published in Society and Mental Health.
      # Need a custom icon?
      # Add an SVG image to the `assets/media/icons/` folder and reference it in the `icon` field below
      buttons:
        - text: Read my latest paper Society and Mental Health
          icon: academicons/arxiv
          url: https://journals.sagepub.com/doi/full/10.1177/21568693221141927
        - text: Connect with me on LinkedIn
          icon: brands/linkedin
          url: https://www.linkedin.com/in/colter-uscola-4474b1249/
---
