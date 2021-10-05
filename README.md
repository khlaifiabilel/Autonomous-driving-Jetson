# Autonomous-driving-Jetson

[![forthebadge](https://forthebadge.com/images/badges/powered-by-black-magic.svg)](https://forthebadge.com) [![forthebadge](https://forthebadge.com/images/badges/made-with-c-plus-plus.svg)](https://forthebadge.com) [![forthebadge](https://forthebadge.com/images/badges/made-with-python.svg)](https://forthebadge.com) [![forthebadge](https://forthebadge.com/images/badges/uses-badges.svg)](https://forthebadge.com) [![forthebadge](https://forthebadge.com/images/badges/uses-git.svg)](https://forthebadge.com)

## Project overview

Developing Autonomous vehicles (AVs) is a very challenging task in terms of Programming, Optimizing and Deployment , especially if we are working in complicated environments, Such as a mixed traffic environment where the AVs coexist with normal human-driven vehicles (HDVs). 

In this project we have developed an efficient and scalable multiagent reinforcement learning model that can be used in different dynamic traffic uses cases where the communication topology could be time-varying. Parameter sharing and local rewards are exploited to foster inter-agency cooperation while achieving great scalability. Later, An action masking scheme is employed to improve the learning efficiency by filtering out invalid/unsafe  Actions at each step. In addition, a novel priority-based safety supervisor is developed to significantly reduce the collision rate and greatly expedite the training process. A simulation environment was tuned, based on a previous open-source project published on GitHub, with three different levels of traffic densities. We exploit curriculum learning to efficiently learn harder tasks from trained models under simpler settings.

## Privious Works 

List of publications & preprints using `highway-env` (please open a pull request to add missing entries):
*   [Approximate Robust Control of Uncertain Dynamical Systems](https://arxiv.org/abs/1903.00220) (Dec 2018)
*   [Interval Prediction for Continuous-Time Systems with Parametric Uncertainties](https://arxiv.org/abs/1904.04727) (Apr 2019)
*   [Practical Open-Loop Optimistic Planning](https://arxiv.org/abs/1904.04700) (Apr 2019)
*   [α^α-Rank: Practically Scaling α-Rank through Stochastic Optimisation](https://arxiv.org/abs/1909.11628) (Sep 2019)
*   [Social Attention for Autonomous Decision-Making in Dense Traffic](https://arxiv.org/abs/1911.12250) (Nov 2019)
*   [Budgeted Reinforcement Learning in Continuous State Space](http://papers.nips.cc/paper/9128-budgeted-reinforcement-learning-in-continuous-state-space/) (Dec 2019)
*   [Multi-View Reinforcement Learning](http://papers.nips.cc/paper/8422-multi-view-reinforcement-learning) (Dec 2019)
*   [Reinforcement learning for Dialogue Systems optimization with user adaptation](https://tel.archives-ouvertes.fr/tel-02422691/) (Dec 2019)
*   [Distributional Soft Actor Critic for Risk Sensitive Learning](https://arxiv.org/abs/2004.14547) (Apr 2020)
*   [Bi-Level Actor-Critic for Multi-Agent Coordination](https://ojs.aaai.org/index.php/AAAI/article/view/6226) (Apr 2020)
*   [Task-Agnostic Online Reinforcement Learning with an Infinite Mixture of Gaussian Processes](https://arxiv.org/abs/2006.11441) (Jun 2020)
*   [Beyond Prioritized Replay: Sampling States in Model-Based RL via Simulated Priorities](https://arxiv.org/abs/2007.09569) (Jul 2020)
*   [Robust-Adaptive Interval Predictive Control for Linear Uncertain Systems](https://arxiv.org/abs/2007.10401) (Jul 2020)
*   [SMART: Simultaneous Multi-Agent Recurrent Trajectory Prediction](https://arxiv.org/abs/2007.13078) (Jul 2020)
*   [Delay-Aware Multi-Agent Reinforcement Learning for Cooperative and Competitive Environments](https://arxiv.org/abs/2005.05441) (Aug 2020)
*   [B-GAP: Behavior-Guided Action Prediction for Autonomous Navigation](https://arxiv.org/abs/2011.03748) (Nov 2020)
*   [Model-based Reinforcement Learning from Signal Temporal Logic Specifications](https://arxiv.org/abs/2011.04950) (Nov 2020)
*   [Robust-Adaptive Control of Linear Systems: beyond Quadratic Costs](https://arxiv.org/abs/2002.10816) (Dec 2020)
*   [Assessing and Accelerating Coverage in Deep Reinforcement Learning](https://arxiv.org/abs/2012.00724) (Dec 2020)
*   [Distributionally Consistent Simulation of Naturalistic Driving Environment for Autonomous Vehicle Testing](https://arxiv.org/abs/2101.02828) (Jan 2021)
*   [Interpretable Policy Specification and Synthesis through Natural Language and RL](https://arxiv.org/abs/2101.07140) (Jan 2021)
*   [Deep Reinforcement Learning Techniques in Diversified Domains: A Survey](https://link.springer.com/article/10.1007/s11831-021-09552-3) (Feb 2021)
*   [Corner Case Generation and Analysis for Safety Assessment of Autonomous Vehicles](https://arxiv.org/abs/2102.03483) (Feb 2021)
*   [Intelligent driving intelligence test for autonomous vehicles with naturalistic and adversarial environment](https://www.nature.com/articles/s41467-021-21007-8) (Feb 2021)
*   [Building Safer Autonomous Agents by Leveraging Risky Driving Behavior Knowledge](https://arxiv.org/abs/2103.10245)
*   [Quick Learner Automated Vehicle Adapting its Roadmanship to Varying Traffic Cultures with Meta Reinforcement Learning](https://arxiv.org/abs/2104.08876) (Apr 2021)
*   [Deep Multi-agent Reinforcement Learning for Highway On-Ramp Merging in Mixed Traffic](https://arxiv.org/abs/2105.05701) (May 2021)
*   [Accelerated Policy Evaluation: Learning Adversarial Environments with Adaptive Importance Sampling](https://arxiv.org/abs/2106.10566) (Jun 2021)
*   [Learning Interaction-aware Guidance Policies for Motion Planning in Dense Traffic Scenarios](https://arxiv.org/abs/2107.04538) (Jul 2021)
*   [Robust Predictable Control](https://arxiv.org/abs/2109.03214) (Sep 2021)

PhD theses
*   [Reinforcement learning for Dialogue Systems optimization with user adaptation](https://hal.inria.fr/tel-02422691/) (2019)
*   [Safe and Efficient Reinforcement Learning for Behavioural Planning in Autonomous Driving](https://hal.inria.fr/tel-03035705/) (2020)
*   [Many-agent Reinforcement Learning](https://discovery.ucl.ac.uk/id/eprint/10124273/) (2021)

Master theses
*   [Multi-Agent Reinforcement Learning with Application on Traffic Flow Control](https://www.diva-portal.org/smash/get/diva2:1573441/FULLTEXT01.pdf) (Jun 2021)
*   [Deep Reinforcement Learning for Automated Parking](https://repositorio-aberto.up.pt/bitstream/10216/136074/2/494682.pdf) (Aug 2021)
