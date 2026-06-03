---
author: Siddharth Manne, Shaden Alshammari, Satish Somaraju
title: "Socratic: Pushing the Boundaries of Interactive Visual Educational Content Creation."
affiliation: Affiliation
spotlight: no
number: 10
---
**Abstract**: We present an agentic AI pipeline that generates interactive, narrated STEM educational content from a problem and its solution. Unlike prior systems that produce passive videos or static slides, our pipeline outputs self-contained HTML presentations where warm-up questions pause the timeline and test understanding, split-screen derivations build algebra alongside animated diagrams, and interactive sliders let students explore parameters after the explanation. A five-stage architecture (Planner, Self-Review, Coder, Judge, Targeted Fix) generates browser-native HTML guided by a∼700-line prompt-as-library, then self-critiques against a rubric until the score reaches 8/10. Each output is a single HTML file requiring no server or installation, deployable offline in rural classrooms and on mo bile devices. We support seven languages including RTL scripts and demonstrate on competition mathematics in English and Arabic. Live demos: https://socratic-demos.vercel.app (EN) and https://socratic-demos.vercel.app/arabic (AR).
