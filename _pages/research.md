---
title: "Autonomy & Intelligence Lab at Northeastern University - Research"
layout: textlay
excerpt: "Autonomy & Intelligence Lab at Northeastern University -- Research"
sitemap: false
permalink: /research/
---

# Research

The Autonomy & Intelligence Laboratory at Northeastern University investigates a broad range of topics, including:

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
- Estornell, Alexander, Leonard Jung, and Michael Everett. "Verification of Visual Controllers via Compositional Geometric Transformations." arXiv preprint arXiv:2507.04523 (2025).
- Chaudhury, Puja, Alexander Estornell, and Michael Everett. "Learning Verifiable Control Policies Using Relaxed Verification." IEEE Conference on Decision and Control (CDC), 2025 (to appear).
- Dong, Zihao, Shayegan Omidshafiei, and Michael Everett. "Collision Avoidance Verification of Multiagent Systems With Learned Policies." IEEE Control Systems Letters (2024).
- Rober, Nicholas, Sydney M. Katz, Chelsea Sidrane, Esen Yel, Michael Everett, Mykel J. Kochenderfer, and Jonathan P. How. "Backward reachability analysis of neural feedback loops: Techniques for linear and nonlinear systems." IEEE Open Journal of Control Systems 2 (2023): 108-124.
- Everett, Michael. "Neural Network Verification in Control." In 2021 60th IEEE Conference on Decision and Control (CDC), pp. 6326-6340. IEEE, 2021.
- Everett, Michael, Björn Lütjens, and Jonathan P. How. "Certifiable robustness to adversarial state uncertainty in deep reinforcement learning." IEEE Transactions on Neural Networks and Learning Systems (2021).
- Everett, Michael, Golnaz Habibi, Chuangchuang Sun, and Jonathan P. How. "Reachability analysis of neural feedback loops." IEEE Access 9 (2021): 163938-163953.

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
- Dong, Zihao, Alan Papalia, Leonard Jung, Alenna Spiro, Philip R. Osteen, Christa S. Robison, and Michael Everett. "Learning Smooth State-Dependent Traversability from Dense Point Clouds." (2025) [Arxiv](https://arxiv.org/pdf/2506.04362).
- Jung, Leonard, Alexander Estornell, and Michael Everett. "Contingency Constrained Planning with MPPI within MPPI." Learning for Dynamics and Control (L4DC), 2025.
- Dong, Zihao, Jeff Pflueger, Leonard Jung, David Thorne, Philip R. Osteen, Christa S. Robison, Brett T. Lopez, Michael Everett. "LiDAR Inertial Odometry And Mapping Using Learned Registration-Relevant Features." In 2025 IEEE International Conference on Robotics and Automation (ICRA) 2025. [Arxiv](https://arxiv.org/pdf/2410.02961)
- Cai, Xiaoyi, Siddharth Ancha, Lakshay Sharma, Philip R. Osteen, Bernadette Bucher, Stephen Phillips, Jiuguang Wang, Michael Everett, Nicholas Roy, and Jonathan P. How. "Evora: Deep evidential traversability learning for risk-aware off-road autonomy." IEEE Transactions on Robotics (2024).
- Cai, Xiaoyi, Michael Everett, Lakshay Sharma, Philip R. Osteen, and Jonathan P. How. "Probabilistic traversability model for risk-aware motion planning in off-road environments." In 2023 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), pp. 11297-11304. IEEE, 2023.
- Sharma, Lakshay, Michael Everett, Donggun Lee, Xiaoyi Cai, Philip Osteen, and Jonathan P. How. "Ramp: A risk-aware mapping and planning pipeline for fast off-road ground robot navigation." In 2023 IEEE International Conference on Robotics and Automation (ICRA), pp. 5730-5736. IEEE, 2023.
- Cai, Xiaoyi, Michael Everett, Jonathan Fink, and Jonathan P. How. "Risk-aware off-road navigation via a learned speed distribution map." In 2022 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), pp. 2931-2937. IEEE, 2022.
- Tordesillas, Jesus, Brett T. Lopez, Michael Everett, and Jonathan P. How. "FASTER: Fast and safe trajectory planner for navigation in unknown environments." IEEE Transactions on Robotics 38, no. 2 (2021): 922-938.
- Everett, Michael, Justin Miller, and Jonathan P. How. "Planning beyond the sensing horizon using a learned context." In 2019 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), pp. 1064-1071. IEEE, 2019.

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
- Francis, Anthony, Claudia Pérez-d'Arpino, Chengshu Li, Fei Xia, Alexandre Alahi, Rachid Alami, Aniket Bera et al. "Principles and guidelines for evaluating social robot navigation algorithms." ACM Transactions on Human-Robot Interaction, 2025.
- Brito, Bruno, Michael Everett, Jonathan P. How, and Javier Alonso-Mora. "Where to go next: learning a subgoal recommendation policy for navigation in dynamic environments." IEEE Robotics and Automation Letters 6, no. 3 (2021): 4616-4623.
- Everett, Michael, Yu Fan Chen, and Jonathan P. How. "Collision avoidance in pedestrian-rich environments with deep reinforcement learning." IEEE Access 9 (2021): 10357-10377.
- Chen, Yu Fan, Michael Everett, Miao Liu, and Jonathan P. How. "Socially aware motion planning with deep reinforcement learning." In 2017 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), pp. 1343-1350. IEEE, 2017.

