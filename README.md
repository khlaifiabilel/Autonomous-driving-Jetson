# Autonomous-driving-Jetson

[![forthebadge](https://forthebadge.com/images/badges/powered-by-black-magic.svg)](https://forthebadge.com) [![forthebadge](https://forthebadge.com/images/badges/made-with-c-plus-plus.svg)](https://forthebadge.com) [![forthebadge](https://forthebadge.com/images/badges/made-with-python.svg)](https://forthebadge.com) [![forthebadge](https://forthebadge.com/images/badges/uses-badges.svg)](https://forthebadge.com) [![forthebadge](https://forthebadge.com/images/badges/uses-git.svg)](https://forthebadge.com)

## Project overview

Developing Autonomous vehicles (AVs) is a very challenging task in terms of Programming, Optimizing and Deployment , especially if we are working in complicated environments, Such as a mixed traffic environment where the AVs coexist with normal human-driven vehicles (HDVs). 

In this project we have developed an efficient and scalable multiagent reinforcement learning model that can be used in different dynamic traffic uses cases where the communication topology could be time-varying. Parameter sharing and local rewards are exploited to foster inter-agency cooperation while achieving great scalability. Later, An action masking scheme is employed to improve the learning efficiency by filtering out invalid/unsafe  Actions at each step. In addition, a novel priority-based safety supervisor is developed to significantly reduce the collision rate and greatly expedite the training process. A simulation environment was tuned, based on a previous open-source project published on GitHub, with three different levels of traffic densities. We exploit curriculum learning to efficiently learn harder tasks from trained models under simpler settings.
