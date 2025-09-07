---
title: "Parallelizable Job Scheduling within a Budget (Machine Learning training jobs)"
collection: projects
permalink: /projects/parallel
excerpt: ''
status: 'In Progress'
start_date: '2024-03'
---

**Project Team:** **Zhouzi Li**, Cindy Zhu, Ben Berg, Arpan Mukhopadhyay, Mor Harchol-Balter

**Description:** Machine learning has become the dominant workload in computing, powering applications from computer vision to natural language processing. The cost of training these models is staggering: organizations now spend billions of dollars per year renting GPUs in the cloud. Such a high cost begs the answer to the question: <em>How to efficiently allocate expensive GPU resources to the machine learning workloads?</em>

**Key Features:**

- Feature 1: ML training jobs are highly parallelizable, yet with imperfect speedup: doubling GPUs rarely halves completion time, and different jobs scale differently.

- Feature 2: One can scale up or down the size of the cluster in real world, but they have to stay in a certain budget (either energy or money).

- Feature 3: One needs to schedule a stream of ML training jobs instead of just one. The users care about the response time (latency) or these jobs. 


**Current Status:** 

- We theoretically find the optimal policy;

- Preliminary simulation shows our policy hugely improves the budget-latency Pareto frontier, reducing the response time by up to 2--3 times compared with existing systems;

- Implementation in progress.
