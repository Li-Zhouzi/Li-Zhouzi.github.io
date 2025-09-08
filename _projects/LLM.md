---
title: "LLM Inference Jobs Scheduling"
collection: projects
permalink: /projects/LLM
excerpt: ''
status: 'In Progress'
start_date: '2025-05'
---

**Project Team:** **Zhouzi Li**, Siyuan Liu, Arvind Krishnamurthy, Phil Gibbons, Mor Harchol-Balter

**Description:** Large Language Model (LLM) inference workloads are now among the **largest drivers of datacenter energy consumption**, accounting for a substantial share (estimated at 15--20% of AI-related GPU energy costs). Thus, effective scheduling policies are crucial for both performance and sustainability.

Existing LLM serving systems rely on a diverse set of ad hoc heuristics (e.g., greedy batching, throughput- vs. latency-oriented scheduling). However, there is little clarity on which heuristic should be used under which workload regime.

Queueing theory used to provide such characterizations in traditional systems, but **direct application of standard queueing theory to LLM inference jobs is infeasible.** The reason is that LLM inference jobs differ fundamentally from classical queueing settings: they have distinct phases (Prefill vs. Decode), support dynamic batching, and exhibit highly variable response-time sensitivities.

Our work aims to **bridge queueing theory and LLM serving**, by developing new theoretical models tailored to inference workloads and validating them via controlled experiments. We provide provable guarantees and show how classical scheduling insights can be adapted to modern serving systems.

**Current Status:** In progress.
