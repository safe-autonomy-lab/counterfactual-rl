# counterfactual-rl
Counterfactual Explanations for RL

This repository implements the method proposed in the paper:

> **"Counterfactual Explanations for Continuous Action Reinforcement Learning"**
> Shuyang Dong, Shangtong Zhang, Lu Feng. University of Virginia, IJCAI 2025 (under review)

GitHub repository: [https://github.com/shuyang-dong/Counterfactual\_Explanation\_for\_RL](https://github.com/shuyang-dong/Counterfactual_Explanation_for_RL)

---

## Overview

This project presents a novel method for generating counterfactual explanations in reinforcement learning with continuous action spaces. It aims to answer: *"What small changes to the agent's actions would have led to a better outcome?"* The method integrates a custom distance metric for action trajectories, a reward shaping mechanism based on potential functions, and an adapted TD3 algorithm for learning optimal counterfactual policies.

The approach is evaluated on two domains:

* **Type 1 Diabetes management** using the UVA/PADOVA simulator, where alternative insulin dosages are recommended.
* **OpenAI Gym's Lunar Lander**, where the agent is guided to generate safer landing behaviors.

This framework supports both unconstrained and constrained counterfactual generation, allowing it to adapt to domain-specific requirements (e.g., safety or clinical constraints).

For more details, implementation, and experimental results, visit the main repository:
[https://github.com/shuyang-dong/Counterfactual\_Explanation\_for\_RL](https://github.com/shuyang-dong/Counterfactual_Explanation_for_RL)
