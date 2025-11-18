---
# Leave the homepage title empty to use the site title
title: ''
date: 2025-11-18
type: landing

design:
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      username: guanyi   # 对应 content/authors/guanyi/_index.md
      text: |
        I’m a master’s student in **Applied Statistics** at the University of Michigan.  
        My research explores how statistical and psychometric methods can improve our understanding of **cognitive aging**, **cross-cultural measurement**, and **bias in neuropsychological assessment**.  
        I work with **Dr. Emily Briceño** on projects spanning Nepal, Mexico, India, and the U.S.

      button:
        text: Download CV
        url: uploads/Guanyi_Yang_CV.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      css_class: hbx-bg-gradient
      avatar:
        size: medium
        shape: circle

  - block: markdown
    content:
      title: '🧠 Research Focus'
      text: |-
        - **Measurement & Cognitive Aging:** Validity and adaptation of cognitive assessments in diverse populations  
        - **Cross-Cultural Data Harmonization:** Linking HCAP cohorts across countries  
        - **Bayesian and Robust Modeling:** Inference under bias, uncertainty, and imperfect data  
        - **Causal Inference Diagnostics:** Assessing overlap and robustness
    design:
      columns: '1'

  - block: collection
    id: projects
    content:
      title: Current Projects
      filters:
        folders:
          - projects
      text: "Selected ongoing collaborations and analyses."
    design:
      view: card
      columns: 2

  - block: collection
    id: publications
    content:
      title: Publications & Posters
      filters:
        folders:
          - publications
    design:
      view: citation
      columns: 1

  - block: markdown
    content:
      title: '🌿 Beyond Research'
      text: |-
        Outside of work, I love exploring cafés around Ann Arbor, photographing good light,  
        and discovering songs that keep me company while coding.  
        I believe good science is like good storytelling — **clear, honest, and curious**.
    design:
      columns: '1'
---
