---
title: "NEU Autonomy Lab - Research"
layout: textlay
excerpt: "NEU Autonomy Lab -- Research"
sitemap: false
permalink: /research/
---

# Research

The NEU Autonomy Lab investigates a broad range of topics, including:

## Certifiable Deep Learning

Learning-based methods could provide solutions to many of the long-standing challenges in control and autonomy. However, the neural networks (NNs) commonly used in modern learning approaches present substantial challenges for analyzing the resulting systems' safety properties. Fortunately, a new body of literature could provide tractable methods for analysis and verification of these high dimensional, highly nonlinear representations. We are particularly interested in developing techniques to provide formal guarantees of neural feedback loops (e.g., dynamical systems driven by a NN control policy). The provided tools are shown to enable closed-loop reachability analysis and robust deep reinforcement learning.

<div class="row">
<div class="col-sm-9">
<img src="{{ site.url }}{{ site.baseurl }}/images/nfls.png" class="img-responsive" width="100%" style="float: left" />
</div>
<div class="col-sm-3">
<img src="{{ site.url }}{{ site.baseurl }}/images/icra21_diagram.png" class="img-responsive" width="100%" style="float: left" />
</div>
</div>


#### Sample publications:
- Everett, Michael. "Neural Network Verification in Control." In 2021 60th IEEE Conference on Decision and Control (CDC), pp. 6326-6340. IEEE, 2021.
- Everett, Michael, Björn Lütjens, and Jonathan P. How. "Certifiable robustness to adversarial state uncertainty in deep reinforcement learning." IEEE Transactions on Neural Networks and Learning Systems (2021).
- Everett, Michael, Golnaz Habibi, Chuangchuang Sun, and Jonathan P. How. "Reachability analysis of neural feedback loops." IEEE Access 9 (2021): 163938-163953.
- Rober, Nicholas, Sydney M. Katz, Chelsea Sidrane, Esen Yel, Michael Everett, Mykel J. Kochenderfer, and Jonathan P. How. "Backward Reachability Analysis of Neural Feedback Loops: Techniques for Linear and Nonlinear Systems." arXiv preprint arXiv:2209.14076 (2022).

## High-Speed, Off-Road Autonomy



<div class="row">
<div class="col-sm-9">
<p>High vehicle speed and off-road environments each present exciting challenges for modern autonomy pipelines. To achieve high speed, the algorithms must quickly reason about the massive amount of data coming from various sensor streams. To navigate off-road, it is critical to understand both the geometry and semantics of the scene (e.g., a robot may be able to drive through soft bushes but not a fallen log). Our work has focused on learning a cost-to-go estimator to enable aggressive, online model predictive control (MPC)-based motion planning.</p>
</div>
<div class="col-sm-3">
<img src="{{ site.url }}{{ site.baseurl }}/images/jackal_offroad_small.png" class="img-responsive" width="100%" style="float: left" />
</div>
</div>

#### Sample publications:
- Everett, Michael, Justin Miller, and Jonathan P. How. "Planning beyond the sensing horizon using a learned context." In 2019 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), pp. 1064-1071. IEEE, 2019.
- Tordesillas, Jesus, Brett T. Lopez, Michael Everett, and Jonathan P. How. "FASTER: Fast and safe trajectory planner for navigation in unknown environments." IEEE Transactions on Robotics 38, no. 2 (2021): 922-938.
- Cai, Xiaoyi, Michael Everett, Jonathan Fink, and Jonathan P. How. "Risk-Aware Off-Road Navigation via a Learned Speed Distribution Map." arXiv preprint arXiv:2203.13429 (2022).
- Sharma, Lakshay, Michael Everett, Donggun Lee, Xiaoyi Cai, Philip Osteen, and Jonathan P. How. "RAMP: A Risk-Aware Mapping and Planning Pipeline for Fast Off-Road Ground Robot Navigation." arXiv preprint arXiv:2210.06605 (2022).
- Cai, Xiaoyi, Michael Everett, Lakshay Sharma, Philip R. Osteen, and Jonathan P. How. "Probabilistic Traversability Model for Risk-Aware Motion Planning in Off-Road Environments." arXiv preprint arXiv:2210.00153 (2022).


## Autonomy in Human Environments

<div class="row">
<div class="col-sm-3">
<img src="{{ site.url }}{{ site.baseurl }}/images/jackal.gif" class="img-responsive" width="100%" style="float: left" />
</div>
<div class="col-sm-9">
<p>Today's robots are designed *for* humans, but are rarely deployed *among* humans. We are particularly interested in the problem of social navigation, where a robot must navigate through a pedestrian-rich environment, such as a busy airport terminal. We proposed several reinforcement learning (RL)-based methods and more recently introduced a hybrid MPC-RL motion planning framework to capture hard constraints for vehicle kinodynamics and collision avoidance. Our socially aware robot was featured by the Boston Globe, BBC Radio, and the Today Show.
</p>
</div>
</div>

#### Sample publications:
- Everett, Michael, Yu Fan Chen, and Jonathan P. How. "Collision avoidance in pedestrian-rich environments with deep reinforcement learning." IEEE Access 9 (2021): 10357-10377.
- Chen, Yu Fan, Michael Everett, Miao Liu, and Jonathan P. How. "Socially aware motion planning with deep reinforcement learning." In 2017 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), pp. 1343-1350. IEEE, 2017.
- Brito, Bruno, Michael Everett, Jonathan P. How, and Javier Alonso-Mora. "Where to go next: learning a subgoal recommendation policy for navigation in dynamic environments." IEEE Robotics and Automation Letters 6, no. 3 (2021): 4616-4623.


