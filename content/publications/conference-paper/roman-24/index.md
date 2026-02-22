---
title: 'Improving Learning from Visual Demonstration Methods by Target Localization'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Pasquale Foggia
  - Mario Vento

# Author notes (optional)
author_notes:
  - 'First Author'
  - 'Supervisor'
  - 'Supervisor'
  

date: '2024-10-30'

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *IEEE International Conference on Robot and Human Interactive Communication (ROMAN),*
publication_short: In *RO-MAN-24*

abstract: This paper presents a novel approach to multi-task visual-guided imitation learning. Upon evaluating the current state-of-the-art method, we observed its capability to replicate the intent of the demonstrator, but with the flaw of manipulating incorrect objects. To address this issue, our study introduces a new approach based on the assumption that explicitly addressing task-relevant problems, such as target object localization, can enhance system performance. Our validation shows that the proposal overtakes the leading method thanks to its ability to drive the robot motion towards the target object.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Imitation Learning
  - Conditioned Object Detector
  - Multi-Task

# Display this page in the Featured widget?
featured: true
type: conference

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 10.1109/RO-MAN60168.2024.10731447

# Custom links
links:
  - type: Project Website
    url: "https://sites.google.com/view/multi-task-mosaic-ctod"


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  filename: "featured.gif"
  caption: 'Example of robot behavior'
  focal_point: ''
  preview_only: false

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

<iframe 
  src="presentazione_roman.pdf"
  width="100%"
  height="600px"
  style="border: none;"
></iframe>