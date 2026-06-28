---
title: 'Video-Conditioned Multi-Task Imitation Learning for Robotic Systems: Enhancing Robustness Through Object Centric Reasoning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin

date: '2025-02-14'

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['thesis']

# Publication name and optional abbreviated publication name.
publication: 'Ph.D. Thesis, Università degli Studi di Salerno — Dottorato di Ricerca in Ingegneria dell''Informazione, Ciclo 37. Supervisor: Prof. Mario Vento'
publication_short: 'Ph.D. Thesis, Università degli Studi di Salerno'

abstract: Robot technology is one of the pillars of modern society. Advances in information, electronic, and mechanical fields enable us to build and program machines to perform tasks in very different contexts, such as industry, surgery, and space missions. While in the early day, robot systems were constrained in isolated and known environments. Over the past few decades, robots have been asked to solve tasks in dynamic and unknown/partially known environments, where they must coexist and cooperate with humans, while solving different dynamic tasks. In this scenario, the desired characteristics of such robotic systems are adaptability to new conditions and adaptability to new tasks. Given this background, the thesis is framed in the context of Learning from Demonstration (LfD), focusing on a specific aspect named Multi-Task LfD, where the control policy is conditioned on a video demonstration that informs the policy about the task to execute, the object to manipulate, and the target placing location. The primary contribution of this thesis is tackling the challenge of distractor objects, addressing the issue of target misidentification observed in end-to-end architectures trained with an action-centric cloning loss. To this end, the thesis proposes a modular architecture composed of a Conditioned Object Detector (COD), which predicts the category-agnostic bounding box of the target object and the final placing location from the video demonstration and the current observation, and an Object Conditioned Control Policy (OCCP), which maps this low-level positional information into actions. The proposed approach was extensively evaluated in simulation, on multi-variation single-task and multi-variation multi-task scenarios across four manipulation tasks (Pick-Place, Nut-Assembly, Stack-Block, and Button-Press), achieving average success rates of 90.13% and 79.24% respectively, improving over baseline methods by +28.78% and +33.23%. The approach was further validated on a real-world robotic platform, reaching a 55.00% success rate under noisy, limited teleoperated data, compared to 0.00% for the baseline, confirming that object-centric priors enable reliable learning from demonstration even in challenging real-world conditions.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Learning from Demonstration
  - Deep Learning in Robotics and Automation
  - Learning and Adaptive Systems
  - Object-Centric Reasoning
  - Imitation Learning

# Display this page in the Featured widget?
featured: false
type: journal

# Standard identifiers for auto-linking
# hugoblox:
#   ids:
#     doi:
# Custom links
links:
  - type: Legal Deposit (Tesi di Dottorato)
    url: "https://tesidottorato.depositolegale.it/handle/20.500.14242/366866"


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   filename: ""
#   caption: ''
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: ""
---