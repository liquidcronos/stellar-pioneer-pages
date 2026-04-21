---
title: "From CAD to POMDP: Probabilistic Planning for Robotic Disassembly of
  End-of-Life Products"
authors:
  - Jan Baumgärtner
  - Malte Hansjosten
  - David Hald
  - Adrian Hauptmannl
  - Alexander Puchta
  - Jürgen Fleischer
date: 2025-01-01T00:00:00Z
hugoblox:
  ids:
    doi: 10.48550/ARXIV.2511.23407
publication_types:
  - article-journal
publication: ""
publication_short: ""
abstract: To support the circular economy, robotic systems must not only
  assemble new products but also disassemble end-of-life (EOL) ones for reuse,
  recycling, or safe disposal. Existing approaches to disassembly sequence
  planning often assume deterministic and fully observable product models, yet
  real EOL products frequently deviate from their initial designs due to wear,
  corrosion, or undocumented repairs. We argue that disassembly should therefore
  be formulated as a Partially Observable Markov Decision Process (POMDP), which
  naturally captures uncertainty about the product's internal state. We present
  a mathematical formulation of disassembly as a POMDP, in which hidden
  variables represent uncertain structural or physical properties. Building on
  this formulation, we propose a task and motion planning framework that
  automatically derives specific POMDP models from CAD data, robot capabilities,
  and inspection results. To obtain tractable policies, we approximate this
  formulation with a reinforcement-learning approach that operates on stochastic
  action outcomes informed by inspection priors, while a Bayesian filter
  continuously maintains beliefs over latent EOL conditions during execution.
  Using three products on two robotic systems, we demonstrate that this
  probabilistic planning framework outperforms deterministic baselines in terms
  of average disassembly time and variance, generalizes across different robot
  setups, and successfully adapts to deviations from the CAD model, such as
  missing or stuck parts.
links:
  - type: source
    url: https://arxiv.org/abs/2511.23407
  - type: Website
    url: https://wbk-robotics.github.io/From-CAD-to-POMDP/
featured: true
image:
  filename: cad2pomdp.gif
  focal_point: Center
  preview_only: false
---
