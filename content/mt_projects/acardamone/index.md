---
title: Evaluating Generalization of State-of-the-Art Multi-Task Language Conditioned Imitation Learning Systems


tags:
  - Vision-Language-Action Models
  - Generalization
  - Language-Conditioned Imitation Learning
  - Robotic Manipulation

featured: true

date: '2026-06-28'
---

This thesis investigates how well modern Vision-Language-Action (VLA) models generalize to scenarios that differ from those seen during training. While these systems achieve strong performance on benchmark tasks, it remains unclear whether they truly understand language instructions and scene composition or simply exploit statistical shortcuts learned during training.

To answer this question, the student built a controlled, reproducible zero-shot generalization benchmark on top of the LIBERO-Goal simulation suite, organized along two complementary axes: syntactic generalization, probing robustness to verb substitution, syntactic restructuring, and compositional spatial reference in the instruction text; and task-level generalization, probing the ability to transfer learned skills to new objects and to compose known sub-skills into novel tasks. Three representative VLA architectures were evaluated against this benchmark: OpenVLA-OFT, TinyVLA, and InternVLA-M1, chosen to span different backbone scales and pre-training paradigms.

Results show that all three models remain close to baseline performance under simple verb substitution and syntactic restructuring, but collapse sharply when instructions require compositional spatial reasoning, with success rates dropping as low as 13.6%. Failure-mode analysis, based on end-effector trajectory heatmaps and token-level ablations, reveals that the residual performance of two of the models is largely driven by superficial lexical anchors rather than genuine spatial grounding. Task-level generalization proved even more brittle: cross-object skill transfer failed completely for all models, and novel task composition succeeded only when accidentally favored by lexical co-occurrence in training data, rather than reflecting true compositional reasoning.

A targeted LoRA-based fine-tuning intervention on InternVLA-M1, using a small number of relabeled demonstrations, was able to recover compositional spatial reference performance from 39.0% to 88.7%, but at the cost of catastrophic forgetting on previously mastered generalization levels. The thesis concludes that current VLA systems generalize far less robustly than their in-distribution success rates suggest, and proposes experience-replay fine-tuning and Knowledge Graph-augmented architectures as promising directions for achieving more reliable relational and spatial reasoning in language-conditioned robot manipulation.
<!--more-->
