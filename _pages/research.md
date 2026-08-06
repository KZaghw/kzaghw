---
layout: archive
title: "Research Interests"
permalink: /research/
author_profile: true
---

My interests are centered on how machine learning systems discover useful structure from data and interaction. I would like to understand what makes a learned representation useful beyond the examples on which it was trained: whether it preserves information needed for prediction and intervention, supports planning, and transfers to new tasks or environments. These interests are still developing, but several themes recur in the questions I find most compelling.

## Representation and Abstraction

I am interested in why some learned representations capture reusable structure while others rely on brittle shortcuts. One question I find particularly important is which assumptions or inductive biases are actually needed for useful structure to emerge. These could come from the data-generating process, architecture, learning objective, temporal structure, interaction, or access to interventions.

Abstraction is closely related. An agent rarely needs every detail of an observation to solve a problem, but what can safely be ignored depends on the task, planning horizon, and environment. I would like to understand how agents can learn appropriate levels of description, select among them for different problems, and retain useful abstractions as tasks change. I am also interested in whether ideas from compression can help explain this process, and in the limits of compression when variables that appear unnecessary for prediction remain important for control or intervention.

## Causality and Compositionality

Causal representation learning interests me because causal structure may help models remain useful when environments change or familiar components are recombined. I would like to better understand when latent causal variables can be recovered from observations, what kinds of temporal structure or interventions make this possible, and whether agents can discover causal structure through their own actions.

Related questions arise in compositional and object-centric learning. Rather than assuming that a particular decomposition is always correct, I am interested in how a learner might discover which entities, mechanisms, or distinctions are useful for the domain and likely to remain useful under new tasks and interventions.

## World Models, Uncertainty, and Agency

I am interested in world models as representations that help an agent reason and act, not only predict the next observation. Ideally, such a model would capture stable and controllable aspects of an environment, represent uncertainty, and support planning at more than one spatial or temporal scale.

Interaction makes this especially interesting because an agent can choose what information to collect. It can explore, intervene, or seek observations that distinguish between competing explanations. Bayesian methods are useful here because they provide tools for separating uncertainty due to limited knowledge from randomness in the environment. My work on Bayesian distributional reinforcement learning and Bayesian Monte Carlo tree search has given me a concrete introduction to these questions, although I see Bayesian methods as tools rather than the boundary of my interests.

## Hierarchy and Planning

I am also interested in hierarchical reinforcement learning, temporal abstraction, learned skills, and multiscale planning. A hierarchy is useful for control only if its abstract states preserve the distinctions needed for decisions and its high-level choices correspond to meaningful lower-level behavior. I would like to understand how these hierarchies can be learned, when they genuinely make planning easier, and how their usefulness can be evaluated rather than assumed.

## Research Approach

The kind of work I enjoy combines a precise conceptual question with both mathematical analysis and serious implementation. I value theory when it clarifies assumptions, identifiability, or expected behavior, and experiments when they test those ideas and reveal failure modes. More generally, I am drawn to research that moves between theory and practice instead of treating either formal elegance or benchmark performance as sufficient on its own.

A related longer-term interest is machine-assisted scientific discovery: whether learning systems can infer concise, causal, or mechanistic explanations from observations and experiments. Across these topics, the common thread for me is understanding how useful structure is learned and how it can help an agent reason, plan, and generalize.
