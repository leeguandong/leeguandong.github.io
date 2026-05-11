---
layout: page
permalink: /code/
title: Code
nav: true

---

### AIGC

- **Summary**
  - [Awesome-Chinese-Stable-Diffusion](https://github.com/leeguandong/Awesome-Chinese-Stable-Diffusion) :Focus on some basic models of Chinese stable diffusion.    
- **LLM**
  - [EcommerceLLM](https://github.com/leeguandong/EcommerceLLM) :E-commerce scene LLM fine-tuned based on qwen1.5 and llama3.     
  - [EcommerceLLMQwen2.5](https://github.com/leeguandong/EcommerceLLMQwen2.5) :A Qwen2.5 series e-commerce large language model fine-tuned on e-commerce data.
  - [MiniLLaMA3](https://github.com/leeguandong/MiniLLaMA3) :A mini version of Llama 3, covering the entire pipeline from data construction (0-1), tokenizer training, pre-training (PT), supervised fine-tuning (SFT), and reinforcement learning from human feedback (RLHF).
  - [ECOMCPM](https://github.com/leeguandong/ECOMCPM) :Language model trained on e-commerce data from 'What's Worth Buying' website, a Chinese pretrained model similar to GPT2.    
  - [UniFlow](https://github.com/leeguandong/UniFlow) :Unified large language model, multimodal, FLUX generation interface, FastAPI deployment, configurable deployment services.
  - [Medical_R1](https://github.com/leeguandong/Medical_R1) :Fine-tune deepseek-r1 on medical data.
  - [EcommerceLLMQwen3](https://github.com/leeguandong/EcommerceLLMQwen3) :Qwen3 Series E-commerce Large Model Fine-tuned with E-commerce Data E-commerce Large Model after E-commerce Data SFT.
- **LMM**
  - [XrayLLaVA](https://github.com/leeguandong/XrayLLaVA) :Xray Large Multi-modal Model, fine-tuned on LLaVA for the Xray's multi-modal large model, using 4 V100 GPUs based on the llava1d6-mistral-7b-instruct model. LLaVA is among the most popular model methodologies and architectures in large multi-modal language models. Fine-tuning LLaVA helps us evaluate and compare the potential of training large multi-modal language models in vertical scenarios. 
  - [XrayQwenVL](https://github.com/leeguandong/XrayQwenVL) : Xray Large Multi-modal Model, fine-tuned on QwenVL for Xray's multi-modal large model, using 4 V100 GPUs based on the qwenvl-chat model for fine-tuning.    
  - [XrayQwen2VL](https://github.com/leeguandong/XrayQwen2VL) :Fine-tuned on Qwen2vl using the Xray open-source dataset. The training LORA weights have been released for academic research. For inference, the original qwen2-vl-7b-instruct weights need to be loaded separately, and the LORA weights can be merged using llamafactory's merge LORA function. Llamafactory 0.9.0 was used for fine-tuning in this experiment.
  - [EcommerceOCRBench](https://github.com/leeguandong/EcommerceOCRBench) :A larger-scale OCR benchmark dataset for multimodal large language models in e-commerce, modeled after OCRBench.
  - [OCRPaliGemma](https://github.com/leeguandong/OCRPaliGemma) :A multimodal large language model with a focus on OCR text detection.
  - [XrayLLama3.2Vision](https://github.com/leeguandong/XrayLLama3.2Vision) :Xray Large Multi-model Model, based on llama3.2-vision fine-tuning Xray's multi-modal large model, fine-tuned on 4 A800 based on llama3_2-11b-vision-instruct model.
- **SD**
  - [HOME-CLIP](https://github.com/leeguandong/HOME-CLIP) :ChineseCLIP model was fine-tuned on home decoration and furniture data crawled from Visual China.      
  - [HOME-DALLE1](https://github.com/leeguandong/HOME-DALLE1) :DALL-E 1 model for Chinese home decoration and furniture scenes.   
  - [controlnet_aux_add](https://github.com/leeguandong/controlnet_aux_add) :Auxiliary functions of ControlNet, an additional library of huggingface's ControlNet aux, adding preprocessors not present in aux.   
  - [EcommerceSD](https://github.com/leeguandong/EcommerceSD) :A focus on image generation in e-commerce scenarios, including model generation and inpainting.
  - [MaskControlnet](https://github.com/leeguandong/MaskControlnet) :A ControlNet-based generative model conditioned on masks, trained on a massive dataset of e-commerce cutout images (saliency map detection data).
  - [ChatAce](https://github.com/leeguandong/ChatAce) :Picture editing based on flux acp++, mainly character consistency editing.
  - [ChatFlux]([ChatFlux](https://github.com/leeguandong/ChatFlux)) :webui based chatdit, supports generating pictures through conversations.
  - [Typemovie-ParaAttention](https://github.com/typemovie/Typemovie-ParaAttention) :TypeMovie-ParaAttention is an enhanced version of ParaAttention, designed to accelerate Diffusion Transformer (DiT) model inference with context parallelism, dynamic caching, and a new high-performance SageAttention backend.
  - [EditIDv2](https://github.com/typemovie/EditIDv2) :Typemovie's EditIDv2 ensures character identity consistency in complex text-to-image generation, using minimal data for enhanced semantic editing, as shown in IBench tests.
  - [IBench](https://github.com/typemovie/IBench) :Image evaluation system in Editid.
  - [RealtimeFlux](https://github.com/leeguandong/RealtimeFlux) :This is the first model enabling real-time flux-based sketch-to-image generation, akin to Ji Meng's Smart Canvas and Krea.ai's real-time rendering, built on the Nunchaku and Flux framework.
- **Video generation**  
  -  [EcommerceVideoDataset](https://github.com/leeguandong/EcommerceVideoDataset) :A dataset primarily used for creating e-commerce animations.     

- **Digital Human**
  - [Wav2lipAll](https://github.com/leeguandong/Wav2lipAll) :Training a virtual digital human based on wav2lip, with lip shape driving, including data processing procedures, etc. The model includes sizes 96x96, 192x192, 192x288, 288x288.   
  - [TalkingFace](https://github.com/leeguandong/TalkingFace) :Training set for 2D virtual digital human projects similar to wav2lip, geneface++.    


### Comfyui-extension and Stable-diffusion-webui-extension 

- [ComfyUI_AliControlnetInpainting](https://github.com/leeguandong/ComfyUI_AliControlnetInpainting)
- [ComfyUI_CompareModelWeights](https://github.com/leeguandong/ComfyUI_CompareModelWeights)
- [ComfyUI_Diffusers](https://github.com/leeguandong/ComfyUI_Diffusers)
- [ComfyUI_MasaCtrl](https://github.com/leeguandong/ComfyUI_MasaCtrl)
- [ComfyUI_VisualAttentionMap](https://github.com/leeguandong/ComfyUI_VisualAttentionMap)
- [ComfyUI_SelfGuidance](https://github.com/leeguandong/ComfyUI_SelfGuidance)
- [ComfyUI_CrossImageAttention](https://github.com/leeguandong/ComfyUI_CrossImageAttention)
- [ComfyUI_Style_Aligned](https://github.com/leeguandong/ComfyUI_Style_Aligned)
- [ComfyUI_M3Net](https://github.com/leeguandong/ComfyUI_M3Net)
- [ComfyUI_VideoEditing](https://github.com/leeguandong/ComfyUI_VideoEditing)
- [ComfyUI_InternVL2](https://github.com/leeguandong/ComfyUI_InternVL2)
- [ComfyUI_LLaSM](https://github.com/leeguandong/ComfyUI_LLaSM)
- [ComfyUI_Qwen3Omni](https://github.com/leeguandong/ComfyUI_Qwen3Omni)
- [ComfyUI_Gemma3](https://github.com/leeguandong/ComfyUI_Gemma3)
- [ComfyUI_BatchPrompt](https://github.com/leeguandong/ComfyUI_BatchPrompt)
- [ComfyUI_KimiVL](https://github.com/leeguandong/ComfyUI_KimiVL)
- [ComfyUI_FluxLayerDiffuse](https://github.com/leeguandong/ComfyUI_FluxLayerDiffuse)
- [ComfyUI_QWQ32B](https://github.com/leeguandong/ComfyUI_QWQ32B)
- [ComfyUI_FluxAttentionMask](https://github.com/leeguandong/ComfyUI_FluxAttentionMask)
- [ComfyUI_Moonlight](https://github.com/leeguandong/ComfyUI_Moonlight)
- [ComfyUI_DeepSeekVL2](https://github.com/leeguandong/ComfyUI_DeepSeekVL2)
- [ComfyUI_ChatGen](https://github.com/leeguandong/ComfyUI_ChatGen)
- [ComfyUI_1Prompt1Story](https://github.com/leeguandong/ComfyUI_1Prompt1Story)
- [ComfyUI_Cogview4](https://github.com/leeguandong/ComfyUI_Cogview4)
- [ComfyUI_FluxClipWeight](https://github.com/leeguandong/ComfyUI_FluxClipWeight)
- [ComfyUI_CompareModelWeights](https://github.com/leeguandong/ComfyUI_CompareModelWeights)
- [ComfyUI_FluxCustomId](https://github.com/leeguandong/ComfyUI_FluxCustomId)
- [sd_webui_ZeST](https://github.com/leeguandong/sd_webui_ZeST)
- [sd_webui_instantid](https://github.com/leeguandong/sd_webui_instantid)
- [sd_webui_prompt_translator_architecture](https://github.com/leeguandong/sd_webui_prompt_translator_architecture)
- [sd_webui_musetalk](https://github.com/leeguandong/sd_webui_musetalk)    
- [sd_webui_tokenize_anything](https://github.com/leeguandong/sd_webui_tokenize_anything)    
- [sd_webui_ootdiffusion](https://github.com/leeguandong/sd_webui_ootdiffusion)     
- [sd_webui_animate_anything](https://github.com/leeguandong/sd_webui_animate_anything)    
- [sd_webui_powerpaint](https://github.com/leeguandong/sd_webui_powerpaint)    
- [sd_webui_outpainting](https://github.com/leeguandong/sd_webui_outpainting)     
- [sd_webui_matting](https://github.com/leeguandong/sd_webui_matting)    
- [sd_webui_reatime_lcm_canvas](https://github.com/leeguandong/sd_webui_realtime_lcm_canvas)    
- [sd_webui_beautifulprompt](https://github.com/leeguandong/sd_webui_beautifulprompt)    
- [sd_webui_lama](https://github.com/leeguandong/sd_webui_lama)    
- [sd_webui_sghm](https://github.com/leeguandong/sd_webui_sghm)    

### CV and Creatives

- **CV**
  - [Camera_blur_detection](https://github.com/leeguandong/Camera_blur_detection) :Perform region detection on photos captured by the camera and provide a blur determination, C++ code, using FastDeploy for multi-platform deployment, VS2019.
  - [mmdetection_add](https://github.com/leeguandong/mmdetection_add) :Add the implemented object detection algorithms, including EfficientDet, YOLOv4/v5, etc.
  - [mmclassification_add](https://github.com/leeguandong/mmclassification_add) :Add the implemented classification algorithms to mmcls, including GhostNet, etc.
  - [Answer_card_identification](https://github.com/leeguandong/Answer_card_identification) :Answer Sheet Project, intelligent grading.
  - [mmsynth](https://github.com/leeguandong/mmsynth) :Reorganized text_render in mm format.
- **Creatives**
  - [TextErasing](https://github.com/leeguandong/TextErasing) :Text erasing algorithm, Alibaba's self-supervised text erasing with controllable image synthesis algorithm, will provide two versions.  
  - [AllRank](https://github.com/leeguandong/AllRank) :Learn-to-rank framework, the re-ranking module in recall/coarse ranking/fine ranking/re-ranking, previously mainly used for dynamic creative optimization to re-rank features including images.   
  - [mmgeneration_add](https://github.com/leeguandong/mmgeneration_add) :GAN and other traditional image generation algorithms.   
  - [Xiaobao](https://github.com/leeguandong/Xiaobao) :VideoClip, a video editing application. 

### Deployment Acceleration

- [KuaiZai](https://github.com/leeguandong/KuaiZai) :Mainly some project codes for multi-platform deployment.
- [PlateRec](https://github.com/leeguandong/PlateRec) :License plate recognition, based on PaddleOCR, ONNX Runtime, C++.
- [Yolov5_rknnlite2](https://github.com/leeguandong/Yolov5_rknnlite2) :YOLOv5 pedestrian detection, deployed on RK3588, RKNLite2. 

### Hyperspectral classification     

- [DGCNet-for-HSI](https://github.com/leeguandong/DGCNet-for-HSI)     
- [FSKNet-for-HSI](https://github.com/leeguandong/FSKNet-for-HSI)   
- [STNet-for-HSI](https://github.com/leeguandong/STNet-for-HSI)
- [WCNet-for-HSI](https://github.com/leeguandong/WCNet-for-HSI)
- [SGDSCNet-for-HSI](https://github.com/leeguandong/SGDSCNet-for-HSI)
- [MVNet-for-HSI](https://github.com/leeguandong/MVNet-for-HSI)
- [KANet-for-HSI](https://github.com/leeguandong/KANet-for-HSI)
- [EKGNet-for-HSI](https://github.com/leeguandong/EKGNet-for-HSI)
- [DACNet-for-HSI](https://github.com/leeguandong/DACNet-for-HSI)
- [mmhyperspectral](https://github.com/leeguandong/mmhyperspectral)

###  Leraning

- [Interview-code-practice-python](https://github.com/leeguandong/Interview-code-practice-python) 
- [Paper-Learning](https://github.com/leeguandong/Paper-Learning)  

