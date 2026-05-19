---
layout: project
permalink: /project/
title: Project
nav: true

sections:
  - title: "Generative AI Research"
    projects:
      - title: "EditID v1/v2 — Training-Free Editable Identity Customization"
        desc: "Two-stage framework for personalized text-to-image generation on Flux. v1 introduces a training-free identity-feature decoupling scheme that severs the zero-sum trade-off between identity fidelity and prompt editability. v2 adds a data-lubrication mechanism that pushes data efficiency further. Self-built IBench evaluation system shows SOTA on identity preservation and editability simultaneously."
        links:
          - label: "EditID arXiv"
            url: "https://arxiv.org/abs/2503.12526"
          - label: "EditIDv2 arXiv"
            url: "https://arxiv.org/abs/2509.05659"
          - label: "EMNLP 2025 Findings"
            url: "https://arxiv.org/abs/2503.12526"

      - title: "Training-Free Identity Injection for Personalized Generation"
        desc: "Family of training-free methods that inject reference identity into text-to-image diffusion without per-subject fine-tuning. DVI disentangles semantic and visual identity components; FlexID modulates injection intent across spatial regions; Inject Where It Matters adapts injection to spatially-relevant tokens; Dual-Channel Attention Guidance refines control under multi-condition prompts."
        links:
          - label: "DVI arXiv"
            url: "https://arxiv.org/abs/2512.18964"
          - label: "FlexID arXiv"
            url: "https://arxiv.org/abs/2602.07554"
          - label: "Inject arXiv"
            url: "https://arxiv.org/abs/2602.13994"
          - label: "Dual-Channel arXiv"
            url: "https://arxiv.org/abs/2602.18022"

      - title: "Image Editing on Flow-based Diffusion Transformers"
        desc: "A series of training-free editing methods over MMDiT / Flux architectures, exploring how attention routing, temporal-channel modulation, and semantics-aware region isolation give precise edit control without retraining. Includes AdaEdit (flow-based image editing), Edit Spillover (a probe for whether editing models understand world relations), AttnRouter (per-category attention routing on MMDiT), Edit Fidelity Field (region isolation for scene text editing), and PhysEdit (physically-consistent region-aware edits)."
        links:
          - label: "AdaEdit"
            url: "https://arxiv.org/abs/2603.21615"
          - label: "Edit Spillover"
            url: "https://arxiv.org/abs/2603.17876"
          - label: "AttnRouter"
            url: "https://arxiv.org/abs/2605.01480"
          - label: "Edit Fidelity Field"
            url: "https://arxiv.org/abs/2604.17500"
          - label: "PhysEdit"
            url: "https://arxiv.org/abs/2605.00707"

      - title: "Diffusion Transformer Inference Acceleration"
        desc: "Inference framework and per-method accelerations for production diffusion / video models. TypemovieInfer is a unified consumer-GPU runtime combining Para-Attention parallelism, KV cache, and FP8 quantization, delivering ~4x speed-up on Wan2.1-14B-720p. LayerCache exploits layer-wise velocity heterogeneity in flow matching. Frequency-Aware Caching gives error-bounded caching for DiT generation. FastUSP is a multi-level collaborative acceleration framework for distributed inference."
        links:
          - label: "LayerCache"
            url: "https://arxiv.org/abs/2604.16492"
          - label: "Frequency-Aware Caching"
            url: "https://arxiv.org/abs/2603.05315"
          - label: "FastUSP"
            url: "https://arxiv.org/abs/2602.10940"

  - title: "Hyperspectral Image Classification"
    projects:
      - title: "Hyperspectral Image Classification — 8-year Research Line"
        desc: "Long-running research line on deep architectures for hyperspectral remote sensing imagery, covering 3D-CNN, dense connections, dynamic group convolution, selective kernels, KAN, Mamba-Transformer, dynamic snake, and wavelet receptive fields. The lead paper alone (Multi-scale Dense Networks, IEEE TGRS 2019) has 200+ Google Scholar citations; the series spans IEEE TGRS, JSTARS, JARS, Remote Sensing Letters, Spectroscopy Letters, Arabian J. Sci. & Eng., International J. of Image and Data Fusion, and 中国图象图形学报."
        links:
          - label: "TGRS (Multi-scale Dense)"
            url: "https://ieeexplore.ieee.org/document/8784389"
          - label: "JSTARS (Deep Feature Aggregation)"
            url: "https://ieeexplore.ieee.org/document/9184224"
          - label: "MVNet (Mamba-Transformer)"
            url: "https://arxiv.org/abs/2507.04409"
          - label: "STNet (Transformer)"
            url: "https://arxiv.org/abs/2506.08324"
          - label: "GitHub series"
            url: "https://github.com/leeguandong?tab=repositories&q=HSI"

  - title: "Suning AIGC Platform"
    projects:
      - title: "Suning AIGC Platform"
        images:
          - "assets/img/sn_ai.png"
          - "assets/img/sd_eval.png"
          - "assets/img/update.png"
        desc: "Provides AIGC services including image/video generation based on diffusion models and LLMs, covering model photo / product photo / poster image / anime avatar generation, controlled-ID type generation, marketing short-video generation for combination fission, lip-sync digital humans for e-commerce live streaming, face swapping, and script generation for voice-over marketing."

      - title: "E-Commerce Inpainting with Mask Guidance in ControlNet"
        images:
          - "assets/img/ecommerceinpainting.png"
        desc: "E-commerce image generation has long been a core demand, with the goal of restoring the missing background while preserving the foreground product. This work addresses overcompletion — the difficulty in maintaining product features under diffusion-model inpainting — via two solutions: (1) an instance-mask fine-tuned inpainting model and (2) a train-free mask-guidance approach that introduces refined product masks as constraints when combining ControlNet with UNet, preventing the model from over-rebuilding the main product."
        links:
          - label: "arXiv"
            url: "https://arxiv.org/abs/2409.09681"

      - title: "Training-Free Style-Consistent Image Synthesis with Condition & Mask Guidance"
        images:
          - "assets/img/train-free-mask-guidance.png"
        desc: "Train-free framework for style-consistent e-commerce image generation. Operates at the QKV level inside attention (self- and cross-attention), using shared KV to amplify similarity in cross-attention and using attention maps to generate mask guidance that steers style-consistent generation while preserving the product's main composition."
        links:
          - label: "arXiv"
            url: "https://arxiv.org/abs/2409.04750"

  - title: "Intelligent Creative Platform"
    projects:
      - title: "Iwogh Platform (木牛流马)"
        images:
          - "assets/img/platform.png"
        desc: "Iwogh is Suning's internal creative design platform with three core modules: intelligent parsing, intelligent creation, and intelligent optimization, plus a set of real-time creative tools. One of China's earliest intelligent creative production platforms, benchmarked against Alibaba 鹿班 and JD 羚珑."

      - title: "Intelligent Parsing"
        images:
          - "assets/img/intelligent_parsing_1.png"
          - "assets/img/intelligent_parsing_2.png"
        desc: "Automated framework for parsing creative materials (banners, posters, designer manuscripts) into structured design semantics. Comprises material recognition, preprocess, smartname, and label layers — using detection (Cascade RCNN, GFL), layer-level filtering, intelligent naming, and multi-level tagging. Significantly boosts downstream intelligent creation and creative optimization in Suning's production scenarios, lifting creative material exposure, circulation, and click-through rates."
        links:
          - label: "arXiv"
            url: "https://arxiv.org/abs/2312.17283"

      - title: "Smartbanner"
        images:
          - "assets/img/smartbanner.png"
        desc: "Intelligent banner design framework that balances creative freedom against design rules. With only product, copy and size as inputs, Smartbanner's planner / actuator / adjuster / generator pipeline synthesizes high-freedom, design-compliant banners. Deployed at production scale, lifting CTR by 30%, designer efficiency by 500%, and synthesizing hundreds of millions of images annually."
        links:
          - label: "arXiv"
            url: "https://arxiv.org/abs/2303.10325"

      - title: "ADCT — Dynamic Creative Optimization under Sparse/Ambiguous Samples"
        images:
          - "assets/img/adct1.png"
          - "assets/img/adct2.png"
        desc: "Two-stage cascade for ad-creative CTR estimation under sparse and ambiguous samples. Stage 1: autoco-based ranking + a transformer-based rerank trained with rank-distillation soft labels to extract creative order knowledge and link ambiguous samples to positive/negative pairs. Stage 2: a bandit selects from Stage 1's top-N for live serving. Online A/B testing shows +10% CTR vs baseline."
        links:
          - label: "arXiv"
            url: "https://arxiv.org/abs/2312.01295"

      - title: "PS Tamper Detection"
        images:
          - "assets/img/tamper1.png"
          - "assets/img/tamper2.png"
        desc: "Three-step pipeline (feature-assist, audit-point localization, tamper recognition) for document Photoshop-tamper detection with graded output (tampered / suspected / untampered). Uses EXIF + binary-stream + noise feature assistance, detection frameworks for localization, and a dual-path dual-stream (RGB + ELA) recognition network with self-correlation percentile pooling and NetVLAD fusion. Accuracy 0.804 on internal benchmarks; saved Suning RMB 3M+/year."
        links:
          - label: "arXiv"
            url: "https://arxiv.org/abs/2402.13545"
---
