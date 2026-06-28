---
title: User-Centric Knowledge Graph Generation - Real-Time Multimodal Context Injection for Personalized Human-Robot Interactions


tags:
  - Human-Robot Interaction
  - Knowledge Graphs
  - Large Language Models
  - Social Robotics

featured: true

date: '2026-06-28'
---

This thesis tackles the challenge of personalizing conversations on a social robot in real time, without compromising the stability and fluidity of an existing conversational pipeline. While Large Language Models have greatly improved the fluency of human-robot dialogue, social robots still struggle to genuinely adapt their answers to the specific person they are talking to, especially under the strict latency constraints of a live interaction.

The student's first contribution is a user-centric Knowledge Graph, built incrementally during the interaction rather than offline: unlike the large, static graphs typically used in the literature, this graph stays small, dynamic and focused exclusively on the current interlocutor, so it can be updated and re-injected into the dialogue manager at every conversational turn. The graph is populated by two complementary pipelines running in parallel with the existing robotic architecture: a perceptual one, which converts biometric attributes already estimated by the robot (age, gender, emotion, ethnicity) into graph triples, and an LLM-based one, which analyzes each user utterance and extracts further semantic triples to enrich the profile. Both pipelines are decoupled from the main dialogue loop, so the graph grows without introducing any latency perceivable by the user.

The system was deployed on the embedded hardware of the Pepper robot and evaluated through a within-subjects A/B study with 40 participants, who interacted blindly with both the baseline and the Knowledge-Graph-augmented version of the system and then completed a questionnaire based on the Godspeed scales, extended with dedicated Memory and Personalization constructs. The results show large and statistically significant improvements on every construct measured, with the biggest gains observed on conversational memory and perceived personalization, confirming that injecting a dynamic, user-centric Knowledge Graph into the conversational pipeline substantially improves the perceived quality of the social interaction while preserving the real-time constraints of a natural dialogue.
<!--more-->
