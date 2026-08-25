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
      subtitle: AI for medical and biological discovery
      text: I develop machine learning methods that connect principled model design with clinically and biologically meaningful applications.
      items:
        - name: Medical AI & Multimodal Diagnosis
          description: Learning from ultrasound, medical images, biomarkers, and clinical records to support noninvasive diagnosis and robust disease prediction.
          icon: hero/heart
          gradient: from-rose-500 to-orange-500
          status: active
          topics:
            - Medical Imaging
            - Multimodal Learning
            - Clinical AI

        - name: Single-cell & Spatial Transcriptomics
          description: Foundation and representation-learning models for cell annotation, novel cell discovery, and spatial tissue-domain analysis.
          icon: hero/beaker
          gradient: from-emerald-500 to-cyan-500
          status: active
          topics:
            - Single-cell RNA-seq
            - Spatial Omics
            - Foundation Models

        - name: Geometric & Scale-aware Learning
          description: Attention and state-space architectures whose inductive biases respect geometry, transport, and multiscale structure.
          icon: hero/cube-transparent
          gradient: from-indigo-500 to-blue-500
          status: active
          topics:
            - Vector Bundles
            - Mamba
            - Scale Invariance
    design:
      layout: cards
      background:
        color:
          light: '#f8fafc'
          dark: '#0f172a'

  - block: focus-areas
    id: projects
    content:
      title: Research Projects
      subtitle: Selected work across AI methodology and applications
      text: My recent projects combine geometric learning, state-space models, medical AI, and computational biology.
      items:
        - name: Vector Bundle Attention (VBA)
          description: A geometry-informed Transformer that represents tokens as base-fiber pairs with learned transport and curvature-aware attention. Evaluated on single-cell and spatial transcriptomics as well as 3D point-cloud classification.
          icon: hero/cube-transparent
          gradient: from-indigo-500 to-violet-500
          url: https://openreview.net/forum?id=nQ4iLQtsCF
          topics:
            - ICML 2026
            - Geometric Attention
            - Transcriptomics

        - name: Dynamic Fractal Mamba
          description: A fractal geometry-inspired multiscale state-space model with shared recursive dynamics across resolutions, designed for robust zero-shot scale generalisation in sequences, spatial omics, and pathology.
          icon: hero/arrows-pointing-out
          gradient: from-blue-500 to-cyan-500
          url: https://openreview.net/forum?id=L8a9GRfoly
          topics:
            - ICML 2026
            - State Space Models
            - Scale Invariance

        - name: DeepLUS+ for Fatty Liver Disease
          description: Multimodal deep learning for noninvasive MASH diagnosis using ultrasound and clinical data, validated on multicentre biopsy cohorts and more than 7,000 real-world cases with AUC above 0.96.
          icon: hero/heart
          gradient: from-rose-500 to-orange-500
          topics:
            - Under Review
            - Ultrasound
            - Multimodal Diagnosis

        - name: scSEEK
          description: A self-supervised expert-embedding foundation model for single-cell RNA-seq, integrating Bio-MoE, multi-head latent attention, and reinforcement-tuned biological knowledge across 599,000 cells.
          icon: hero/sparkles
          gradient: from-emerald-500 to-teal-500
          topics:
            - Under Review
            - Single-cell RNA-seq
            - Foundation Models

        - name: Hybrid Transformer-Mamba for Medical Imaging
          description: A gated-attention Vision Transformer and Mamba architecture for multimodal disease classification across histopathology, MRI, X-ray, and clinical imaging datasets.
          icon: hero/photo
          gradient: from-fuchsia-500 to-pink-500
          topics:
            - Under Review
            - Medical Imaging
            - Multimodal Learning

        - name: Alzheimer's Disease Prediction
          description: Deep learning models that combine ADNI MRI images and biomarkers, processing 150 GB of imaging data and more than one million clinical data points for disease prediction.
          icon: hero/cpu-chip
          gradient: from-amber-500 to-red-500
          topics:
            - Under Review
            - MRI
            - Biomarkers
    design:
      layout: cards

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

  - block: markdown
    id: contact
    content:
      title: Get in touch
      text: >
        I am always happy to discuss AI for Science, medical AI, single-cell
        and spatial transcriptomics, geometric learning, state-space models,
        and research collaborations.

        [Email me](mailto:FangS4@cardiff.ac.uk) · [GitHub](https://github.com/Fcam34)
    design:
      spacing:
        padding: ['5rem', '1.5rem', '6rem', '1.5rem']
      background:
        color:
          light: '#eff6ff'
          dark: '#111827'
---
