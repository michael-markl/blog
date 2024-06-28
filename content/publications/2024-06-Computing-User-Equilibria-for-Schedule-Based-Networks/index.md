---
title: "Computing User Equilibria for Schedule-Based Transit Networks with Hard Vehicle Capacities"
date: 2024-06-24T12:00:00+01:00
slug: "computing-user-equilibria-for-schedule-based-transit-network-with-hard-vehicle-capacities"
draft: false
summary: Modelling passenger assignments in public transport networks is a fundamental task for city planners, especially when deliberating network infrastructure decisions. A key aspect of a realistic model for passenger assignments is to integrate selfish routing behaviour of passengers on the one hand, and the limited vehicle capacities on the other hand. We formulate a side-constrained user equilibrium model in a schedule-based time-expanded transit network, where passengers are modelled via a continuum of non-atomic agents that want to travel with a fixed start time from a user-specific origin to a destination. An agent's route may comprise several rides along given lines, each using vehicles with hard loading capacities. We give a characterization of (side-constrained) user equilibria via a quasi-variational inequality and prove their existence by generalizing a well-known existence result of Bernstein and Smith (Transp. Sci., 1994). We further derive a polynomial time algorithm for single-commodity instances and an exact finite time algorithm for the multi-commodity case. Based on our quasi-variational characterization, we finally devise a fast heuristic computing user equilibria, which is tested on real-world instances based on data gained from the Hamburg S-Bahn system and the Swiss long-distance train network. It turns out that w.r.t. the total travel time, the computed user-equilibria are quite efficient compared to a system optimum, which neglects equilibrium constraints and only minimizes total travel time.
joint-authors: Tobias Harks, Sven Jäger, and Philine Schiewe
---

## Abstract

Modelling passenger assignments in public transport networks is a fundamental task for city planners, especially when deliberating network infrastructure decisions. A key aspect of a realistic model for passenger assignments is to integrate selfish routing behaviour of passengers on the one hand, and the limited vehicle capacities on the other hand. We formulate a side-constrained user equilibrium model in a schedule-based time-expanded transit network, where passengers are modelled via a continuum of non-atomic agents that want to travel with a fixed start time from a user-specific origin to a destination. An agent's route may comprise several rides along given lines, each using vehicles with hard loading capacities. We give a characterization of (side-constrained) user equilibria via a quasi-variational inequality and prove their existence by generalizing a well-known existence result of Bernstein and Smith (Transp. Sci., 1994). We further derive a polynomial time algorithm for single-commodity instances and an exact finite time algorithm for the multi-commodity case. Based on our quasi-variational characterization, we finally devise a fast heuristic computing user equilibria, which is tested on real-world instances based on data gained from the Hamburg S-Bahn system and the Swiss long-distance train network. It turns out that w.r.t. the total travel time, the computed user-equilibria are quite efficient compared to a system optimum, which neglects equilibrium constraints and only minimizes total travel time.

## Publications

* ArXiv Preprint: {{< doi "10.48550/arXiv.2406.17153" >}}

## Supplementary Material

* Source Code on [GitHub](https://github.com/ArbeitsgruppeTobiasHarks/sbta)
