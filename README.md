# Low-Resource Hallucination Detection in LLMs on Multi-Task Datasets via Iterative Pseudo-Labeling Using Confidence Thresholding and Active Learning

This repository contains the code and supporting materials for the research work:

**“Low-Resource Hallucination Detection in LLMs on Multi-Task Datasets via Iterative Pseudo-Labeling Using Confidence Thresholding and Active Learning.”**

The work is published in *Discover Artificial Intelligence* by Springer Nature.

**Published article:** [Springer Nature](https://link.springer.com/article/10.1007/s44163-026-02106-1)

---

## Overview

Large Language Models often generate outputs that are fluent but factually incorrect, commonly referred to as hallucinations. This research studies hallucination detection in low-resource settings, where only limited labeled data is available across multiple natural language generation tasks.

The work first explores different machine learning, deep learning, and transformer-based architectures before developing and evaluating a proposed iterative framework based on DeBERTa-v3 Large. The framework focuses on:
- Learning from limited labeled data
- Iterative self-training through confidence-based pseudo-labeling
- Active Learning for selecting informative samples
- Ensemble learning and Query-by-Committee for improved sample selection
- Evaluation using accuracy and Spearman correlation

The overall aim is to reduce the need for extensive manual annotation while improving hallucination detection under limited-resource conditions.

---

## Research Context

Hallucination detection is an important part of improving the reliability of Large Language Models, particularly as these models are increasingly used across different natural language generation tasks. However, developing reliable detection models can require substantial labeled data and manual annotation.

This work focuses on this challenge by studying an iterative semi-supervised approach that progressively expands the labeled training data using pseudo-labeling and selected manual annotations. The framework is evaluated on the publicly available SHROOM benchmark, which covers multiple natural language generation tasks and provides a low-resource setting for hallucination detection.

The study also examines the contribution of individual components of the framework and uses additional analysis to assess performance variability and annotation consistency.


---

## Methodology

The framework explored in this work includes:
- A transformer-based hallucination classifier
- Iterative self-training starting from a small labeled seed set
- Confidence thresholding to control pseudo-label quality
- Active learning using Query-by-Committee strategies
- Ensemble-based confidence estimation
- Lightweight LLM baselines using parameter-efficient fine-tuning
- 

Further methodological details will be added after acceptance.

---

## Evaluation

Model performance is evaluated using:
- Accuracy for binary hallucination detection
- Spearman rank correlation to assess alignment with hallucination severity

This combination provides a more informative assessment of hallucination risk than binary correctness alone.

---

## Usage

Code and usage instructions will be provided after the paper is accepted for publication.

---

## Data

This project uses benchmark datasets released for shared evaluation tasks.  SHROOM dataset, released as part of SemEval-2024 Task 6 is used in this work. Link to the [SemEval-2024](https://helsinki-nlp.github.io/shroom/2024) Github 


---

## Citation

If you find this work useful, please cite the associated paper once it becomes publicly available.

Citation information will be updated here after acceptance.

---

## License

The license for this repository will be added upon public release.

---

## Contact

For questions or collaboration inquiries, please contact [Anirud R](anirud25@gmail.com) after the paper is published.

---
