---
title: "AyahVerse at MAHED Shared Task: Fine-Tuning ArabicBERT for Hope and Hate Detection"
publishDate: 2025-11-01 00:00:00
img: /assets/stock-2.jpg
img_alt: A digital visualization of data streams representing text classification and sentiment analysis in Arabic script.
description: |
  A robust architecture evaluating single multiclass and stacked multi-layer ArabicBERT models for detecting hope and hate speech in Arabic social media content.
tags:
  - Text Classification
  - Arabic NLP
  - Transformers
  - Published Paper
---

**Authors:** Ibad-ur-Rehman Rashid and Muhammad Hashir Khalil  
**Venue:** Proceedings of The Third Arabic Natural Language Processing Conference: Shared Tasks, Suzhou, China (ArabicNLP 2025).  
**Publisher:** Association for Computational Linguistics (ACL)  
**Links:** [Read the full paper on ACL Anthology](https://aclanthology.org/2025.arabicnlp-sharedtasks.92/) | [PDF Download](https://aclanthology.org/2025.arabicnlp-sharedtasks.92.pdf)

### Abstract

This paper details our submission to Subtask 1 of the MAHED Shared Task 2025, which focuses on detecting "hope", "hate", and "not applicable" labels in Arabic social media content concerning the Middle East conflict. To tackle the linguistic diversity and dialect variations in the dataset, we developed and evaluated two distinct model architectures leveraging ArabicBERT.

### Methodology

Our approach tested the efficacy of specialized preprocessing pipelines alongside two primary architectures:
1. **Multiclass Classifier:** A fine-tuned ArabicBERT model directly performing multiclass classification.
2. **Stacked Meta-Classifier:** A two-step stacked architecture where two separate binary ArabicBERT models (one for hope, one for hate) feed their probability outputs into a final logistic regression meta-classifier.

We experimented extensively with class imbalance handling, including oversampling, undersampling, and adjusted class weights, as well as distinct preprocessing configurations like emoji removal.

### Key Findings

We found that proper Arabic preprocessing is the most significant driver of performance. While standard undersampling and oversampling led to overfitting, carefully adjusted weights resulted in stable performance gains. 

Though the difference between the single multiclass classifier and the stacked architecture was minimal during initial testing, optimizing the stacked classifier's preprocessing pipeline ultimately resulted in a notable improvement, reaching an F1 score of 0.91 on the official test set.