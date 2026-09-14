# PySimEd Research

Research software development conducted under Professor Barry Lawson as part of the PySimEd project.

## Overview

PySimEd is a Python implementation of simulation and statistical tools inspired by the `simEd` framework in R. My work focused on developing and validating simulation functionality in Python, particularly for queueing models and time-persistent statistics.

## My Contributions

* Developed a **single-server queue (SSQ) simulation in Python** and validated its statistical outputs against benchmarks from the R implementation of `simEd`.
* Implemented Python versions of **time-persistent statistics (TPS)** functions, including:

  * `meanTPS` — calculates a time-weighted mean based on how long the simulated process remains at each value.
  * `sdTPS` — measures time-weighted variability of a simulated process.
  * `quantileTPS` — calculates quantiles based on the proportion of simulation time spent below a given value.
* Worked on translating simulation functionality from the existing R framework into a reusable Python package.
* Began developing a **Matplotlib-based animation framework** for visualizing the evolution of single-server queue simulations, with the goal of supporting additional simulation models in the future.
* Tested Python implementations against existing results to verify numerical and statistical consistency.

## Technologies

**Python • Matplotlib • Simulation Modeling • Queueing Systems • Statistical Computing**

## Source Code

The project's source code is maintained in a private research repository. This page documents my individual contributions to the project; additional implementation details are available upon request.
