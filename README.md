# Awesome Stable Diffusion [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of high-quality tools, UIs, libraries, and resources for Stable Diffusion and modern diffusion image models.

## Contents

- [Start here](#start-here)
- [UIs](#uis)
- [Libraries](#libraries)
- [Training](#training)
- [Control and conditioning](#control-and-conditioning)
- [Upscale and restore](#upscale-and-restore)
- [Local and edge](#local-and-edge)
- [Integrations](#integrations)
- [Video and 3D](#video-and-3d)
- [Desktop apps](#desktop-apps)
- [Contributing](#contributing)

## Start here

- [ComfyUI](https://github.com/comfyanonymous/ComfyUI) - Modular node-based GUI and backend for diffusion models.
- [Diffusers](https://github.com/huggingface/diffusers) - State-of-the-art diffusion models library for image, video, and audio in PyTorch.
- [kohya_ss](https://github.com/bmaltais/kohya_ss) - GUI for training LoRA and DreamBooth models.

## UIs

- [ComfyUI](https://github.com/comfyanonymous/ComfyUI) - Most powerful modular diffusion GUI with a graph/nodes interface.
- [Stable Diffusion web UI](https://github.com/AUTOMATIC1111/stable-diffusion-webui) - Widely used Gradio-based Stable Diffusion web UI.
- [automatic](https://github.com/vladmandic/automatic) - Opinionated, actively maintained fork of Stable Diffusion WebUI.
- [Fooocus](https://github.com/lllyasviel/Fooocus) - Minimal, user-friendly interface focused on good defaults.
- [InvokeAI](https://github.com/invoke-ai/InvokeAI) - Creative engine aimed at professionals and enthusiasts.
- [ComfyUI-Manager](https://github.com/ltdrdata/ComfyUI-Manager) - Install and manage custom nodes for ComfyUI.
- [SwarmUI](https://github.com/mcmonkeyprojects/SwarmUI) - Modular high-performance web UI for image and video diffusion models.
- [stable-diffusion-webui-forge](https://github.com/lllyasviel/stable-diffusion-webui-forge) - Optimized A1111-based WebUI with improved VRAM management and speed.
- [ComfyUI-KJNodes](https://github.com/kijai/ComfyUI-KJNodes) - Quality-of-life utility and model optimization nodes for ComfyUI.
- [rgthree-comfy](https://github.com/rgthree/rgthree-comfy) - Utility nodes and workflow improvements for ComfyUI.
- [ComfyUI_LayerStyle](https://github.com/chflame163/ComfyUI_LayerStyle) - Photoshop-style layer, mask and compositing nodes for ComfyUI.
- [ComfyUI-Custom-Scripts](https://github.com/pythongosssss/ComfyUI-Custom-Scripts) - Utility and workflow enhancement nodes for ComfyUI.

## Libraries

- [Diffusers](https://github.com/huggingface/diffusers) - Official Hugging Face library for diffusion pipelines and training helpers.
- [LyCORIS](https://github.com/KohakuBlueleaf/LyCORIS) - Extended LoRA-style adapters beyond conventional methods.
- [flux](https://github.com/black-forest-labs/flux) - Official inference code for FLUX.1 open-weight models.
- [DiffSynth-Studio](https://github.com/modelscope/DiffSynth-Studio) - Unified diffusion engine with VRAM management, training and inference for FLUX, Wan and SD models.

## Training

- [sd-scripts](https://github.com/kohya-ss/sd-scripts) - Core training scripts for DreamBooth and LoRA.
- [kohya_ss](https://github.com/bmaltais/kohya_ss) - Popular GUI wrapper around kohya training scripts.
- [LyCORIS](https://github.com/KohakuBlueleaf/LyCORIS) - Alternative network architectures for efficient fine-tuning.
- [ai-toolkit](https://github.com/ostris/ai-toolkit) - All-in-one training toolkit for FLUX/SDXL and other diffusion models.
- [OneTrainer](https://github.com/Nerogar/OneTrainer) - Unified GUI and scripts for training diffusion models including FLUX and SDXL.
- [musubi-tuner](https://github.com/kohya-ss/musubi-tuner) - Kohya training scripts specialized for video diffusion models.

## Control and conditioning

- [ControlNet](https://github.com/lllyasviel/ControlNet) - Add spatial conditions (pose, depth, edges) to diffusion models.
- [sd-webui-controlnet](https://github.com/Mikubill/sd-webui-controlnet) - ControlNet extension for AUTOMATIC1111 WebUI.
- [sd-webui-additional-networks](https://github.com/kohya-ss/sd-webui-additional-networks) - Load LoRA and extra networks in A1111 WebUI.
- [adetailer](https://github.com/Bing-su/adetailer) - Automatic detection and detailing extension for WebUI.
- [ComfyUI_IPAdapter_plus](https://github.com/cubiq/ComfyUI_IPAdapter_plus) - Reference IP-Adapter nodes for image prompt conditioning in ComfyUI.
- [comfyui_controlnet_aux](https://github.com/Fannovel16/comfyui_controlnet_aux) - Auxiliary preprocessors for ControlNet hint images in ComfyUI.
- [x-flux-comfyui](https://github.com/XLabs-AI/x-flux-comfyui) - ComfyUI nodes for FLUX ControlNets and LoRAs.
- [ComfyUI-Advanced-ControlNet](https://github.com/Kosinkadink/ComfyUI-Advanced-ControlNet) - Advanced ControlNet nodes with timestep scheduling and attention masks.

## Upscale and restore

- [Real-ESRGAN](https://github.com/xinntao/Real-ESRGAN) - Practical AI image upscaler commonly used with Stable Diffusion.
- [IOPaint](https://github.com/Sanster/IOPaint) - Inpainting and object removal powered by modern AI models.
- [ComfyUI-Impact-Pack](https://github.com/ltdrdata/ComfyUI-Impact-Pack) - Detector, detailer, and upscaler nodes for image enhancement in ComfyUI.

## Local and edge

- [stable-diffusion.cpp](https://github.com/leejet/stable-diffusion.cpp) - Stable Diffusion and Flux inference in pure C/C++.
- [MochiDiffusion](https://github.com/godly-devotion/MochiDiffusion) - Native Stable Diffusion on Mac.
- [web-stable-diffusion](https://github.com/mlc-ai/web-stable-diffusion) - Run Stable Diffusion in the browser with WebGPU.
- [ComfyUI-GGUF](https://github.com/city96/ComfyUI-GGUF) - GGUF quantization support for native ComfyUI models (FLUX/SD3).
- [mflux](https://github.com/filipstrand/mflux) - Native MLX port of FLUX and related models for Apple Silicon.
- [Mold](https://github.com/utensils/mold) - CLI-native local AI image/video/3D generation in Rust/Candle with CUDA/Metal and MCP.
- [ComfyUI-nunchaku](https://github.com/nunchaku-ai/ComfyUI-nunchaku) - ComfyUI nodes for 4-bit SVDQuant inference of FLUX and related models.

## Integrations

- [Krita AI Diffusion](https://github.com/Acly/krita-ai-diffusion) - Generate and inpaint with AI inside Krita.
- [Dream textures](https://github.com/carson-katri/dream-textures) - Stable Diffusion integration for Blender.
- [Auto-Photoshop-StableDiffusion-Plugin](https://github.com/AbdullahAlfaraj/Auto-Photoshop-StableDiffusion-Plugin) - Generate images inside Photoshop via A1111 backend.

## Video and 3D

- [stable-diffusion-videos](https://github.com/nateraw/stable-diffusion-videos) - Create videos by morphing between text prompts in latent space.
- [i2vgen-xl](https://github.com/ali-vilab/i2vgen-xl) - Video generation ecosystem built on diffusion models.
- [Stable-Dreamfusion](https://github.com/ashawkey/stable-dreamfusion) - Text-to-3D generation powered by Stable Diffusion.
- [ComfyUI-WanVideoWrapper](https://github.com/kijai/ComfyUI-WanVideoWrapper) - Wrapper nodes for Wan video generation models in ComfyUI.
- [ComfyUI-VideoHelperSuite](https://github.com/Kosinkadink/ComfyUI-VideoHelperSuite) - Nodes for video loading, combining, batching, and frame utilities in ComfyUI.
- [ComfyUI-Frame-Interpolation](https://github.com/Fannovel16/ComfyUI-Frame-Interpolation) - Video frame interpolation nodes supporting RIFE, FILM, GMFSS and other VFI models.
- [ComfyUI-3D-Pack](https://github.com/MrForExample/ComfyUI-3D-Pack) - Nodes for 3D mesh, 3DGS, and NeRF generation from images in ComfyUI.

## Desktop apps

- [Easy Diffusion](https://github.com/easydiffusion/easydiffusion) - Simple one-click local installation for non-technical users.
- [Off Grid AI Desktop](https://github.com/off-grid-ai/off-grid-ai-desktop) - Local-first macOS app for on-device image generation.
- [Imference Desktop](https://github.com/Publikey/imference-desktop) - Local desktop app supporting SDXL, SD 1.5, FLUX, and custom weights.
- [Image MetaHub](https://github.com/LuqP2/Image-MetaHub) - Search and organize AI images by prompt, model, LoRA, and workflow metadata.
- [ImageBench](https://github.com/dh7/image-bench-ai) - Open benchmark ranking text-to-image models with published outputs.
- [StabilityMatrix](https://github.com/LykosAI/StabilityMatrix) - Multi-platform package manager and launcher for ComfyUI, Forge, A1111 and training tools.

## Contributing

Contributions welcome. Please:

- Add only actively maintained, high-quality projects.
- Use the format: `- [Name](url) - Short neutral description.`
- Place items in the most relevant section.
- Open a pull request with a clear reason for the addition.

See the [Awesome manifesto](https://github.com/sindresorhus/awesome/blob/main/awesome.md) for curation guidelines.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related or neighboring rights to this work.
