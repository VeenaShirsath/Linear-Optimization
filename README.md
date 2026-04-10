# Energy Systems Optimization (inspired by a course on Economics of Modern Power Systems)

This repository has work inspired from a course on Economics of Modern Power Markets, with a focus on optimization methods for energy systems modelling using Python and Pyomo. This is the stepping stone to other repositories on power systems.

## What is included

- `Intro_to_LP.ipynb`
  - Introductory linear programming models implemented in Pyomo
  - Demonstrates formulation of production planning, resource constraints, and solver-based optimization
  - Includes a structured example on production scheduling with machine availability and profit maximization

- `IPP_Optimization.ipynb`
  - Reservoir operation model for an independent power producer (IPP)
  - Implements a monthly water allocation problem with electricity and irrigation revenue streams
  - Covers water balance, storage bounds, generation limits, and dual variable analysis for marginal value interpretation

- `Energy_Management_System.ipynb`
  - Residential PV plus battery system management model
  - Uses hourly PV generation, load profiles, and time-varying electricity prices
  - Optimizes grid import, charging/discharging, and battery state-of-charge under operational constraints

## Skills demonstrated

- Linear and mixed-integer optimization modeling with Pyomo
- Energy system formulation for hydro reservoir dispatch and distributed PV-battery management
- Data-driven model construction using NumPy and pandas
- Solver integration with open-source tools such as GLPK and CBC
- Interpretation of dual prices and operational schedules for system-level decision support

## Background

These notebooks show a methodical approach to translating energy economics and engineering constraints into mathematical models that support practical operational decisions. The examples are grounded in real-world power system contexts, such as resource adequacy, storage optimization, and revenue-driven dispatch.
