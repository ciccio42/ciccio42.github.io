---
title: 'VF-GPU: Exploiting Parallel GPU Architectures to Solve Subgraph Isomorphism'

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
  - 'First Author'
  - 'Supervisor'
  - 'Second Author'
  - 'Supervisor'
  

date: '2025-06-08'

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *International Workshop on Graph-Based Representations in Pattern Recognition*
publication_short: In *GbRPR-25*

abstract: Subgraph isomorphism is a challenging problem involving the search for structural patterns in graphs. It has numerous applications across various fields, and many specialized algorithms have been proposed. However, existing sequential algorithms struggle with extremely large and sparse graphs, particularly when the pattern size is very small with respect to the target graph. Recently, GPU-based approaches have been introduced to address this issue; but, while they are highly effective at exploiting GPU parallelism, these methods are also memory-intensive. In this paper, we present VF-GPU, a novel hybrid algorithm that leverages both CPU and GPU architectures to efficiently solve the subgraph isomorphism problem. Our approach is based on a state space representation (SSR) and employs a limited breadth-first search (BFS) strategy to constrain state generation during exploration. This enables efficient parallelism while controlling memory usage. We evaluated VF-GPU against VF3, VF3-L, and the GPU-based GSI algorithm. The experiments, conducted on a large sparse graph with over 300,000 nodes, demonstrate the effectiveness of our method across different query sizes and label distributions.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Graph-Matching
  - Subgraph Isomorphism
  - Parallel Algorithms
  - GPU

# Display this page in the Featured widget?
featured: false

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 10.1007/978-3-031-94139-9_11

---