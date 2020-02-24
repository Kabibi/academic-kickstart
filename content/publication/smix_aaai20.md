+++
date = "2020-02-07"
draft = true
title = "SMIX(λ): Enhancing Centralized Value Functions for Cooperative Multi-Agent Reinforcement Learning"

date: the date that your publication was first published (must be in a valid TOML date format)
publication_types: 1
publication: Proceedings of the Thirty-Fourth AAAI Conference on Artificial Intelligence (AAAI 20)
abstract: This work presents a sample efficient and effective value-based method, named SMIX(λ), for reinforcement learning in multi-agent environments (MARL) within the paradigm of centralized training with decentralized execution (CTDE), in which learning a stable and generalizable centralized value function (CVF) is crucial. To achieve this, our method carefully combines different elements, including 1) removing the unrealistic centralized greedy assumption during the learning phase, 2) using the λ-return to balance the trade-off between bias and variance and to deal with the environment's non-Markovian property, and 3) adopting an experience-replay style off-policy training. Interestingly, it is revealed that there exists inherent connection between SMIX(λ) and previous off-policy Q(λ)approach for single-agent learning. Experiments on the StarCraft Multi-Agent Challenge (SMAC) benchmark show that the proposed SMIX(λ) algorithm out-performs several state-of-the-art MARL methods by a large margin, and that it can be used as a general tool to improve the overall performance of a CTDE-type method by enhancing the evaluation quality of its CVF. We open-source our code at: https://github.com/chaovven/SMIX.

+++

