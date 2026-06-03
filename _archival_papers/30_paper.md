---
author: Suraj Prasad, Pinak Mahapatra
title: "Speech-Synchronized Whiteboard Generation via VLM-Driven Structured Drawing Representations"
affiliation: Affiliation
spotlight: no
number: 18
---
**Abstract**: Creating whiteboard-style educational videos demands precise coordination between freehand illustrations and spoken narration, yet no existing method addresses this multimodal synchronization problem with structured, reproducible drawing representations. We present the first dataset of 24 paired Excalidraw demonstrations with narrated audio, where every drawing element carries millisecond-precision creation timestamps spanning eight STEM domains. Using this data, we study whether a vision-language model (Qwen2-VL-7B), fine-tuned via LoRA, can predict full stroke sequences synchronized to speech from only 24 demonstrations. Our topic-stratified five-fold evaluation reveals that timestamp conditioning significantly improves temporal alignment over ablated baselines, while the model generalizes across unseen STEM topics. We discuss transferability to real classroom settings and release our dataset and code to support future research in automated educational content generation.
