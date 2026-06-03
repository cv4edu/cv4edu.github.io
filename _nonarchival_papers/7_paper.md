---
author: Pinak Mahapatra, Suraj Prasad
title: "From Knowing to Drawing: Teaching Vision-Language Models Spatial Programs for Educational Diagrams via Visual RL"
affiliation: Affiliation
spotlight: no
number: 3
---
**Abstract**: Vision-language models (VLMs) encode rich semantic knowledge about visual concepts; they can describe a kidney or a mitochondrion with medical precision, yet consistently fail to express that knowledge as accurate drawings. We call this the semantic–spatial gap: the asymmetry between declarative knowledge (“knowing that”) and procedural spatial knowledge (“knowing how to draw”).

We demonstrate this gap empirically through iterative drawing experiments using a live rendering loop, showing that VLMs can close it incrementally with visual feedback, but that this learning evaporates at session end. We propose SpatialRL, a two-stage reinforcement learning framework that permanently encodes spatial drawing programs into VLM weights using the render-and-feedback loop as an RL environment, without human demonstrations.

Stage 1 trains spatial vocabulary (what to draw); Stage 2 trains temporal alignment (when to draw it, synchronized with narration). We argue that this opens a new research axis for CV4Edu: automated visual explanation generation as a complement to the community’s focus on classroom perception.
