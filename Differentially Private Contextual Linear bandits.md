# Differentially Private Contextual Linear bandits

Roshan Shariff and Or Sheffet

## Abstract

1.Contextual Linear Bandit problem, a version of standard stochastic MAB problem, where a learner sequentially select actions to maximize a reward depending also on a user provided per-round context.

2.Context is chosen arbitrarily or adversarially, the reward is assumed to be a stochastic function of a feature vector encoding context and selected action.

3.Goal: Private learning for contextual linear bandit problems.
4.Standard DP results in linear regret. Use joint DP. Convert linear-UCB into a joint DP algorithm using tree-based algorithm. Apply Guassian or Wishart noise to achieve joint-DP and bound regrets.

