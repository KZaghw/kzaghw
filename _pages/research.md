---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My research asks how learning systems can build representations that expose the structure needed for prediction, reasoning, and action. I am particularly interested in the interaction between representation, uncertainty, abstraction, and planning: what an agent should represent, which assumptions make useful structure recoverable, and how that structure can improve decisions under limited data and computation.

## Uncertainty and Decision-Making

I use Bayesian methods to distinguish epistemic uncertainty from uncertainty inherent in an environment. This distinction is especially useful in reinforcement learning, where an agent must decide whether uncertainty calls for exploration or reflects genuine risk.

In **Bayesian Moment Learning**, I developed a model-free distributional reinforcement-learning method that maintains a posterior over finite-dimensional mean embeddings of return distributions. The representation captures risk-relevant moments while supporting Bellman-consistent propagation, allowing value-of-perfect-information exploration to be extended to moment-based risk objectives. This work was accepted at RLC 2026 / RLJ.

I am now working on **Bayesian Monte Carlo tree search**, using Normal-Gamma edge posteriors, Bayesian Q-learning-style backups, and posterior-probability and value-of-computation criteria for deciding where and when to continue search.

## Representation, Abstraction, and Causality

I am interested in representations that are useful beyond a single prediction task: abstractions that preserve causal or decision-relevant structure, support transfer, and compose across tasks and levels of description. My current lab rotation studies when block-identifiable overcomplete representations preserve high-level causal abstractions under reparameterization.

This connects to broader questions in causal representation learning, object-centric and compositional models, and task-sensitive abstraction. I am especially interested in identifying the weakest assumptions under which useful structure becomes recoverable, rather than relying on inductive biases that work empirically but remain poorly understood.

## Hierarchical Models and Planning

Hierarchical world models offer a way to connect fine-grained observations and actions to reusable higher-level structure. In work on renormalising generative models, I reconstructed and verified a hierarchical active-inference framework, translated core MATLAB/SPM routines into Python, and clarified its derivations for inference, planning, and structure learning. The resulting paper was accepted at IWAI 2026.

My longer-term goal is to develop learning systems that discover compact, causally meaningful models of their environments and use them to explore, plan, and generalize efficiently. I prefer research that is theoretically motivated, empirically testable, and explicit about the assumptions that make its guarantees or behavior possible.
