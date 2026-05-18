---
layout: about
title: About
permalink: /
description:

profile:
  align: right
  image: li.jpg

news:
  - date: "2026"
    content: "Paper <em>EditIDv2: Editable ID Customization with Data-Lubricated ID Feature Integration for Text-to-Image Generation</em> accepted to <b>Multimedia Systems</b>."
    tier: "JCR Q2"
  - date: "2026"
    content: "Paper <em>Hyperspectral Image Classification via Transformer-based Spectral-Spatial Attention Decoupling and Adaptive Gating</em> accepted to <b>International Journal of Image and Data Fusion</b>."
    tier: "JCR Q4"
  - date: "2026"
    content: "Paper <em>DGCNet: An Efficient 3D-DenseNet based on Dynamic Group Convolution for Hyperspectral Remote Sensing Image Classification</em> accepted to <b>Spectroscopy Letters</b>."
    tier: "JCR Q4"
  - date: "2025"
    content: "Paper <em>EditID: Training-Free Editable ID Customization for Text-to-Image Generation</em> accepted to <b>Findings of EMNLP 2025</b>."
    tier: "CCF-B"
  - date: "2025"
    content: "Paper <em>Dynamic 3D KAN Convolution with Adaptive Grid Optimization for Hyperspectral Image Classification</em> accepted to <b>Arabian Journal for Science and Engineering</b>."
    tier: "JCR Q2"

research_interests:
  - group: "Generative AI"
    items:
      - AIGC
      - LLMs
      - LVMs
      - Diffusion Models
  - group: "Vision & Video"
    items:
      - Video Editing
      - Digital Humans
      - OCR
      - Detection
  - group: "Foundations"
    items:
      - Deep Learning
      - Remote Sensing

experience:
  - title: Algorithm Engineer
    company: iFlytek
    department: Consumer Business Group, AI Marketing Business Line
    location: Hefei, China
    period: 2024.11 - Present
    description:
      - Core algorithm research on <a href="https://typemovie.art" target="_blank">讯飞绘镜 (Typemovie)</a>, <b>homture</b> (AI photo frame), and <b>超级制图</b> — native large-model AIGC applications for intelligent marketing.
      - Authored the <b>EditID v1/v2</b> series (Findings of EMNLP 2025 / Multimedia Systems): training-free identity-feature decoupling for Flux-based text-to-image generation, resolving the zero-sum trade-off between identity fidelity and prompt editability.
      - Built <b>TypemovieInfer</b>, a high-performance inference framework combining Para-Attention parallelism, KV cache, and FP8 quantization — pushed Wan2.1-14b-720p video generation onto consumer GPUs with ~4× speed-up.
      - Drove identity-consistent video generation in <b>homture</b> via end-to-end data loops, LoRA training, and continual SFT/DPO iteration on motion and identity quality.
      - Designed <b>超级制图</b> layer parsing pipeline (Grounding-SAM + SAM 2.1, text-layer separation, image restoration) and inpainting-based watermark / object removal for production scenes.

  - title: Algorithm Engineer (Tech Lead)
    company: Suning
    department: Computer Vision Algorithm Group
    location: Nanjing, China
    period: 2019.7 - 2024.11
    description:
      - Led <b>木牛流马 (Mu Niu Liu Ma)</b> — one of China's earliest intelligent creative production platforms (benchmarked against Alibaba 鹿班 / JD 羚珑) — covering Smartbanner intelligent layout, hero-image / social-share image generation, and intelligent layer parsing.
      - Owned the Suning AIGC platform: ControlNet / Inpainting / IP-Adapter / InstanceID at production scale; e-commerce reference-image style transfer, virtual try-on, and ID-controlled portrait generation.
      - Trained the Suning e-commerce foundation model <b>灵思 (LingSi)</b> (LLM) and the multimodal e-commerce LLM (built EcommerceOCRBench for evaluation); shipped the platform through national 网信办 备案 in 2024.12.
      - Built OCR (general + finance-document specialised, TPS 7→18), PS-tamper detection (dual-path RGB+ELA, Accuracy 0.804), 2D lip-sync digital humans, intelligent creative ranking (autoco + AllRank, +10% CTR online), and video remix engines.
      - Saved RMB 3M+/year through the PS-tamper detection project; project awarded <i>Suning Outstanding Employee</i>.

education:
  - degree: M.S. in Surveying and Mapping Engineering
    school: Hefei University of Technology
    period: 2016.9 - 2019.6
    description: Research focused on deep learning for remote sensing image processing. Secretary of the 3rd Party Branch of the College. Outstanding graduate with thesis nominated for excellent graduation thesis. ESI top 1% paper.

  - degree: B.S.
    school: Liaoning Technical University
    period: 2012.9 - 2016.6

social_links:
  - name: Google Scholar
    url: https://scholar.google.com/citations?user=on_b6MMAAAAJ
    icon: ai ai-google-scholar
  - name: GitHub
    url: https://github.com/leeguandong
    icon: fab fa-github
  - name: CSDN
    url: https://blog.csdn.net/u012193416
    icon: fas fa-blog
  - name: Zhihu
    url: https://www.zhihu.com/people/li-xin-52-81
    icon: fab fa-zhihu
  - name: Email
    url: mailto:leeguandon@gmail.com
    icon: fas fa-envelope
---

I am an Algorithm Engineer at iFlytek (Consumer Business Group · AI Marketing), driving native large-model AIGC research for production-grade products including [**讯飞绘镜 (Typemovie)**](https://typemovie.art), **homture**, **超级制图**, and **讯飞绘文**.

From 2019 to 2024 I led algorithm work in Suning's CV group, covering the **木牛流马 (Mu Niu Liu Ma)** intelligent creative production platform, the Suning AIGC platform, the e-commerce foundation model **灵思 (LingSi)**, OCR, PS-tamper detection, and 2D lip-sync digital humans.

Academically, my Master's at Hefei University of Technology focused on deep learning for hyperspectral remote sensing — work that produced an [ESI top-1% paper](https://ieeexplore.ieee.org/abstract/document/8784389/) and multiple publications in IEEE TGRS / J-STARS / Remote Sensing Letters. I hold 10+ Chinese invention patents, maintain ComfyUI workflows on [OpenArt](https://openart.ai/workflows/profile/leeguandong) with 124k+ downloads, write long-form AIGC tutorials on [CSDN](https://liguandong.blog.csdn.net/) (12k+ followers), and have accumulated ~493 Google Scholar citations across both academic and industrial research.
