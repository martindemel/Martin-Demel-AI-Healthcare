# Assignment 9: Designing Reinforcement Learning Scenarios

## Overview

This assignment designs a reinforcement learning (RL) system to assist with respiratory care for premature infants in the NICU. RL is a type of machine learning where a computer learns by choosing an action, observing the result, and receiving feedback as a reward or penalty.

## RL System Design

| Component | Description |
|-----------|-------------|
| **State** | Gestational age, weight, oxygen saturation trends, heart rate, respiratory rate, blood gas values, apnea or bradycardia events, and current respiratory settings |
| **Action** | Small adjustment in oxygen concentration or pressure settings within safety limits set by the care team |
| **Reward** | Positive rewards for staying within target oxygen range, avoiding dangerous events, and gradually needing less support. Negative rewards for hypoxemia, hyperoxia, worsening blood gases, or emergency reintubation |

## Potential Benefits

1. **Consistency** — assists clinicians in making more consistent decisions during extended NICU stays, especially when small changes in respiratory support are repeatedly adjusted
2. **Personalization** — tailors care by learning from patterns in numerous prior cases instead of applying a uniform approach to every infant

## Safety Concerns

- An RL model cannot safely "learn by experimentation" on real newborns, so it relies heavily on historical data
- If data is incomplete, biased, or sourced from a single hospital, recommendations may not transfer to another NICU
- RL models can have difficulty with missing data and transferability when applied to different clinical environments

## Key Takeaway

RL could have a beneficial impact on healthcare because it is suited for repeated decisions that evolve over time. In the NICU, an RL tool for respiratory support could make care more personalized, consistent, and data-driven. However, it should assist clinicians rather than replace them, and must be thoroughly validated and maintained within strict safety limits.
