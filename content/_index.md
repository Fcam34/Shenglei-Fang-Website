---
title: Home
date: 2026-08-24
type: landing
seo:
  title: Shenglei Fang — PhD Researcher in AI

sections:
  - block: resume-biography
    id: about
    content:
      username: me
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      show_status: false
      spacing:
        padding: ['0', '0', '5rem', '0']
      banner:
        filename: kalen-emsley-Bkci_8qcdvQ-unsplash.jpg
      biography:
        style: 'text-align: center; font-size: 0.92em; max-width: 780px;'
      avatar:
        size: large
        shape: rounded

  - block: focus-areas
    id: research
    content:
      title: Research
      subtitle: Learning across geometry and scale
      text: I design neural architectures whose inductive biases reflect the structure of the data they learn from.
      items:
        - name: Geometric Deep Learning
          description: Intrinsic attention mechanisms that compare features consistently across manifolds, graphs, and local coordinate systems.
          icon: hero/cube-transparent
          gradient: from-indigo-500 to-blue-500
          status: active
          topics:
            - Vector Bundles
            - Parallel Transport
            - Manifold Learning

        - name: Scale-Invariant Sequence Modelling
          description: State-space architectures that connect fine-scale dynamics with long-range behaviour through multiscale and renormalisation-inspired structure.
          icon: hero/arrows-pointing-out
          gradient: from-blue-500 to-cyan-500
          status: active
          topics:
            - Mamba
            - State Space Models
            - Fractal Dynamics

        - name: AI for Scientific Data
          description: Representation learning for structured scientific observations, including single-cell data, spatial transcriptomics, and 3D point clouds.
          icon: hero/beaker
          gradient: from-cyan-500 to-teal-500
          status: active
          topics:
            - Single-cell Omics
            - Spatial Data
            - Point Clouds
    design:
      layout: cards
      background:
        color:
          light: '#f8fafc'
          dark: '#0f172a'

  - block: content-collection
    id: publications
    content:
      title: Selected Publications
      text: Two papers presented at the International Conference on Machine Learning (ICML 2026).
      count: 10
      filters:
        folders:
          - publications
      sort_by: Date
      sort_ascending: false
      archive:
        enable: false
    design:
      view: citation
      spacing:
        padding: ['6rem', '0', '6rem', '0']

  - block: resume-experience
    id: experience
    content:
      title: Education & Experience
      username: me
    design:
      date_format: January 2006
      is_education_first: true
      background:
        color:
          light: '#f8fafc'
          dark: '#0f172a'

  - block: resume-skills
    id: skills
    content:
      title: Research Toolkit
      username: me

  - block: markdown
    id: contact
    content:
      title: Get in touch
      text: >
        I am always happy to discuss geometric learning, state-space models,
        scientific machine learning, and research collaborations.

        [Email me](mailto:FangS4@cardiff.ac.uk) · [GitHub](https://github.com/Fcam34)
    design:
      spacing:
        padding: ['5rem', '1.5rem', '6rem', '1.5rem']
      background:
        color:
          light: '#eff6ff'
          dark: '#111827'
---
