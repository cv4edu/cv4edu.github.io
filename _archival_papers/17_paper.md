---
author: Chongyu He, Peter Youngs, Scott Acton
title: "Delta-Gated Incremental Multi-Forward-Pass Modeling for Robust Multimodal Classroom Video Understanding"
affiliation: Affiliation
spotlight: no
number: 9
---
**Abstract**: Multimodal transformers are attractive options for the analysis of human activity in the classroom, but real-world classroom data often contain missing or misaligned modalities, making robust multimodal learning challenging. In this work, we propose a Delta-Gated Multi-Forward-Pass (DG-MFP) Longformer for robust multimodal classroom discourse understanding. The model treats the transcript as the primary modality and models audio and video as incremental sources of information. A shared encoder performs multiple forward passes with different modality masks (text, text+audio, text+video, text+audio+video), allowing modality contributions to be isolated through differences between representations. These increments are fused through class-specific delta gates that modulate modality contributions relative to the text baseline. To evaluate robustness under realistic classroom conditions, we introduce controlled missing-modality and cross-modal misalignment tests. Experiments on the Artificial Intelligence for Advancing Instruction at Scale (AIAIS) dataset show that the proposed method consistently improves overall F1 over standard multimodal fusion baselines and exhibits substantially stronger robustness under missing or misaligned modalities. Further analysis of the learned gates reveals interpretable, task-specific patterns of modality activity, highlighting how multimodal signals provide complementary information when transcript evidence alone is insufficient.

[Poster](posters/CV4Edu-17_DG-MFP_Poster.pdf)
