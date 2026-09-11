---
layout: page
title: Open-Pit Mine Scheduling Optimizer
description: Large-scale MILP optimization for mine production planning, developed with Rio Tinto under a MITACS industrial collaboration.
img:
importance: 1
category: research
---

**Problem:** multi-period block-extraction scheduling with precedence and resource constraints, at a scale generic solvers can't handle directly.

**Approach:** custom cutting planes, rolling-horizon decomposition, and Large Neighborhood Search, implemented in C++ with OpenMP.

**Result:** 90% reduction in computation time and 80% reduction in time-to-feasibility versus the baseline approach, deployed into Rio Tinto's production planning workflows.

**Stack:** C++, Gurobi, OpenMP
