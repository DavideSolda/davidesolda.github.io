---
title: "ECHO: a Hierarchical Combination of Classical and Multi-Agent Epistemic Planning Problems"
collection: publications
permalink: /publication/paper-ECHO
excerpt: 'ECHO: a Hierarchical Combination of Classical and Multi-Agent Epistemic Planning Problems'
date: 2023-07-21
venue: 'Journal of Logic and Computation (JLC)'
paperurl: 'https://academic.oup.com/logcom/advance-article/doi/10.1093/logcom/exad036/7227283?utm_source=advanceaccess&utm_campaign=logcom&utm_medium=email'
---
The continuous interest in Artificial Intelligence (AI) has brought, among other things, the development of several scenarios where multiple artificial entities interact with each other. As for all the other autonomous settings, these multi-agent systems require orchestration. This is, generally, achieved through techniques derived from the vast field of Automated Planning. Notably, arbitration in multi-agent domains is not only tasked with regulating how the agents act, but must also consider the interactions between the agents' information flows and must, therefore, reason on an epistemic level.

This brings a substantial overhead that often diminishes the reasoning process's usability in real-world situations.
To address this problem, we present ECHO, a hierarchical framework that embeds classical and multi-agent epistemic (epistemic, for brevity) planners in a single architecture. The idea is to combine classical; and epistemic solvers to model efficiently the agents' interactions with the ``physical world''; and information flows, respectively. In particular, the presented architecture starts by planning on the ``epistemic level'', with a high level of abstraction, focusing only on the information flows. Then it refines the planning process, thanks to the classical planner, to fully characterize the interactions with the ``physical'' world.

To further optimize the solving process, we introduced the concept of macros in epistemic planning and enriched the ``classical'' part of the domain with goal-networks.
Finally, we evaluated our approach in an actual robotic environment showing that our architecture indeed reduces the overall computational time.

[Download paper here](https://academic.oup.com/logcom/advance-article/doi/10.1093/logcom/exad036/7227283?utm_source=advanceaccess&utm_campaign=logcom&utm_medium=email)
