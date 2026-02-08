---
title:          "Lipschitz-Regularized Path-Strength Refactoring for Differentiable Architecture Search"
# date:           2026-01-05 00:01:00 +0800
selected:       true
pub:            "Neurocomputing"
status:         "submitted"
pub_date:       "2026"
abstract: >-

Differentiable Architecture Search (DARTS) has significantly advanced neural architecture search through efficient gradient-based optimization, yet it remains hindered by optimization instability and the notorious ``performance collapse'' issue. In this paper, we propose Lip-DARTS, a novel framework that addresses these challenges via Lipschitz-regularized search space reformulation and path-strength refactoring. By imposing strict Lipschitz constraints, we stabilize the gradient landscape and establish a rigorous connection between loss functions and path gradients. This theoretical foundation enables the decoupling of the traditionally unstable bi-level optimization into a sequential single-level process. Specifically, architecture selection is refactored into the evaluation of path-strength metrics, allowing the search to be efficiently conducted via heuristic optimization algorithms such as Simulated Annealing (SA). Experimental results and ablation studies demonstrate that Lip-DARTS not only maintains high efficiency but also effectively circumvents performance collapse, particularly the over-representation of skip connections. Specifically, it achieves a test error of 3.11\% on CIFAR-10 and an error rate of 18.74\% on CIFAR-100. Notably, the method reduces the marginal search cost to merely 0.04 GPU days, offering a stable and practitioner-friendly solution for discovering high-performance architectures across diverse datasets.

cover:          /assets/images/covers/lipdartsselect.png
authors:
- Zilin Wang
- Qingtian Liu
- Zihao Chen
- Suohai Fan
# links:
#   Paper: https://www.cell.com
---