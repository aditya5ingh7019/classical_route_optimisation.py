# classical_route_optimisation.py
To establish a baseline for small-scale route optimisation, a Python-based classical approach was implemented using random search and full permutation enumeration.
Classical Route Optimisation (TSP Baseline)

This repository contains a classical baseline implementation for route optimisation using a small-scale Travelling Salesman Problem (TSP) formulation. The work serves as a foundational reference for subsequent exploration of quantum and hybrid quantum–classical optimisation algorithms within an NTCC project.

Overview:

Route optimisation problems such as TSP are computationally challenging due to their combinatorial growth with problem size. Before applying quantum optimisation techniques, it is essential to establish a classical reference solution for comparison.

In this notebook:

Cities are represented as points in a 2D plane.
Route cost is computed using Euclidean distance.
Two classical approaches are evaluated:
Random search (heuristic baseline)
Exhaustive permutation search (exact solution for small instances)
Implementation Details

Language: Python
Environment: Jupyter Notebook
Problem Size: 4 cities (demonstration-scale)

The notebook includes:
Distance and cost function definitions
Randomised route sampling
Exhaustive evaluation of all possible routes
Stored execution outputs for reproducibility

Results:

The random search approach is able to approximate the optimal route, while exhaustive search confirms the true minimum-cost solution. This validates the correctness of the cost formulation and provides a reference benchmark for future quantum-assisted optimisation experiments.
