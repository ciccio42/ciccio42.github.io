---
title: 'Graph neural networks for IoT security: A comparative study'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Nicola Capuano
  - Vincenzo Carletti
  - Pasquale Foggia
  - admin
  - Mario Vento

# Author notes (optional)
author_notes:
  - 'First Author'
  - 'Supervisor'
  - 'Second Author'
  - 'Supervisor'
 
  

date: '2026-01-01'

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: In *Internet of Things*
publication_short: In *IoT*

abstract: The increasing deployment of IoT devices has introduced new cybersecurity vulnerabilities, as traditional defense mechanisms often fail to protect resource-constrained and highly heterogeneous environments. Network traffic analysis has emerged as a key strategy for detecting malicious activities; however, the inherent dynamism of IoT communications undermines the effectiveness of traditional security mechanisms. In this paper, we focus on detecting malicious activities in IoT networks by solving a node-classification problem in a graph-based network representation. We evaluate six Graph Neural Network methods, encompassing both static and time-dependent models, using two distinct graph representations of network traffic. Our analysis is conducted across three recent IoT traffic datasets, and considers multiple snapshot durations to understand how temporal granularity affects detection accuracy. Through extensive experiments, we assess the impact of graph structure, snapshot duration, and temporal modeling on detection performance. Results show that GNNs, especially static models, are effective at identifying anomalous nodes even in unseen environments. We find that shorter snapshot durations consistently improve model accuracy by reducing noise in node embeddings, and that simpler traffic representation often match or outperform more complex counterparts, particularly when computational efficiency is a concern. Additionally, further research is needed to draw firm conclusions about dynamic methods. Our findings provide actionable insights for selecting models, representations, and configurations in the design of GNN-based intrusion detection systems for IoT networks.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Network Anomaly Detection
  - IoT Networks
  - Graph Neural Networks

# Display this page in the Featured widget?
featured: false
type: journal

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: https://doi.org/10.1016/j.iot.2025.101863

---