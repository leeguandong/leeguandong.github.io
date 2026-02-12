---
layout: project
permalink: /project/
title: Project
nav: true

sections:
  - title: "AIGC Platform"
    projects:
      - title: "SN AI Platform"
        images:
          - "assets/img/sn_ai.png"
          - "assets/img/sd_eval.png"
          - "assets/img/update.png"
        desc: "Provide AIGC services including image/video generation based on diffusion models, LLM, etc., covering model photo/product photo/poster image/anime avatar generation, control ID type generation, marketing short video generation for combination fission, lip shape-driven virtual e-commerce live streaming digital humans, face swapping, and script generation for voice-over marketing."
      - title: "E-Commerce Inpainting with Mask Guidance in Controlnet for Reducing Overcompletion"
        images:
          - "assets/img/ecommerceinpainting.png"
        desc: "E-commerce image generation has always been one of the core demands in the e-commerce field. The goal is to restore the missing background that matches the main product given. In the post-AIGC era, diffusion models are primarily used to generate product images, achieving impressive results. This paper systematically analyzes and addresses a core pain point in diffusion model generation: overcompletion, which refers to the difficulty in maintaining product features. We propose two solutions: 1. Using an instance mask fine-tuned inpainting model to mitigate this phenomenon; 2. Adopting a train-free mask guidance approach, which incorporates refined product masks as constraints when combining ControlNet and UNet to generate the main product, thereby avoiding overcompletion of the product. Our method has achieved promising results in practical applications and we hope it can serve as an inspiring technical report in this field."
        links:
          - label: "arXiv"
            url: "https://arxiv.org/abs/2409.09681"
      - title: "Training-Free Style Consistent Image Synthesis with Condition and Mask Guidance in E-Commerce"
        images:
          - "assets/img/train-free-mask-guidance.png"
        desc: "Generating style-consistent images is a common task in the e-commerce field, and current methods are largely based on diffusion models, which have achieved excellent results. This paper introduces the concept of the QKV (query/key/value) level, referring to modifications in the attention maps (self-attention and cross-attention) when integrating UNet with image conditions. Without disrupting the product's main composition in e-commerce images, we aim to use a train-free method guided by pre-set conditions. This involves using shared KV to enhance similarity in cross-attention and generating mask guidance from the attention map to cleverly direct the generation of style-consistent images. Our method has shown promising results in practical applications."
        links:
          - label: "arXiv"
            url: "https://arxiv.org/abs/2409.04750"

  - title: "Intelligent Creative Platform"
    projects:
      - title: "Iwogh Platform"
        images:
          - "assets/img/platform.png"
        desc: "Iwogh is an internal creative design platform at Suning, which includes three main modules: intelligent parsing, intelligent creation, and intelligent optimization. It also encompasses a series of real-time creative tools, providing comprehensive support for Suning's creative business."
      - title: "Intelligent Parsing"
        images:
          - "assets/img/intelligent_parsing_1.png"
          - "assets/img/intelligent_parsing_2.png"
        desc: "In the industrial e-commerce landscape, creative designs such as banners and posters are ubiquitous. Extracting structured semantic information from creative e-commerce design materials (manuscripts crafted by designers) to obtain design semantics represents a core challenge in the realm of intelligent design. In this paper, we propose a comprehensive automated framework for intelligently parsing creative materials. This framework comprises material recognition, preprocess, smartname, and label layers. The material recognition layer consolidates various detection and recognition interfaces, covering business aspects including detection of auxiliary areas within creative materials and layer-level detection, alongside label identification. Algorithmically, it encompasses a variety of coarse-to-fine methods such as Cascade RCNN, GFL, and other models. The preprocess layer involves filtering creative layers and grading creative materials. The smartname layer achieves intelligent naming for creative materials, while the label layer covers multi-level tagging for creative materials, enabling tagging at different hierarchical levels. Intelligent parsing constitutes a complete parsing framework that significantly aids downstream processes such as intelligent creation, creative optimization, and material library construction. Within the practical business applications at Suning, it markedly enhances the exposure, circulation, and click-through rates of creative materials, expediting the closed-loop production of creative materials and yielding substantial benefits."
        links:
          - label: "arXiv"
            url: "https://arxiv.org/abs/2312.17283"
      - title: "Smartbanner"
        images:
          - "assets/img/smartbanner.png"
        desc: "Companies use banners extensively to promote their products, and the intelligent automatic synthesis of banners is a challenging event. Under the premise of inputting only a small amount of information such as product, text and size, it can synthesize styles with high freedom and richness, but at the same time, it must satisfy the design specifications of advertisers for advertising and scenes. We propose an intelligent banner design framework that strikes a balance between creative freedom and design rules, called smartbanner. Smartbanner consists of planner, actuator, adjuster and generator. The banner is synthesized through the combined framework, which fully liberates the designer and reduces the threshold and cost of design. It increases the click-through rate by 30%, improves the human efficiency of designers by 500% under the condition of ensuring the quality of creation, and synthesizes hundreds of millions of pictures in batches throughout the year."
        links:
          - label: "arXiv"
            url: "https://arxiv.org/abs/2303.10325"
      - title: "ADCT"
        images:
          - "assets/img/adct1.png"
          - "assets/img/adct2.png"
        desc: "Ad creative is one of the main mediums for e-commerce advertising. Ad creative with good visuals may increase a product's click-through rate(ctr). In recent years, unlike artificially produced ad creatives, advertising platforms can automatically synthesize ad creatives, and each type of element can be arbitrarily specified. Advertisers only need to provide basic materials to synthesize a large number of potential ad creatives in batches. But with limited real-time feedback, it is difficult to accurately estimate the ctr of creatives. In our scenario, in addition to a large number of sparse samples, we also face the problem of ambiguous samples. In our approach we decouple this dynamic creative optimization into two stages, a cascaded structure that can trade off between effectiveness and efficiency. In the first stage, we train an automatic creative optimization architecture based on autoco to simulate complex interactions between creative elements. Although we obtained the ranking of different creatives under a sku, because we bucketed and merged historical data according to periods, this confuses the ctr diversity of the same ad creatives on different days and weakens the ability to separate ambiguous samples. Therefore, we propose a transformer-based rerank model. With the help of the rank model, we propose a distillation method to learn the relative order of ideas and extract the ranking knowledge to guide the rerank learning. The creative order soft labels under each sku are generated by the rank model to alleviate the dilemma that a large number of under-represented creatives cannot obtain real labels. Through the knowledge diffusion of rerank, the ambiguous samples are associated with the positive and negative samples. Cascade rerank and autoco to output the estimated value of the synthetic ad image. In the second stage, we designed a bandit model, and the bandit selected one of the output ad of the first stage for timely delivery. Experimental results show that our method can outperform competing baselines in terms of sctr. Online A/B testing shows that our method improves ctr by 10% compared to the baseline."
        links:
          - label: "arXiv"
            url: "https://arxiv.org/abs/2312.01295"
      - title: "Tamper Detection"
        images:
          - "assets/img/tamper1.png"
          - "assets/img/tamper2.png"
        desc: "Document tamper detection has always been an important aspect of tamper detection. Before the advent of deep learning, document tamper detection was difficult. We have made some explorations in the field of text tamper detection based on deep learning. Our Ps tamper detection method includes three steps: feature assistance, audit point positioning, and tamper recognition. It involves hierarchical filtering and graded output (tampered/suspected tampered/untampered). By combining artificial tamper data features, we simulate and augment data samples in various scenarios (cropping with noise addition/replacement, single character/space replacement, smearing/splicing, brightness/contrast adjustment, etc.). The auxiliary features include exif/binary stream keyword retrieval/noise, which are used for branch detection based on the results. Audit point positioning uses detection frameworks and controls thresholds for high and low density detection. Tamper recognition employs a dual-path dual-stream recognition network, with RGB and ELA stream feature extraction. After dimensionality reduction through self-correlation percentile pooling, the fused output is processed through vlad, yielding an accuracy of 0.604, recall of 0.659, and precision of 0.913."
        links:
          - label: "arXiv"
            url: "https://arxiv.org/abs/2402.13545"
---
