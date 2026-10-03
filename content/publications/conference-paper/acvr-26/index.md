---
title: 'EYE: Enhanced YOLO for Empty-shelf detection'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Luca Greco
  - admin
  - Alessia Saggese
  - Mario Vento

date: '2026-01-01'

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Fourteenth International Workshop on Assistive Computer Vision and Robotics (ACVR)*
publication_short: In *ACVR-26*

abstract: 'Autonomous mobile robots represent a promising solution for large-scale Out-of-Stock (OoS) detection in retail environments. However, images acquired by robotic platforms are often affected by motion blur and other degradations arising from robot movement, which significantly compromise the performance of downstream detection modules. In this paper, we investigate generative image restoration as a preprocessing stage for robotic OoS detection, proposing a two-stage framework, named EYE (Enhanced YOLO for Empty-shelf detection), that combines a GAN-based deblurring module with a YOLO26-Nano object detector. Unlike traditional image enhancement pipelines, EYE adopts an end-to-end training strategy in which the deblurring module is directly optimized through the downstream detection task. Consequently, image restoration is not guided by human visual quality criteria, but by the ability of the generated images to improve empty-shelf detection accuracy under realistic robotic operating conditions. To assess out-of-distribution generalization, the model is trained on static retail datasets and tested on the MIVIA-Video dataset, collected by a mobile robot navigating supermarket aisles. Experimental results demonstrate that motion-blur augmentation during training and generative restoration at inference time are complementary strategies: their combination yields consistent and substantial improvements over the baseline across all evaluation metrics, achieving gains of up to 20% in Recall and 23% in mAP@50-95.'

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Object Detection
  - Deblurring
  - Retail Robotics
  - YOLO

# Display this page in the Featured widget?
featured: false
type: conference

links:
  - type: OpenReview
    url: "https://openreview.net/forum?id=B9XrCx9fIG"

---
