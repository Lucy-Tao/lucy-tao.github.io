---
permalink: /
title: "Yuan Tao"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hello! I’m Yuan Tao. I recently completed an MSc in Advanced Computer Science (Artificial Intelligence) at the University of Oxford. Before that, I studied Information and Computing Science at South China University of Technology.

During my master’s research at [OATML](https://oatml.cs.ox.ac.uk/) at the University of Oxford, I worked with Prof. [Yarin Gal](https://www.cs.ox.ac.uk/people/yarin.gal/) and Dr. [Lin Li](https://treelli.github.io/) on uncertainty and hallucinations in LLM distillation. As an undergraduate, I worked with Prof. [Rui Liu](https://www2.scut.edu.cn/math/2017/1227/c14582a242135/page.psp) on detecting critical transitions in complex biological systems.

My research interests lie in uncertainty quantification and reliable machine learning, particularly for large language models. I am interested in how uncertainty is represented, lost, and recovered as models learn from data and from other models, and how this affects their ability to recognize unreliable answers. I am currently applying to PhD programs in artificial intelligence and machine learning.

## Research

**Uncertainty and hallucinations in LLM distillation.** For my master’s dissertation at Oxford’s OATML group, I studied sequence-level knowledge distillation under the supervision of Prof. Yarin Gal, Dr. Lin Li, Dr. Yi Ren, and Dr. Jialin Yu. We found that training a student on single responses from a teacher can erase information about the teacher’s uncertainty, leaving the student confident even when reproducing hallucinated answers. Across four teacher–student model pairs, continued distillation reduced hallucination-detection performance from an AUROC of approximately 0.8 toward chance level. We also evaluated strategies for preserving uncertainty, including uncertainty filtering, abstention replacement, and distillation from multiple responses.

**Bayesian uncertainty in active learning.** In an Oxford course project, I reproduced and extended deep Bayesian active learning experiments. I compared uncertainty-based acquisition methods and studied how different approaches to posterior inference behave under label noise and limited data.

**Graph learning and computational biology.** I have also investigated aggregation methods in graph neural networks. Earlier, I led an undergraduate research project on detecting critical transitions in biological systems from high-dimensional, small-sample data. This work led to a first-author paper in *Philosophical Transactions of the Royal Society A*.

## Selected Publications

- **Yuan Tao**, Yi Ren, Jialin Yu, Yarin Gal, and Lin Li. “Distilling Answers, Discarding Uncertainty: Uncertainty Collapse in Sequence-Level Knowledge Distillation.” **Under review at ICLR 2027**. [OpenReview](https://openreview.net/forum?id=KQYh1Ku6GP)
- **Yuan Tao**, Yi Ren, Jialin Yu, Yarin Gal, and Lin Li. “Sequence-Level Knowledge Distillation Collapses Uncertainty and Erodes Hallucination Detection.” **Accepted at the NeurIPS 2026 Workshop on Transitioning from Pre-Training to Post-Training**.
- **Yuan Tao**, Ruoqi Lan, Yunshan Lai, Jiayuan Zhong, and Rui Liu. “sMIE: Revealing Critical Transitions in Complex Biological Systems Using Single-Sample Mutual Information Entropy.” *Philosophical Transactions of the Royal Society A*, 2026. [Paper](https://doi.org/10.1098/rsta.2024.0484)

## Education

- **University of Oxford** — MSc in Advanced Computer Science (Artificial Intelligence), Distinction, 2026.
- **South China University of Technology** — BSc in Information and Computing Science, 2025. GPA: 3.93/4.00; ranked 1st of 60.
