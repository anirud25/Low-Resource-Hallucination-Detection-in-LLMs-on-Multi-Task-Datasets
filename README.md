# Low-Resource Hallucination Detection in LLMs on Multi-Task Datasets via Iterative Pseudo-Labeling Using Confidence Thresholding and Active Learning

This repository contains the code and supporting materials for the research work  
**“Low-Resource Hallucination Detection in LLMs on Multi-Task Datasets via Iterative Pseudo-Labeling Using Confidence Thresholding and Active Learning.”**

The work is currently under review.  
Detailed implementation, datasets, and full experimental configurations will be released publicly after acceptance.

---

## Overview

Large Language Models often generate outputs that are fluent but factually incorrect, a phenomenon commonly referred to as hallucination.  
This research work studies hallucination detection under low-resource conditions, where labeled data is scarce and the task spans multiple natural language generation settings.

The proposed framework focuses on:
- Learning with minimal labeled data
- Iterative self-training using pseudo-labels
- Confidence-based sample selection
- Active learning and ensemble-based strategies
- Evaluation across multiple NLP tasks

The goal is to develop methods that are scalable, task-agnostic, and practical under realistic resource constraints.

---

## Research Context

This work builds on recent efforts in hallucination detection and evaluation for large language models, with a specific emphasis on:
- Multi-task hallucination signals
- Low-resource learning settings
- Robust evaluation beyond simple accuracy metrics

Experiments are conducted on publicly available benchmark data, and the methodology is designed to generalize across domains.

---

## Methodology (High-Level)

The framework explored in this work includes:
- A transformer-based hallucination classifier
- Iterative self-training starting from a small labeled seed set
- Confidence thresholding to control pseudo-label quality
- Active learning using Query-by-Committee strategies
- Ensemble-based confidence estimation
- Lightweight LLM baselines using parameter-efficient fine-tuning

Further methodological details will be added after acceptance.

---

## Evaluation

Model performance is evaluated using:
- Accuracy for binary hallucination detection
- Spearman rank correlation to assess alignment with hallucination severity

This combination provides a more informative assessment of hallucination risk than binary correctness alone.

---

## Repository Status

This repository is currently in a **pre-release state**.

Planned updates after acceptance:
- Full source code
- Experiment scripts and configurations
- Reproducibility instructions
- Trained model checkpoints (where applicable)
- Detailed documentation

---

## Usage

Code and usage instructions will be provided after the paper is accepted for publication.

---

## Data

This project uses benchmark datasets released for shared evaluation tasks.  SHROOM dataset, released as part of SemEval-2024 Task 6 is used in this work. Link to the [SemEval-2024](https://helsinki-nlp.github.io/shroom/2024) Github 


Links, preprocessing scripts, and usage notes will be added post-acceptance in accordance with dataset licenses.

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
