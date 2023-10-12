---
layout: archive
title: "CV"
# permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Research Interests
======
* Broad interests in theoretical computer science.
* Research experiences and publications in **deep learning theory and online algorithm design**.

Education
======
* **IIIS, Tsinghua University, Beijing**, from Aug. 2019 – Present

  * Special CS Pilot Class (**Yao Class**, established by Turing Award Laureate, **Prof. Andrew Chi-Chih Yao**) 
  
  *  **Overall GPA 3.91/4.0 (7/30)**
  *  **GRE: 325** (Verbal: 155, Quantitative: 170, Writing: 3.5); **TOEFL: 109** (Speaking: 23, Reading: 30, Listening: 29, Writing: 27)
* **Department of Computer Science, Carnegie Mellon University, Pittsburgh**, from March 2022 - Aug. 2022
  * Undergraduate Visiting Research Intern; Supervised by **Prof. Anupam Gupta**

Research experience
======
## **Online Algorithm (Graph Searching with Predictions).**

<p align = "right"> 3.2022 – present</p>

**Student Research Intern, advised by [Prof. Anupam Gupta](https://www.cs.cmu.edu/~anupamg/)**

- Focus on the "Graph Searching" problem in the "advice" setting: *Consider an agent exploring an unknown graph in search of some goal state. As it walks around the graph, it learns the nodes and their neighbors, at the same time **predictions of their distance to the goal state**. The agent only knows where the goal state is when it reaches it. The objective is to minimize the total movement cost, even in the case when some of the predictions may be wrong.*
- **Give deterministic algorithms for the problem on unweighted trees incurring a cost $O(D+\Delta Err)$** where $D$ is the distance from the root to the goal state (which is the optimum), $\Delta$ is the maximal degree and $Err$ is the number of wrongly predicted nodes. This upper bound is proved to **match the lower bound of the problem**.
- Further go beyond trees and give an algorithm which gets good performance on (weighted) graphs with bounded doubling dimension for a "planning" version of the problem.
- Still under progress, aiming to generalize the algorithms to general graphs.


## **Learning Theory and Optimization (Analyzing Sharpness along GD Trajectory)**

<p align = "right"> 10. 2020 – 5.2022</p>

**Independent research project together with Zixuan Wang, advised by [Prof. Jian Li](http://people.iiis.tsinghua.edu.cn/~jianli)**

- Focus on the explanation of a surprising phenomenon in neural networks' optimization called **Edge of Stability (EoS, discovered by Cohen et al.  2021)**: under various network settings trained with gradient descent (GD), the **sharpness** (the largest eigenvalue of the objective’s Hessian matrix) first increases to 2/(step size) and then hovers around that value. However, the loss decreases non-monotonically despite the conventional L-smoothness assumption is violated. This phenomenon cannot be explained by traditional optimization theories.
- Divide the GD trajectory into four phases depending on the change of the sharpness value and empirically identify the norm of output layer weight as an interesting indicator of the sharpness dynamics.
- Heuristically explain **the dynamics of various essential quantities (e.g. the training loss and the sharpness)** in each phase of EoS for general neural networks under a set of assumptions.
- Theoretical prove the sharpness behavior in the EoS regime in **two-layer fully-connected linear neural networks** under weaker assumptions.

# Publications

  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

Leadership
======
* President of Yao Class (Yao 91). *Sep. 2019 – Sep.2020*
  * won the highest award for classes in Tsinghua University.

  * won the highest award for student leaders in Tsinghua University.

* Member of Study and Research Department,  IIIS's students' union. *Mar. 2021 – Present*
  * organized seminars in the direction of theoretical computer science.

* Captain of IIIS's basketball team. *Sep. 2020 - Feb.2022*

* Manager of IIIS's basketball club. *Feb. 2021 - Feb.2022*