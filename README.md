<div align="center">
  <img src="https://ansteinhuynh.com/logo/final.svg" width="72" alt="AH monogram" />
</div>

# Anstein Huynh

AI engineer & full-stack developer in Houston, TX. I build end-to-end: model adapters and quantization, ComfyUI pipelines, and the self-hosted infrastructure they run on (Linux · nginx · PM2 · Tailscale, GPU inference on my own RTX 4090). I also run **QuantumLeek**, an AI content platform built on that stack.

📍 Open to AI engineering / full-stack roles — [résumé](https://ansteinhuynh.com/resume/Anstein-Huynh-Resume.pdf) · [ansteinhuynh.com](https://ansteinhuynh.com)

## Things I've built

**[rotasim](https://github.com/AnsteinHuynh/rotasim)** — perceptual similarity trained as *orthogonal rotation adapters*: tiny (0.4–2.3M param) adapters on frozen vision towers that preserve the base model's geometry instead of burning it. The adapters alone add **+8.8 pp** on NIGHTS over the exact same towers without them. Apache-2.0.

**[ComfyUI-pyiqa-toolbox](https://github.com/AnsteinHuynh/ComfyUI-pyiqa-toolbox)** — a ComfyUI node pack wrapping the entire pyiqa library — **53 IQA architectures / 103 variants** through a single loader — plus an int8 ConvRot quantization of Q-ReAlign: **17.5 → 11.6 GiB VRAM, mean |Δ| 0.0008 vs bf16**. Published on the [ComfyUI Registry](https://registry.comfy.org/ansteinhuynh/pyiqa-toolbox); weights on [Hugging Face](https://huggingface.co/ansteinhuynh).

**Agent infrastructure** — a personal multi-harness AI agent setup (OpenClaw, Z-code, DeepSeek Harness): LLM orchestration across providers, persistent memory, Matrix/web channels.

## Stack

Python · TypeScript / React / Next.js · C# / C++ · PyTorch · ComfyUI · Linux / nginx / PM2 / Tailscale · Unity / Blender / Fusion 360 / CNC

---

`anstein@ansteinhuynh.com` · [site](https://ansteinhuynh.com) · [Hugging Face](https://huggingface.co/ansteinhuynh)
