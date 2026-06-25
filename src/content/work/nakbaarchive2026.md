---
title: "AyahVerse at NakbaArchiveClassifier: Decision Calibration for Humanitarian Image Classification"
publishDate: 2026-04-15 00:00:00
img: /assets/stock-4.jpg
img_alt: A digital visualization overlaying machine learning detection metrics onto historical and humanitarian photography.
description: |
  An exploration of architectural trade-offs and advanced decision calibration techniques applied to humanitarian image classification for the NakbaArchiveClassifier Shared Task.
tags:
  - Computer Vision
  - Humanitarian AI
  - Decision Calibration
  - Published Paper
---

**Authors:** Ibad-ur-Rehman Rashid, Fizza Nawaz, Uswa Abid, and Junaid Hussain *(Update if co-authors differ)* **Venue:** NakbaArchiveClassifier Shared Task  
**Links:** [Read the full paper on ResearchGate](https://www.researchgate.net/publication/405220350_AyahVerse_at_NakbaArchiveClassifier_Shared_Task_Architectural_Trade-offs_and_Decision_Calibration_for_Humanitarian_Image_Classification) 

### Abstract

This paper details the AyahVerse team's submission to the NakbaArchiveClassifier Shared Task, focusing on the critical challenge of humanitarian image classification. Analyzing historical and humanitarian archives requires models that are not only highly accurate but mathematically calibrated to avoid overconfident misclassifications in sensitive contexts. 

In this work, we evaluate various architectural trade-offs, comparing lightweight classifiers against deeper, more complex vision models. We specifically address the challenges of class imbalance and visual ambiguity present in humanitarian archives.

### Methodology & Decision Calibration

Our approach goes beyond standard accuracy optimization by prioritizing **decision calibration**. We implemented post-processing calibration techniques to ensure that the confidence scores output by our visual architectures accurately reflect the true probability of correctness. 

The methodology explores:
1. **Architectural Trade-offs:** Balancing computational efficiency with feature-extraction depth in morphologically complex historical imagery.
2. **Confidence Calibration:** Adjusting the model's logits to provide reliable uncertainty estimates, which is vital for human-in-the-loop review systems in humanitarian efforts.

### Impact

By optimizing both the architecture and the decision thresholds, this framework provides a more reliable, ethically sound approach to deploying AI for the automated archival and classification of sensitive humanitarian imagery.