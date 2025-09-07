---
title: "LookAhead: The Optimal Non-decreasing Index Policy for a Time-Varying Holding Cost problem"
collection: publications
permalink: /publications/LookAhead
excerpt: ''
paperurl: 'http://Li-Zhouzi.github.io/files/LookAhead.pdf'
---
**Zhouzi Li**, Keerthana Gurushankar, Mor Harchol-Balter, Alan Scheller-Wolf

**Abstract:** In practice, the cost of delaying a job can grow as the job waits. Such behavior is modeled by the Time-Varying Holding Cost (TVHC) problem, where each job's instantaneous holding cost increases with its current age (a job's age is the time since it arrived). The goal of the TVHC problem is to find a scheduling policy that minimizes the time-average total holding cost across all jobs. 


However, no optimality results are known for the TVHC problem outside of the asymptotic regime. In this paper, we study a simple yet still challenging special case: A two-class M/M/1 queue in which class 1 jobs incur a non-decreasing, time-varying holding cost and class 2 jobs incur a constant holding cost.

Our main contribution is deriving the first optimal (non-decreasing) index policy for this special case of the TVHC problem. Our optimal policy, called LookAhead, stems from the following idea: Rather than considering each job's current holding cost when making scheduling decisions, we should look at their cost some X time into the future, where this X is intuitively called the "lookahead amount."  This paper derives that optimal lookahead amount.