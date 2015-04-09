# Organizational Churn: A Roll of the Dice? 
Our paper for the Interdisciplinary Contest in Modeling, which won the Outstanding Winner award (&lt;1%).

This repo contains the source for the paper. Although we won the award, there are still minor flaws in the paper.
Therefore, I would like to maintain this repo in order to make tiny improvements.

I WILL not make the source code public, mainly because of two reasons:

1. The code is written in a hurry, and needs some hacks/recompiles to solve the different problems.
2. The method described in our paper is simple and straightforward, so it is not hard to implement by yourselves.

For generating random numbers from Beta-Bernoulli distribution, please refer to [The Boost Library](http://www.boost.org/).

## Contributors
- [Jiaming Song](mailto:jiaming.tsong@gmail.com)
- Canyao Liu
- Chuan Yu

## Problem
[Managing Human Capital in Organizations]
(http://www.comap.com/undergraduate/contests/mcm/contests/2015/problems/2015_ICM_Problem_C.pdf)

## Certificate
[Team 37075: Jiaming Song, Canyao Liu, Chuan Yu](http://www.comap-math.com/mcm/2015Certs/37075.pdf)

## Summary (aka. Abstract)
Network science is critical to understanding management due to its extensive applications in complex 
systems with network-based structures. Since the organization of ICM forms an network structure, 
network science can be utilized to analyze dynamic processes within the team, e.g. the diffusion 
effects of organizational churn.

In this paper, we construct a Human Capital network according to the hierarchical structure of ICM 
and create a simple yet effective model to capture the dynamic processes, which includes organizational
churn, promotion, and recruitment. For organizational churn, we propose and implement our probabilistic
churn model inspired by Bayesian learning principles, which estimates and updates the likelihood of 
individual churn using the Beta-Bernoulli distribution. Then we develop three promotion measures 
based on working experience, inclination to churn, and closeness centrality. Moreover, we propose
several means of controlling the recruitment rate from the HR's perspective, and further define
some key concepts for evaluation, such as dissatisfaction and productivity.

Through extensive simulations, we show that our model is flexible enough to encompass most features
of the current situation and yield convincing productivity and cost results. We further extend our
model to scenarios with higher churn rates, and discover an interesting fact that higher churn rates
lead to lower productivity-cost ratios. In an extreme case with no recruitment, we discover
differentiated HR health degeneration among different offices over two years through visualization.

Ultimately, we incorporate methods from team science and approaches from multilayer networks in our
context to combine Human Capital network with other network layers and discuss how to improve our
estimation on organizational churn.

In summary, our model is flexible and powerful for various types of human capital dynamic processes.
Nevertheless, there are some existing problems such as simulation volatility which introduces extra
computational costs.
