---
title: "A Data-Efficient Model-Based Learning Framework for the Closed-Loop Control of Continuum Robots"
collection: publications
permalink: /publication/Tendon_continuum_robot_control
excerpt: 'This paper presents a model-based learning framework for continuum robot closed-loop control that, by combining simulation and real data, shows to require only 100 real data to outperform a real-data-only controller trained using up to 10000 points. The introduced data-efficient framework with three control policies has utilized a Gaussian process regression (GPR) and a recurrent neural network (RNN).'
date: April 2022 
venue: '2022 IEEE 5th International Conference on Soft Robotics (RoboSoft)'
paperurl: 'https://arxiv.org/abs/2204.10454'
videourl: 'https://www.youtube.com/embed/1-qUU-PjG4o'
citation: 'Xinran, Wang, and Nicolas Rojas. "A Data-Efficient Model-Based Learning Framework for the Closed-Loop Control of Continuum Robots." In 2022 IEEE 5th International Conference on Soft Robotics (RoboSoft), pp. 247-254. IEEE, 2022'
---
Traditional dynamic models of continuum robots are in general computationally expensive and not suitable for real-time control. Recent approaches using learning-based methods to approximate the dynamic model of continuum robots for control have been promising, although real data hungry -- which may cause potential damage to robots and be time consuming -- and getting poorer performance when trained with simulation data only. This paper presents a model-based learning framework for continuum robot closed-loop control that, by combining simulation and real data, shows to require only 100 real data to outperform a real-data-only controller trained using up to 10000 points. The introduced data-efficient framework with three control policies has utilized a Gaussian process regression (GPR) and a recurrent neural network (RNN). Control policy A uses a GPR model and a RNN trained in simulation to optimize control outputs for simulated targets; control policy B retrains the RNN in policy A with data generated from the GPR model to adapt to real robot physics; control policy C utilizes policy A and B to form a hybrid policy. Using a continuum robot with soft spines, we show that our approach provides an efficient framework to bridge the sim-to-real gap in model-based learning for continuum robots.

[Download paper here](https://arxiv.org/pdf/2204.10454.pdf)

