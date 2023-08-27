---
title: "A Process Algebra for Link Layer Protocols"
date: 2019-04-09T12:00:00+01:00
slug: "a-process-algebra-for-link-layer-protocols"
draft: false
summary: We study a dynamic traffic assignment model, where agents base their instantaneous routing decisions on real-time delay predictions. We describe a general mathematical model which, in particular, includes the settings leading to IDE and DE. On the theoretical side we show existence of equilibrium solutions under some additional assumptions while on the practical side we implement a machine-learned predictor and compare it to other static predictors.
joint-authors: Rob van Glabbeek and Peter Höfner
---

## Abstract

We propose a process algebra for link layer protocols, featuring a unique mechanism for modelling frame collisions. We also formalise suitable liveness properties for link layer protocols specified in this framework. To show applicability we model and analyse two versions of the Carrier-Sense Multiple Access with Collision Avoidance (CSMA/CA) protocol. Our analysis confirms the hidden station problem for the version without virtual carrier sensing. However, we show that the version with virtual carrier sensing not only overcomes this problem, but also the exposed station problem with probability 1. Yet the protocol cannot guarantee packet delivery, not even with probability 1.

## Publications

* ArXiv Preprint: {{< doi "10.48550/arXiv.1907.13329" >}}
* Conference Paper: Proceedings of Programming Languages and Systems, ESOP 2019.
  {{< doi "10.1007/978-3-030-17184-1_24" >}}
