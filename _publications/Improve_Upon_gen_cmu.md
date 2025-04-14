---
title: "Improving Upon the generalized c-mu rule: a Whittle approach"
collection: publications
permalink: /publications/Whittle
excerpt: ''
paperurl: 'http://Li-Zhouzi.github.io/files/whittle_TVHC.pdf'
---
**Zhouzi Li**, Keerthana Gurushankar, Mor Harchol-Balter, Alan Scheller-Wolf

**Abstract:** Scheduling a stream of jobs whose holding cost changes over time is a classic and practical problem.  Specifically, each job is associated with a holding cost (penalty), where a job's instantaneous holding cost is some increasing function of its class and current age (the time it has spent in the system since its arrival). The goal is to schedule the jobs to minimize the time-average total holding cost across all jobs.

The seminal paper on this problem, by Van Mieghem in 1995, introduced the generalized c-mu rule for scheduling jobs.  Since then, this problem has attracted significant interest  but remains challenging due to the absence of a finite-dimensional state space formulation. Consequently, subsequent works focus on more tractable versions of this problem.

This paper returns to the original problem, deriving a heuristic that empirically improves upon the generalized c-mu rule and all existing heuristics. Our approach is to first translate the holding cost minimization problem to a novel Restless Multi-Armed Bandit (R-MAB) problem with a finite number of arms. Based on our R-MAB, we derive a novel Whittle Index policy, which is both elegant and intuitive. 