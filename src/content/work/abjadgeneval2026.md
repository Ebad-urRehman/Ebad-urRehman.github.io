---
title: "AyahVerse at AbjadGenEval: Monolingual Precision and Cross-Lingual Analysis in Perso-Arabic AI Detection"
publishDate: 2026-03-28 00:00:00
img: /assets/stock-1.jpg
img_alt: A visual representation of cross-lingual AI detection algorithms processing Arabic and Urdu scripts.
description: |
  A robust composite framework for detecting AI-generated text in morphologically rich and low-resource environments, specifically targeting Arabic and Urdu using monolingual and multilingual transformers.
tags:
  - AI Detection
  - Perso-Arabic NLP
  - Transformers
  - Published Paper
---

**Authors:** Fizza Nawaz, Ibad-ur-Rehman Rashid, Uswa Abid, and Junaid Hussain  
**Venue:** Proceedings of the 2nd Workshop on NLP for Languages Using Arabic Script (AbjadNLP 2026), Rabat, Morocco.  
**Publisher:** Association for Computational Linguistics (ACL)  
**Links:** [Read the full paper on ACL Anthology](https://aclanthology.org/2026.abjadnlp-1.63/) | [PDF Download](https://aclanthology.org/2026.abjadnlp-1.63.pdf)

### Abstract

This paper presents our submission to the AbjadGenEval shared task on AI-generated text detection in Arabic and Urdu. To address the challenges of morphologically rich and low-resource environments, we developed a composite framework leveraging monolingual specialists (AraBERTv2, CAMeLBERT-DA) and multilingual transformers. 

Our system achieved robust in-domain performance with Test F1-scores of 0.75 for Arabic and 0.86 for Urdu. Methodologically, we tested both raw and normalized text to distinguish whether models detect based on semantic content or on surface artifacts such as punctuation and formatting patterns. 

### Cross-Lingual Analysis

Beyond monolingual precision, our research explores the zero-shot cross-lingual capabilities of these models. Our investigations reveal distinct directional performance differences: Urdu-trained models achieved a 0.75 F1 score on Arabic, while Arabic-trained models achieved a 0.61 F1 score on Urdu. 

Despite these differences, both directions maintained a notably high recall for the machine class. This indicates that the models successfully learn cross-lingual machine detection patterns across the shared Perso-Arabic script, rather than just memorizing language-specific vocabulary.

### Impact

This framework provides a critical step forward in identifying LLM-generated content in under-resourced languages, ensuring the integrity of digital text in Perso-Arabic communities.