---
title: 'Detecting malicious IoT network communication through Graph Neural Networks in real-world conditions'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Vincenzo Carletti
  - Pasquale Foggia
  - Francesco Rosa
  - Mario Vento

# Author notes (optional)
author_notes:
  - 'Corresponding Author'
  - 'Supervisor'
  - 'Second Author'
  - 'Supervisor'

date: '2025-01-27'

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: In *Pattern Recognition Letters*
publication_short: ""

abstract: Internet of Things (IoT) devices are increasingly permeating homes, industries, and many other environments. The need for robust security measures in IoT networks has never been more critical, since they are becoming the preferred target for cyberattacks. In this paper, we address the challenge of detecting abnormal communication patterns in IoT networks using Graph Neural Networks (GNNs). To this end, we have conducted a comprehensive and fair comparison of machine learning approaches and GNNs, for both static and dynamic graphs, across three recent datasets, IoT23, IoTID20, IoT Traces, that contain recordings of network communications among IoT devices in real environments. Differently from the state-of-the-art, we face the problem as a node anomaly detection task under the realistic assumption of only having normal traffic samples for training the GNNs. Furthermore, we have also restricted the false positive rate below 1% to make the system practical for human operators willing to use it as an Anomaly-based IDS (A-IDS). Finally, the experimental results highlight the relevance of structural information to effectively address the task in real-world conditions.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Graph Neural Networks
  - IoT network security
  - Anomaly Detection

# Display this page in the Featured widget?
featured: false
type: journal

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 10.1016/j.patrec.2025.01.010


---