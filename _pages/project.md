---
layout: project
permalink: /project/
title: Project
nav: true

sections:
  - title: "AIGC Platform"
    projects:
      - title: "SN AI Platform"
        img: "assets/img/sn_ai.png"
        desc: "Full-stack AIGC platform providing image/video generation based on diffusion models and LLMs. Covers model photo, product photo, poster, anime avatar generation, ID-consistent generation, marketing video production, lip-sync digital human live streaming, face swapping, and script generation."
      - title: "E-Commerce Inpainting with Mask Guidance"
        img: "assets/img/ecommerceinpainting.png"
        desc: "Addresses the overcompletion problem in diffusion-based e-commerce image generation. Proposes instance mask fine-tuned inpainting and train-free mask guidance to preserve product features during background restoration."
        links:
          - label: "arXiv"
            url: "https://arxiv.org/abs/2409.09681"
      - title: "Training-Free Style Consistent Image Synthesis"
        img: "assets/img/train-free-mask-guidance.png"
        desc: "Generates style-consistent e-commerce images using QKV-level attention manipulation. Employs shared KV in cross-attention and mask guidance from attention maps without additional training."
        links:
          - label: "arXiv"
            url: "https://arxiv.org/abs/2409.04750"

  - title: "Intelligent Creative Platform"
    projects:
      - title: "Iwogh Platform"
        img: "assets/img/platform.png"
        desc: "Internal creative design platform at Suning with three core modules: intelligent parsing, intelligent creation, and intelligent optimization. Provides comprehensive support for creative business with a suite of real-time creative tools."
      - title: "Intelligent Parsing"
        img: "assets/img/intelligent_parsing_1.png"
        desc: "Automated framework for extracting structured design semantics from e-commerce creatives. Includes material recognition, preprocessing, smart naming, and multi-level labeling layers. Significantly improves exposure, circulation, and CTR of creative materials."
        links:
          - label: "arXiv"
            url: "https://arxiv.org/abs/2312.17283"
      - title: "Smartbanner"
        img: "assets/img/smartbanner.png"
        desc: "Intelligent banner synthesis framework balancing creative freedom with design rules. Consists of planner, actuator, adjuster, and generator modules. Increases CTR by 30% and improves designer efficiency by 500%."
        links:
          - label: "arXiv"
            url: "https://arxiv.org/abs/2303.10325"
      - title: "ADCT - Ad Creative Optimization"
        img: "assets/img/adct1.png"
        desc: "Two-stage dynamic creative optimization for e-commerce advertising. Decouples optimization into a cascaded ranking stage (AutoCO + Transformer rerank) and a bandit selection stage. Improves CTR by 10% in online A/B testing."
        links:
          - label: "arXiv"
            url: "https://arxiv.org/abs/2312.01295"
      - title: "Text Tamper Detection"
        img: "assets/img/tamper1.png"
        desc: "Deep learning-based document tamper detection system with three-step pipeline: feature assistance, audit point positioning, and tamper recognition. Uses dual-path dual-stream network (RGB + ELA) achieving 0.913 precision."
        links:
          - label: "arXiv"
            url: "https://arxiv.org/abs/2402.13545"
---
