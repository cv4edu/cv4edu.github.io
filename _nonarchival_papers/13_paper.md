---
author: Yanhang Li, Zhichao Fan, Zexin Zhuang
title: "Do We Need Faces? Privacy-Preserving Engagement Detection via Face-Free Features in Classroom Video"
affiliation: Affiliation
spotlight: no
number: 9
---
**Abstract**: Classroom engagement systems rely on facial features, yet data involving minors demands strong privacy protections. Prior work studies de-identification for action recognition, but its impact on classroom tasks—gaze, expression, head pose—remains unquantified, and whether faces are necessary for engagement detection is unexplored in controlled settings. We address both questions. First, we benchmark eight de-identification configurations across three tasks, showing that methods achieving meaningful privacy (>90% re-identification prevention) can eliminate gaze detection entirely and reduce expression recognition to near chance. Second, on the DAiSEE dataset (7,919 clips), we compare face-based and face-free features for engagement prediction. Body-based CLIP features match face-based features on the 4-class task (57.3±0.9% vs. 57.8±1.0% accuracy; difference within one standard deviation across folds), while remaining robust to face occlusion that drops face detection to 37%. These findings provide initial evidence for a privacy-by-design approach: analyzing body features instead of collecting and de-identifying faces.
