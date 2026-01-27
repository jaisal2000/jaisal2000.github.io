---
layout: page
title: "SemDiff-QA: Semantic Differentiation for Multi-Choice QA"
description: Discriminative ranking approach for commonsense question answering
img: assets/img/1.jpg
importance: 4
category: work
related_publications: false
---

## Overview

Implementation of the DCQA research paper (ECAI 2024), re-architecting a T5-Base model into a discriminative ranker for multiple-choice question answering.

### Key Achievements

- **60.52% Accuracy**: Achieved strong performance on CommonsenseQA dataset
- **Architectural Innovation**: Shifted from text generation to list-wise classification to resolve semantic drift
- **Memory Efficiency**: Engineered training pipeline using Mixed Precision (FP16) and gradient accumulation for T4 GPUs

### Technologies Used

- T5-Base
- PyTorch
- Mixed Precision Training
- GPU Optimization

### Development Timeline

- **Date**: November 2025

### Links

- [GitHub Repository](https://github.com/jaisal2000/SemDiff-QA-Semantic-Differentiation-for-Multiple-Choice-QA.git)

### Impact

Successfully optimized deep learning training on limited computational resources, demonstrating practical approaches to deploying large language models efficiently.
