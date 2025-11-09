---
title: 'Context-aware data augmentation for enhanced speech command recognition in industrial environments'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Giuseppe de Simone
  - Antonio Greco
  - Francesco Rosa
  - Alessia Saggese
  - Mario Vento

# Author notes (optional)
author_notes:
  - 'First Author'
  - 'Corresponding Author'
  - 'First Author'
  - 'Supervisor'
  - 'Supervisor'

date: '2025-05-20'

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: In *Scientific Reports*
publication_short: ""

abstract: In Human-Robot Interaction, speech is one of the most intuitive and effective communication channel. In Industry 4.0, speech-based communication can significantly enhance productivity and efficiency on production lines. However, deploying a Speech Command Recognition Module in real-world industrial settings poses challenges, as the system must balance two conflicting objectives, accurately recognizing commands while rejecting noise and irrelevant speech. To address this, we propose a modular framework designed to optimize recognition accuracy and rejection robustness while minimizing the need for extensive industrial dataset collection. The framework features an efficient Command Recognition module trained on laboratory-collected data augmented with synthetic samples. Advanced context-aware data augmentation techniques and dynamic noise injection further enhance the model’s robustness. To improve reliability in noisy environments, a Keyword Spotting module is introduced, activating the recognition system only when a predefined keyword is detected. The proposed system was evaluated using real-world samples collected in a noisy industrial setting. The results demonstrated a high recall rate for both command recognition and noise rejection, confirming the system’s effectiveness in meeting the demands of industrial applications.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Human-Robot Collaboration
  - HRI
  - Speech-Command Recognition

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 10.1038/s41598-025-01886-3
# Custom links
links:
  - type: Project Website
    url: "https://www.felice-project.eu/"


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  filename: "image.png"
  caption: 'Speech Command Recognition Architecture'
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