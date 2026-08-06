---
layout: archive
title: "Research Interests"
permalink: /research/
author_profile: true
---

My interests are centered on how machine learning systems discover useful structure from data and interaction. I would like to understand what makes a learned representation useful beyond its training examples: whether it preserves information needed for prediction and intervention, supports planning, and transfers to new tasks or environments. These interests are still developing, but several themes recur in the questions I find most compelling.

## Representation and Abstraction

I am interested in why some learned representations capture reusable structure while others rely on brittle shortcuts, and which assumptions or inductive biases are needed for useful structure to emerge. These assumptions might come from the data, architecture, learning objective, temporal structure, interaction, or access to interventions.

I am also interested in how agents can learn appropriate levels of abstraction. What can safely be ignored depends on the task, planning horizon, and environment. I would like to understand how agents can select among different levels of description and retain useful abstractions as tasks change. Ideas from compression may help explain this process, but compression can also discard variables that remain important for control or intervention.

## Causality and Compositionality

Causal representation learning interests me because causal structure may help models remain useful when environments change or familiar components are recombined. I would like to better understand when latent causal variables can be recovered, what forms of temporal structure or intervention make this possible, and whether agents can discover causal structure through their own actions.

Related questions arise in compositional and object-centric learning. Rather than assuming one decomposition is always correct, I am interested in how a learner might discover which entities, mechanisms, or distinctions are useful for a domain and likely to remain useful under new tasks and interventions.

## World Models, Uncertainty, and Planning

I am interested in world models that help an agent reason and act, rather than only predict the next observation. Ideally, such a model would capture stable and controllable aspects of an environment, represent uncertainty, and support planning at multiple scales.

Interaction matters because an agent can choose what information to collect through exploration or intervention. Bayesian methods offer tools for separating uncertainty due to limited knowledge from randomness in the environment. My work on Bayesian reinforcement learning and Monte Carlo tree search has introduced me to these questions, although I see Bayesian methods as tools rather than the boundary of my interests.

I am also interested in hierarchical reinforcement learning and temporal abstraction. I would like to understand how useful hierarchies can be learned, when they genuinely simplify planning, and how their value for control can be tested rather than assumed.

## Research Approach

The kind of work I enjoy combines a precise conceptual question with mathematical analysis and serious implementation. I value theory when it clarifies assumptions or expected behavior, and experiments when they test those ideas and reveal failure modes. Across these topics, the common thread for me is understanding how useful structure is learned and how it can help an agent reason, plan, and generalize.
