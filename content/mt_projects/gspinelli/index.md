---
title: An evaluation of finetuning paradigm in the context of Imitation Learning for robotic tasks


links:
  - type: video
    url: https://drive.google.com/file/d/10bhrMTKqcOpk3IoUY23wMqJ554oOAu4I/view?usp=drive_link
tags:
  - Video-Conditioned Imitation Learning
  - Multi-Task
  - Data-Driven Control Policy
  - ROS

featured: true

date: '2025-04-29'
---

This thesis investigates the use of fine-tuning in data-driven robotic control, focusing on video-conditioned imitation learning. While fine-tuning is widely successful in computer vision and natural language processing, its application to robotics is challenging due to differences in robot designs, environments, and control spaces.

The proposed system, V-RT1, is a video-conditioned multi-task imitation learning model designed to enable intuitive robot programming through visual demonstrations rather than natural language. The model is trained and tested on various pick-and-place tasks in both simulation and real-world settings.

Experiments explore how dataset size and diversity affect performance. Results show that fine-tuning significantly improves performance (up to +25%) compared to training from scratch, particularly when pre-trained on large, diverse datasets spanning different robots and environments. However, co-training approaches showed mixed results, as the model tended to overfit to more frequent task trajectories.

Finally, the study finds that while command inputs influence robot behavior, they do not do so optimally, suggesting the need for an auxiliary loss to better integrate task-related information from the video input.
<!--more-->