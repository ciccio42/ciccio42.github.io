---
title: 'Enhancing IoT Network Security with Graph Neural Networks for Node Anomaly Detection'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Vincenzo Carletti
  - Pasquale Foggia
  - admin
  - Mario Vento

# Author notes (optional)
author_notes:
  - 'Corresponding Author'
  - 'Supervisor'
  - 'First Author'
  - 'Supervisor'
 
  

date: '2025-01-31'

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Joint IAPR International Workshops on Statistical Techniques in Pattern Recognition (SPR) and Structural and Syntactic Pattern Recognition (SSPR)*
publication_short: In *SPR-SSPR-25*

abstract: The widespread deployment of Internet of Things (IoT) devices in homes, industries, and public spaces presents significant cybersecurity challenges, particularly due to their limited computational capabilities and often insecure configurations. Detecting infected devices through network analysis presents a significant challenge given the diversity of network protocols and behaviors. Traditional methods, reliant on packet statistics or binary signatures, show their limits in these complex environments. Recent advancements in machine learning and deep learning offer promising alternatives, also through the use of graph-based representations that capture network topology and facilitate the detection of complex attack patterns. This paper presents a comprehensive analysis in a realistic setup of two state-of-the-art Graph Neural Networks (GNNs) designed for node anomaly detection, applied to a large-scale dataset of IoT network traffic. The dataset, comprising over 240,000 graphs extracted from IoT23, IoTID20, and IoT-Traces, includes both benign and malicious communications. In the analysis we take into account the impact of varying snapshot durations and graph-based representations on the performance achieved by the GNNs. The results suggest that using a state-of-the-art graph autoencoder (DOMINANT) with a computationally efficient representation (TDG) is the best trade-off among the considered constraints and variables.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Network Anomaly Detection
  - IoT Networks
  - Graph Neural Networks

# Display this page in the Featured widget?
featured: false
type: conference

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 10.1007/978-3-031-80507-3_5

---