---
title: "How to Rent GPUs on a Budget"
collection: publication
permalink: /publication/How-to-Rent-GPUs-on-a-Budget
excerpt: ''
venue: "EPEW"
date: "2024-6-1"
paperurl: 'http://Li-Zhouzi.github.io/files/budget.pdf'
citation: 'arXiv preprint arXiv:2406.15560.'
---
**Zhouzi Li**, Benjamin Berg, Arpan Mukhopadhyay, Mor Harchol-Balter. (Accepted by EPEW 2024)

**Abstract:** The explosion in Machine Learning (ML) over the past ten years has led to a dramatic increase in demand for GPUs to train ML models. Because it is prohibitively expensive for most users to build and maintain a large GPU cluster, large cloud providers (Microsoft Azure, Amazon AWS, Google Cloud) have seen explosive growth in demand for renting cloud-based GPUs. In this cloud-computing paradigm, a user must specify their demand for GPUs at every moment in time, and will pay for every GPU-hour they use. ML training jobs are known to be parallelizable to different degrees. Given a stream of ML training jobs, a user typically wants to minimize the mean response time across all jobs. Here, the response time of a job denotes the time from when a job arrives until it is complete. Additionally, the user is constrained by some operating budget. Specifically, in this paper the user is constrained to use no more than b GPUs per hour, over a long-run time average. The question is how to minimize mean response time while meeting the budget constraint. Because training jobs receive a diminishing marginal benefit from running on additional GPUs, allocating too many GPUs to a single training job can dramatically increase the overall cost paid by the user. Hence, an optimal rental policy must balance a tradeoff between training cost and mean response time. This paper derives the optimal rental policy for a stream of training jobs where the jobs have different levels of parallelizability (specified by a speedup function) and different job sizes (amounts of inherent work). We make almost no assumptions about the arrival process and about the job size distribution. Our optimal policy specifies how many GPUs to rent at every moment in time and how to allocate these GPUs.