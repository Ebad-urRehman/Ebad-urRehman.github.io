---
title: "QurSci-Onto: A Hierarchical Ontology and Dataset for Scientific Exegesis"
publishDate: 2026-03-01 00:00:00
img: /assets/qursci-onto.png
img_alt: A digital visualization of a complex network graph illustrating linguistic routing and semantic connections.
description: |
  A published resource for the computational study of scientific exegesis (Tafsir Ilmi), introducing a structured, three-layer ontology and curated dataset to enable multi-hop reasoning.
tags:
  - NLP Research
  - Ontology Routing
  - Arabic Semantic NLP
  - Published Paper
---

**Authors:** Ibad-ur-Rehman Rashid, Junaid Hussain, and Sadam Al-Azani  
**Venue:** Proceedings of the 2nd Workshop on NLP for Languages Using Arabic Script (AbjadNLP 2026), Rabat, Morocco.  
**Publisher:** Association for Computational Linguistics (ACL)  
**Links:** [Read the full paper on ACL Anthology](https://aclanthology.org/2026.abjadnlp-1.22/) | [PDF Download](https://aclanthology.org/2026.abjadnlp-1.22.pdf)

### Abstract

This paper introduces resources for the computational study of scientific exegesis (Tafsir Ilmi): a structured ontology, a curated dataset of 194 scientifically relevant Quranic verses linked to 260 exegetical records from two authoritative Tafsir books, and an annotation framework that organizes scientific references by topic and sequential context. 

Existing Quranic resources treat verses as unstructured text, losing the logical order and causal relationships of scientific concepts documented in exegesis. To address this, we present QurSci-Onto, a three-layer ontology that categorizes verses by scientific domain, links them to authoritative Tafsir, and provides a framework for representing sequential processes through stage-based annotations. 

### Methodology & Dataset

Our dataset includes page-level citations and covers 8 major scientific topics across 73 nodes. While the full corpus is tagged with broad categories and scientific topics, a specialized subset features granular node-level mappings to capture complex scientific narratives. 

### Key Findings

We release QurSci-Onto as a foundational resource for Arabic semantic NLP. Our evaluations demonstrate that this structured approach enables significant improvements in semantic retrieval and enables multi-hop sequential reasoning capabilities over standard unstructured baselines.