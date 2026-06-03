---
author: Yanzhe Chen, Kevin Qinghong Lin, Mike Zheng Shou
title: "Code2Video: A Code-centric Paradigm for Educational Video Creation"
affiliation: Affiliation
spotlight: no
number: 1
---
**Abstract**: Recent video generation systems operate primarily in pixel space, but educational videos require more than visual plausibility: they demand precise temporal sequencing, legible spatial layouts, and faithful delivery of domain knowledge. We argue that this setting is better served by a renderable environment explicitly controlled by code. We present Code2Video, a code-centric agent framework that generates educational videos by writing executable Manim programs. The framework contains three agents: a Planner that converts a learning topic into a storyboard, a Coder that synthesizes runnable code with scope-guided repair, and a Critic that improves layout using visual anchor prompting. To evaluate educational usefulness rather than appearance alone, we build MMMC, a benchmark of professionally produced educational videos across 13 disciplines, and introduce TeachQuiz, an end-to-end metric that measures how much knowledge a video teaches to an unlearned VLM. Experiments show that Code2Video outperforms direct code generation and pixel-based video generation, improving TeachQuiz by up to 46 points and producing videos much closer to human-crafted tutorials.
