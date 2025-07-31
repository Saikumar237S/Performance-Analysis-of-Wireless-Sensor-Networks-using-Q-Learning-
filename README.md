# Performance Analysis of Wireless Sensor Networks using Q-Learning

This repository includes a published research project analyzing the performance of Wireless Sensor Networks (WSNs) using Q-Learning, compared to traditional routing protocols like AODV and DSDV.

## 📄 Paper Title
**Performance Analysis of Wireless Sensor Networks using Q-Learning**

### Authors
Pulugujju Rajesh, Arra Sai Kumar, T.K. Manisha Sarayu, A. Durga Prasad, Ch. Sai Dhanush  
B.V. Raju Institute of Technology, Narsapur, India

## 🔍 Project Overview

The goal of this project was to:
- Evaluate AODV and DSDV routing protocols in a static WSN setup
- Implement Q-Learning to explore if it could improve performance
- Compare key metrics like **throughput**, **delay**, **jitter**, and **packet delivery ratio**

Simulations were performed using **NS-2**, with analysis from `.tcl`, `.awk`, and `.xg` files. Results showed that while Q-Learning performed similarly in a fixed-node setup, it holds greater potential in dynamic or mobile networks.

## 📊 Key Observations

- Q-Learning explored multiple routes intelligently and adapted to network conditions
- AODV + Q-Learning showed improved routing flexibility with reduced control overhead
- DSDV + Q-Learning reduced unnecessary routing table updates

## 🧠 Skills & Tools Used

- NS-2 Simulator
- Q-Learning Reinforcement Algorithm
- Simulation scripting (TCL, AWK)
- Network analysis: delay, throughput, packet loss

## 📘 Publication

📄 [Download Full Paper](./Performance%20analysis%20of%20wireless%20sensor%20networks%20using%20Q-learning_AI.pdf)

## ✅ Status

Project completed and open to further enhancement using Deep Q-Networks (DQN), MARL, or mobile network simulation.


