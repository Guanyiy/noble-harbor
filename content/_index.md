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
      username: guanyi
      text: |
        I’m a master’s student in **Applied Statistics** at the University of Michigan.  
        My research lies at the intersection of **statistical methodology** and **cognitive aging**, focusing on how modeling frameworks can yield interpretable and robust inference when real-world data deviate from ideal assumptions.

        My current work with **Dr. Emily Briceño** applies **Bayesian hierarchical models**, **latent-variable frameworks**, and **diagnostic-driven statistical workflows** to improve the validity of neuropsychological assessment across culturally diverse populations.

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
      title: '📊 Research Focus'
      text: |-
        My work builds bridges between **statistical theory** and **psychometric measurement**,  
        emphasizing model transparency, uncertainty quantification, and diagnostic reasoning.

        - **Robust & Semiparametric Modeling:** Methods that remain valid under non-normality, heteroskedasticity, and model misspecification  
        - **Bayesian Inference & Hierarchical Models:** Quantifying uncertainty and borrowing strength across populations  
        - **Latent Variable & Factor Models:** Improving construct validity in cognitive testing  
        - **Missing Data & Bias Diagnostics:** Understanding MNAR mechanisms, overlap, and generalizability  
        - **Causal Inference under Imperfect Data:** Identification-first frameworks for observational studies  
    design:
      columns: '1'

  - block: collection
    id: projects
    content:
      title: Selected Projects
      text: "Applications of Bayesian and diagnostic-based statistical modeling in global cognitive aging research."
      filters:
        folders:
          - projects
    design:
      view: card
      columns: 2

  - block: collection
    id: publications
    content:
      title: Publications & Abstracts
      filters:
        folders:
          - publications
    design:
      view: citation
      columns: 1

  - block: markdown
    content:
      title: '🧠 Methodological Philosophy'
      text: |-
        I view statistics not only as a tool for estimation,  
        but as a **language for reasoning about data-generating mechanisms**.  
        My approach emphasizes:
        - **Assumption-aware modeling** before computation  
        - **Inference that reflects uncertainty** rather than overconfidence  
        - **Transparency in diagnostics and reporting**

        This mindset guides my work across measurement validation, missing-data analysis, and population inference.
    design:
      columns: '1'

  - block: markdown
    content:
      title: '🌿 Beyond Research'
      text: |-
        Outside of data and models, I enjoy discovering new cafés in Ann Arbor,  
        taking photos that capture good light, and curating playlists that keep me company while coding.  
        I believe that **clarity and empathy** belong as much in research as they do in life.
    design:
      columns: '1'
---
