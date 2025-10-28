---
title: "Towards Realistic Earth-Observation Constellation Scheduling: Benchmark and Methodology"
collection: publications
category: conferences
permalink: /publication/2025-12-01-eo-constellation-scheduling
excerpt: 'A unified framework integrating AEOS-Bench, the first large-scale benchmark suite for realistic constellation scheduling, and AEOS-Former, a Transformer-based scheduling model with constraint-aware attention mechanism.'
date: 2025-12-01
venue: 'Neural Information Processing Systems (NeurIPS) 2025'
slidesurl: # URL to slides if available
paperurl: 'https://neurips.cc/virtual/2025/poster/116515'
citation: 'Wang, L.*, Xiang, Y.*, Huang, H., Li, D., Gao, C., & Liu, S. (2025). &quot;Towards Realistic Earth-Observation Constellation Scheduling: Benchmark and Methodology.&quot; <i>Neural Information Processing Systems (NeurIPS) 2025</i>. (*Equal contribution)'
---

## Abstract

Agile Earth Observation Satellites (AEOSs) constellations offer unprecedented flexibility for monitoring the Earth's surface, but their scheduling remains challenging under large-scale scenarios, dynamic environments, and stringent constraints. Existing methods often simplify these complexities, limiting their real-world performance. We address this gap with a unified framework integrating a standardized benchmark suite and a novel scheduling model.

**AEOS-Bench**: Our benchmark suite contains 3,907 finely tuned satellite assets and 16,410 scenarios. Each scenario features 1 to 50 satellites and 50 to 300 imaging tasks. These scenarios are generated via a high-fidelity simulation platform, ensuring realistic satellite behavior such as orbital dynamics and resource constraints. Ground truth scheduling annotations are provided for each scenario. To our knowledge, AEOS-Bench is the first large-scale benchmark suite tailored for realistic constellation scheduling.

**AEOS-Former**: Building upon this benchmark, we introduce a Transformer-based scheduling model that incorporates a constraint-aware attention mechanism. A dedicated internal constraint module explicitly models the physical and operational limits of each satellite. Through simulation-based iterative learning, AEOS-Former adapts to diverse scenarios, offering a robust solution for AEOS constellation scheduling.

Experimental results demonstrate that AEOS-Former outperforms baseline models in task completion and energy efficiency, with ablation studies highlighting the contribution of each model component.

**Presentation**: Poster at NeurIPS 2025, Exhibit Hall C, D, E
**Time**: Wednesday, December 3, 2025, 4:30 PM - 7:30 PM PST

*This is a collaborative work with equal contribution between the first two authors.*
