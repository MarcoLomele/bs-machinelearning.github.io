---
title: Empathy in Multi-Agent Reinforcement Learning
type: Research
status: completed
date: 2025-12-21
authors:
  - name: Christina Eirini Christodoulou
  - name: Simone De Giorgi
  - name: Lavinia Maria Alexandra Skandali
---

This paper studies whether valuing other agents’ rewards can improve outcomes in multi-agent reinforcement learning. We model empathy as a reward-weighting parameter that allows agents to partially account for the payoffs of others when updating their policies. We compare environments where empathy is fixed at different levels with environments where agents learn their level of empathy over time using a bandit-based adaptation mechanism.

We test this framework in three classic environments: the Prisoner’s Dilemma, the Stag Hunt, and a Renewable Resource Sharing setting. Across all environments, stronger empathy consistently improves cooperation, welfare, and stability. However, when empathy is learned endogenously, agents do not converge to the welfare-maximizing level and instead stabilize at intermediate values.

The paper shows that what is best for the group is not necessarily what decentralized learning dynamics discover. Even when higher empathy clearly improves outcomes, agents struggle to reach and sustain it when learning autonomously. Read the full paper to explore the results in detail and understand why the learning mechanism itself becomes the central limitation.
