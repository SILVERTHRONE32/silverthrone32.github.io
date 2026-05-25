---
layout: about
title: about
permalink: /
subtitle: UC Berkeley, Class of 2028 | B.S. EECS + B.S. Business Administration (M.E.T. Program)

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false
  more_info: >
    <p>University of California, Berkeley</p>
    <p>Electrical Engineering & Computer Sciences</p>
    <p>Management, Entrepreneurship, and Technology (M.E.T.)</p>

selected_papers: true
social: true

announcements:
  enabled: true
  scrollable: true
  limit: 5

latest_posts:
  enabled: true
  scrollable: true
  limit: 3
---

I'm a sophomore at UC Berkeley studying electrical engineering, computer science, and business through the Management, Entrepreneurship, and Technology (M.E.T.) program.

My work sits at the intersection of machine learning systems, efficient inference, and applied AI research, with a long-term interest in building AI that is private, local, and emotionally consistent.

My primary research project is **Atlas**, a hypernetwork architecture (**HyperLoRA**) that conditions LoRA adapter gains on a four-dimensional affect vector: valence, arousal, guardedness, and intimacy. At inference time over a frozen LLM backbone, the system produces parametrically distinct outputs across emotional states where plain LoRA shows no differentiation. This has been validated across Qwen3-4B, Phi-3.5-mini, and Llama-3.2-3B. An IPIRA invention disclosure was filed and disclaimed back to me, giving full independent IP ownership.

I also developed **DRiPP**, a protocol for inter-stage communication in VRAM-constrained heterogeneous LLM pipelines, where cross-family pipeline configurations outperformed same-model baselines by 28% F1.

On the systems side, I built **Atlas Vision V9**, a video understanding pipeline using PyNvVideoCodec zero-copy decode, GRU-SSM delta detection, and Qwen3.5-4B's 256k context window. The pipeline achieved 1168 FPS throughput on a 177-minute 60 FPS video at 9.08 GB VRAM flat, with 84.6% token savings on gaming content.

I published [**nvfp4-fix**](https://github.com/SILVERTHRONE32/nvfp4-fix), an open-source package resolving compressed-tensors bugs for NVFP4 model loading on Blackwell GPUs, and released **Atlas-72B-SVT**, a QLoRA fine-tune of Qwen2.5-72B, on Hugging Face under the **SILVERTHRONE** handle.

Earlier work includes a water-detecting guide stick for the visually impaired (Irish Design Patent IES87168, BT Young Scientist 2nd place at age 12), an agricultural emissions reduction system published at IEEE (2023), and a first-place finish at the RISHI UC Berkeley Water & Sanitation Designathon (April 2025) for a modular reclaimed-freezer rainwater harvesting system for rural India.

I plan to post selected preprints, systems write-ups, and implementation notes here as ongoing work matures.
