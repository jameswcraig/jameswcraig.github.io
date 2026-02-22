---
title: "Publications"
description: >-
  Peer-reviewed publications in pharmacometrics, NLME optimization, machine
  learning model selection, PBPK simulation, and pharmacometric visualization.
hidemeta: true
---


## Effective Visualizations Using "vachette" to Assess and Communicate Pharmacometric Model Results

**Jos Lommerse, Anna Largajolli, James Craig, Nele Mueller-Plock, Jeff Sachs, Amy Cheung, et al.**

*The AAPS Journal*, Vol. 27, Article 163 (2025)

DOI: [10.1208/s12248-025-01131-9](https://doi.org/10.1208/s12248-025-01131-9)

Pharmacometric model communication suffers from fragmented, stratified visualizations that lose diagnostic power with sparse or heterogeneous data. This paper introduces the vachette method (variability-aligned, covariate-harmonized effects and time-transformation equivalent), which unifies all observations into a single reference-aligned plot while preserving covariate effects and random variability. Craig is the creator and maintainer of the vachette R package (available on CRAN) that implements this method. The approach addresses a long-standing gap in model evaluation by enabling non-modelers to interpret complex NLME model behavior.

---

## ADPO: Automatic-Differentiation-Assisted Parametric Optimization

**Shuhua Hu, James Craig, et al.**

*Journal of Pharmacokinetics and Pharmacodynamics*, Vol. 52, Article 53 (2025)

DOI: [10.1007/s10928-025-09997-0](https://doi.org/10.1007/s10928-025-09997-0)

NLME parameter estimation traditionally relies on finite-difference gradient approximations, which are computationally expensive and numerically imprecise for complex ODE-based models. ADPO replaces finite-difference gradients with automatic differentiation for FOCE ELS, Laplacian, and adaptive Gaussian quadrature algorithms, reducing estimation runtime by 20--50% generally and up to 95% for complex models (voriconazole). Craig contributed to the implementation within Phoenix NLME and RsNLME. This work brings modern ML-era differentiation techniques to pharmacometric estimation.

---

## Pirana and Integrated PMX Tools, a Workbench for NONMEM, NLME, pyDarwin, and RsNLME

**Rong Chen, Mark Sale, James Craig, Michael Tomashevskiy, Alex Mazur, Shuhua Hu, Keith Nieforth**

*CPT: Pharmacometrics & Systems Pharmacology*, 14(8):1298--1309 (2025)

DOI: [10.1002/psp4.70067](https://doi.org/10.1002/psp4.70067)

Pharmacometric workflows historically required manual orchestration across disconnected tools. This tutorial presents the modernized Pirana workbench integrating NLME engine (via RsNLME), Shiny-based model construction, pyDarwin ML model selection, and custom diagnostic interfaces into a unified platform. Craig contributed the RsNLME integration and Shiny interfaces (Model Builder, Model Results, VPC Results) that form the core interactive components of the workbench.

---

## Using the Simcyp R Package for PBPK Simulation Workflows With the Simcyp Simulator

**James Craig et al.**

*CPT: Pharmacometrics & Systems Pharmacology* (2025)

DOI: [10.1002/psp4.70022](https://doi.org/10.1002/psp4.70022)

PBPK/PD modeling with the Simcyp Simulator traditionally required GUI-based workflows, limiting reproducibility and scalability. This paper describes an R package enabling programmatic control of the Simcyp Simulator, demonstrating automated workflows for DDI model verification (atazanavir) and virtual bioequivalence assessment (paliperidone palmitate). Craig contributed to the R package development enabling R-based scripting, automation, and visualization of PBPK simulation outputs.

---

## pyDarwin Machine Learning Algorithms Application and Comparison in Nonlinear Mixed-Effect Model Selection and Optimization

**Mark Sale, James Craig, et al.**

*Journal of Pharmacokinetics and Pharmacodynamics*, 51:785--796 (2024)

DOI: [10.1007/s10928-024-09932-9](https://doi.org/10.1007/s10928-024-09932-9)

Population PK model selection has relied on forward addition/backward elimination (FABE) for nearly 50 years despite known limitations of local greedy search. This paper benchmarks five ML algorithms (GA, GP, RF, GBRT, PSO) against an exhaustive search gold standard across 1.57M model combinations. All algorithms found the global optimum when combined with two-bit local search. Craig contributed to the software infrastructure (pyDarwin/RsNLME integration) enabling this scale of automated model search.

---

## pyDarwin: A Machine Learning Enhanced Automated Nonlinear Mixed-Effect Model Selection Toolbox

**Liang Zhao, Robert Bies, Mark Sale, James Craig, et al.**

*Clinical Pharmacology & Therapeutics*, 115(4):758--773 (2024)

DOI: [10.1002/cpt.3114](https://doi.org/10.1002/cpt.3114)

Manual pharmacometric model selection is labor-intensive, subjective, and prone to local optima. pyDarwin is the first open-source toolbox combining ML algorithms with NONMEM for automated global search across user-defined model spaces. This tutorial introduces the package architecture, workflow, and demonstrates application to quetiapine clinical data. Craig contributed to the software development and integration infrastructure.

---

## Research Themes

Cross-cutting themes across these publications:

- **Pharmacometric Visualization** -- Novel methods for communicating NLME model results to modelers and non-modelers (vachette)
- **Optimization Algorithms** -- Automatic differentiation for NLME estimation; replacing finite-difference with exact gradients (ADPO)
- **Machine Learning Model Selection** -- ML-driven alternatives to traditional stepwise search across combinatorial model spaces (pyDarwin)
- **Workflow Integration** -- Unified platforms connecting modeling engines, diagnostic tools, and interactive interfaces (Pirana, RsNLME)
- **Simulation Systems** -- PBPK simulation automation, virtual bioequivalence assessment, VPC workflows
- **Statistical Methodology** -- OFV/-2LL minimization, FOCE/Laplacian/AGQ algorithms, simulation-based inference
