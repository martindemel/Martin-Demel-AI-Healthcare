# Discussion 9: Reinforcement Learning for Ventilation Management

## Week Topic

Reinforcement learning (RL) principles and their application to sequential clinical decisions.

## Key Learnings

Reinforcement learning is different from one-time prediction because it learns a policy for a sequence of decisions, not just a single label. RL has four core pieces: a state, an action, a reward, and a policy. In a NICU example, the state could include oxygen saturation trends, blood gas values, and respiratory support level; the action could be changing inspired oxygen or ventilator settings; and the reward could reflect staying in target ranges while avoiding harm. Prelipcean and colleagues (2025) describe the NICU as a data-rich setting for clinical decision support, yet Schouten and colleagues (2024) found that most neonatal and pediatric intensive care AI models still remain in prototyping and rarely reach routine bedside use. Evaluation matters as much as the algorithm itself — Roggeveen and colleagues (2024) showed why off-policy evaluation and policy restriction matter, because a policy can look strong under one reward setup yet become less convincing under others.

## Reflection

If a NICU eventually uses reinforcement learning for oxygen or ventilation decisions, how should the care team decide which actions must stay clinician-controlled, and what evidence would be strong enough to show that a learned policy is safer than experienced bedside practice?
