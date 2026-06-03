---
author: Mahsa Ardakani, Arshia Eslami, Ramtin Zand
title: "VLMath: A Multimodal Vision-Language System for Pedagogically Aligned Math Tutoring"
affiliation: Affiliation
spotlight: no
number: 1
---
**Abstract**: Recent advances in vision language models (VLM) enable multimodal reasoning over text and images, yet strong mathematical performance does not inherently translate into effective tutoring behavior. We present VLMath, a multimodal vision language system designed for pedagogically aligned math tutoring. Built on Phi-3.5-Vision-Instruct, VLMath is trained using a synthetic teacher-student dataset constructed from MathVision problems and Gemini-generated Socratic dialogues. We introduce a pedagogically masked fine-tuning objective that conditions on student turns and visual context while optimizing only teacher responses, encouraging scaffolded and reflective reasoning. Evaluated on MathTutorBench, VLMath achieves state-of-the-art pedagogical performance, reaching 0.94 in scaffolding and 0.99 in pedagogy instruction-following, surpassing substantially larger models including GPT-4o and LearnLM 1.5 Pro. We further demonstrate that a 4-bit quantized variant preserves instructional quality, response stability, and reasoning behavior. Our results show that explicit pedagogical alignment, rather than model scale alone, is key to effective multimodal tutoring and enables efficient deployment on resource-constrained devices.

[Poster](posters/CVPR26_VLMath_Poster-final_MA.pdf)
