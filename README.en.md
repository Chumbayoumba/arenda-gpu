<div align="center">

# GPU server rental by the minute — RTX 4090, RTX 5090, A100, H100

**[gpu.nz](https://gpu.nz/en?utm_source=github&utm_medium=readme&utm_campaign=arenda-gpu)** — cloud GPUs for AI, rendering and model training. Thousands of GPUs in 60+ countries, pay with crypto or rubles, a server ready in a couple of minutes.

[![GPU catalog](https://img.shields.io/badge/catalog-5000%2B_GPUs-b7ff36?style=for-the-badge&labelColor=0a0b0d)](https://gpu.nz/en/gpu?utm_source=github&utm_medium=readme&utm_campaign=arenda-gpu)
[![Billing](https://img.shields.io/badge/billing-per_minute-b7ff36?style=for-the-badge&labelColor=0a0b0d)](https://gpu.nz/en/pricing?utm_source=github&utm_medium=readme&utm_campaign=arenda-gpu)
[![Payments](https://img.shields.io/badge/pay_with-USDT_·_TON_·_BTC-b7ff36?style=for-the-badge&labelColor=0a0b0d)](https://gpu.nz/en/pricing?utm_source=github&utm_medium=readme&utm_campaign=arenda-gpu)

[Русская версия](README.md)

<img src="images/hero.png" alt="gpu.nz — GPU server rental billed by the minute" width="100%">

</div>

## What gpu.nz is

gpu.nz rents servers with NVIDIA GPUs. Pick a card in the catalog, press «Rent», and a few minutes later you have a server with SSH, JupyterLab and a ready environment: ComfyUI, Stable Diffusion, Ollama, vLLM, PyTorch or a chat with a language model. Billing is **by the minute** from your balance, with no minimum term and no subscription: stop the server and the GPU meter stops.

- **Hourly and per-minute GPU rental**: pay only while it runs, with the price locked at launch.
- **More than a hundred GPU models**, from the RTX 3060 to the H100, H200, B200 and RTX PRO 6000 96 GB.
- **Crypto payments**: USDT, TON, BTC and more, plus ruble methods for Russia.
- **One-click templates**: an AI app starts without installing drivers or CUDA.
- **API, CLI and a Telegram bot**: rent a GPU from a script, a terminal or Telegram.

## GPU rental prices

<img src="images/prices.png" alt="GPU rental prices: RTX 3060, RTX 4090, RTX 5090, L40S, H100, H200, B200, B300" width="420" align="right">

The lowest price per GPU-hour on 17 October 2026, from the free servers in the catalog (rubles; the site shows dollars in its English version):

| GPU | Memory | From |
|---|---|---|
| RTX 3060 | 12 GB | 10 ₽/h |
| RTX A4000 | 16 GB | 14 ₽/h |
| RTX 3090 | 24 GB | 22 ₽/h |
| RTX 4090 | 24 GB | 25 ₽/h |
| RTX 5090 | 32 GB | 64 ₽/h |
| L40S | 48 GB | 108 ₽/h |
| A100 80 GB | 80 GB | 181 ₽/h |
| H100 SXM | 80 GB | 337 ₽/h |
| H200 | 141 GB | 660 ₽/h |
| B200 | 180 GB | 1 099 ₽/h |

Prices follow the market: see the [GPU catalog](https://gpu.nz/en/gpu?utm_source=github&utm_medium=readme&utm_campaign=arenda-gpu) for live ones. **Interruptible servers** cost up to 50% less, for long jobs that survive a pause.

<br clear="right">

## Rent a GPU in 2 minutes

1. **Sign up** at [gpu.nz](https://gpu.nz/en?utm_source=github&utm_medium=readme&utm_campaign=arenda-gpu) with e-mail, Google or Telegram.
2. **Top up** your balance with crypto.
3. **Pick a GPU and a template** in the catalog and press «Rent». The server is up in a few minutes; app links and SSH appear on its page.

<img src="images/console-search.png" alt="Searching for a GPU server in the gpu.nz console" width="100%">

## One-click AI templates

| Template | What it does |
|---|---|
| **Uncensored Image Chat** | A chat for image generation: description → picture, edit your own photo in words. Z-Image and FLUX.2 |
| **ComfyUI** | Node-based image and video generation: FLUX, SDXL, Wan, HunyuanVideo |
| **Stable Diffusion WebUI Forge** | The familiar AUTOMATIC1111 interface with ControlNet and LoRA |
| **InvokeAI, SwarmUI** | Studios for artists: canvas, layers, inpainting |
| **LLM chats** | Qwen 3.8, GPT-OSS 120B, Gemma 4, Hermes and uncensored builds, the model preloaded |
| **Ollama + Open WebUI** | Your own ChatGPT with any model from Ollama or Hugging Face |
| **vLLM** | Fast inference with an OpenAI-compatible API |
| **Wan2GP** | Video generation with Wan 2.2, Hunyuan, LTX |
| **ACE-Step, Whisper** | Songs with vocals, and speech to text in 99 languages |
| **Kohya, AI Toolkit, FluxGym, Unsloth** | LoRA training and LLM fine-tuning |
| **PyTorch + Jupyter, Ubuntu, your Docker image** | A clean environment for your own work |

<img src="images/templates.png" alt="AI templates on gpu.nz" width="100%">

## Uncensored image generation in a chat

The new Uncensored Image Chat template is a chat where the model draws from a description or reworks a photo you upload. The models run on the GPU you rent, so there are no content filters and nobody sees your pictures. Inside are **Z-Image Turbo** (text to image) and **FLUX.2 klein 4B** (photo edits and combinations), both Apache 2.0. On an RTX A4000 a 1024×1024 picture takes ~30 seconds and an edit ~11 seconds.

<img src="images/image-chat-edit.jpg" alt="Editing a picture with AI: original, red spacesuit, anime style" width="100%">

<img src="images/image-chat.png" alt="An image generation chat on your own GPU server" width="100%">

More: [uncensored AI image generator on your own GPU](https://gpu.nz/en/templates/image-chat?utm_source=github&utm_medium=readme&utm_campaign=arenda-gpu).

## The catalog: RTX 4090, H100, A100 and a hundred more

Every GPU has a page with prices, specs and the work it suits: [RTX 4090](https://gpu.nz/en/gpu/rtx-4090-24gb?utm_source=github&utm_medium=readme&utm_campaign=arenda-gpu), [RTX 5090](https://gpu.nz/en/gpu/rtx-5090-32gb?utm_source=github&utm_medium=readme&utm_campaign=arenda-gpu), [RTX 3090](https://gpu.nz/en/gpu/rtx-3090-24gb?utm_source=github&utm_medium=readme&utm_campaign=arenda-gpu), [A100](https://gpu.nz/en/gpu/a100-sxm4-80gb?utm_source=github&utm_medium=readme&utm_campaign=arenda-gpu), [H100](https://gpu.nz/en/gpu/h100-sxm-80gb?utm_source=github&utm_medium=readme&utm_campaign=arenda-gpu), [H200](https://gpu.nz/en/gpu/h200-141gb?utm_source=github&utm_medium=readme&utm_campaign=arenda-gpu), [L40S](https://gpu.nz/en/gpu/l40s-48gb?utm_source=github&utm_medium=readme&utm_campaign=arenda-gpu).

<img src="images/catalog.png" alt="Rental GPU catalog with hourly prices" width="100%">

## API and CLI

The catalog is open without a key; everything else takes an API key from your account ([docs](https://gpu.nz/en/docs?utm_source=github&utm_medium=readme&utm_campaign=arenda-gpu)).

```bash
# every GPU model with its lowest price
curl https://gpu.nz/api/v1/gpus

# CLI for Linux, macOS and WSL
curl -fsSL https://gpu.nz/install.sh | sh
gpunz login
gpunz search --gpu rtx-4090 --max-price 40 --verified
gpunz create <OFFER_ID> --template comfyui --disk 80
```

## FAQ

**How much does GPU rental cost?**
From 10 ₽ an hour for an RTX 3060 and from 25 ₽ for an RTX 4090; an H100 from 337 ₽ an hour. Billing is per minute and the price is locked at launch. Traffic is billed separately, and its price is shown before you launch.

**Is there a minimum rental term?**
No. Run a server for ten minutes and delete it: you pay for those minutes only.

**What is an interruptible server?**
The same server for up to 50% less, which may be paused when the hardware owner gets a full-price order. Good for jobs with checkpoints.

**Can I run my own Docker image?**
Yes: the «Your Docker image» template runs any image from Docker Hub or your own registry, with SSH and the ports you need.

## Links

- Website: [gpu.nz](https://gpu.nz/en?utm_source=github&utm_medium=readme&utm_campaign=arenda-gpu)
- GPU catalog: [gpu.nz/en/gpu](https://gpu.nz/en/gpu?utm_source=github&utm_medium=readme&utm_campaign=arenda-gpu)
- Templates: [gpu.nz/en/templates](https://gpu.nz/en/templates?utm_source=github&utm_medium=readme&utm_campaign=arenda-gpu)
- Guides: [gpu.nz/en/guides](https://gpu.nz/en/guides?utm_source=github&utm_medium=readme&utm_campaign=arenda-gpu)
- Telegram bot: [@gpunzbot](https://t.me/gpunzbot) · channel: [@gpunz](https://t.me/gpunz)

---

<sub>GPU rental, rent a GPU, cloud GPU, GPU server rental, rent RTX 4090, rent H100, rent A100, GPU for AI, hourly GPU rental, pay for GPU with crypto.</sub>
