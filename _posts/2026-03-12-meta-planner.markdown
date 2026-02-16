---
layout: post
title:  "Resource-rational Adaptive Planning under Uncertainty"
date:   2026-02-15 23:59:59 +00:00
image: /images/meta-planner2.png
categories: research
author: "Peter Nickl"
authors: <strong>Peter Nickl</strong>, Pablo Tano, Alexandre Pouget
venue: "Computational and Systems Neuroscience (COSYNE)"
excerpt: We propose a normative meta-planning framework for adaptive allocation of planning resources under uncertainty and resource constraints.
abstract: Planning in stochastic environments is a fundamental challenge for model-based reinforcement learning, particularly with imperfect world models and limited data. We introduce a meta-planner that adaptively decides when and how far ahead to plan using uncertainty estimates. At each planning step, the meta-planner receives world-model predictive uncertainty as features, decomposed into aleatoric (inherent stochasticity) and epistemic (model uncertainty) components, and evaluates candidate planning configurations. It selects a planning horizon H (how far?) and planning interval F (when?; number of executed actions before replanning) by predicting returns for each configuration via supervised learning. The meta-planner accounts for the cost of mental simulation, proportional to H/F , which enables trade-offs between performance and resource use. Using the selected planning parameters, a low-level planner optimizes action sequences via probabilistic world-model rollouts over horizon H and executes the first F actions before querying the meta-planner again. In a navigation task inspired by a rodent-escape paradigm, our approach matches the performance of the best fixed configuration at substantially lower planning cost. This meta-planning framework offers a normative perspective on how biological agents might adaptively allocate planning resources under uncertainty and resource constraints.
---
