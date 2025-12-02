---
title: "A new adaptive mesh refinement to model water flow around fishing nets"
authors:
  - M. Devilliers
  - B. Vincent
  - I. Mnassri
collection: publications
date: 2016-01-01
doi: "10.1016/j.oceaneng.2015.12.009"
link: "https://www.sciencedirect.com/science/article/pii/S0029801815006630"
excerpt: "A new adaptive mesh refinement strategy applied to fluid–structure interaction problems, demonstrating efficient, low-memory refinement for modeling water flow around submerged fishing nets."
keywords:
  - Adaptive mesh refinement
  - Fluid mechanics
  - 3D model
  - Riemann problem
  - Fluid–structure interaction
  - Net deployment
---

This paper presents a new adaptive mesh refinement (AMR) strategy that offers an alternative to classic AMR methods, with automatic local refinement requiring very little additional memory. The approach provides strong computational efficiency and makes it a good candidate for complex applications where memory use is constrained.

The method is applied to a fluid–structure interaction test case: predicting the hydrodynamic behavior of a submerged fishing net. Because the structure code already consumes significant memory, the proposed scheme avoids additional data structures by using a local numbering system to identify neighboring cells. The auto-adaptive mesh is applied to a 3D fluid model simulating flow around a netting panel, showing promising results for fisheries applications and scientific analysis.
