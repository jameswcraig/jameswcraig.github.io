---
title: "Projects"
description: >-
  Scientific modeling infrastructure, optimization systems, and cloud-native
  pharmacometric platforms spanning R, Python, and full-stack engineering.
hidemeta: true
---

Scientific modeling infrastructure and cloud-native platforms I have designed, architected, and maintained across statistical computing, optimization systems, and enterprise modeling environments.

---

# Modeling Engine Interfaces & Infrastructure

## RsNLME (R Speaks NLME)

CRAN-distributed R interface to Certara's NLME engine. Enables complete pharmacometric workflows in R — including model specification, parameter estimation, simulation, and diagnostics — across FOCE, Laplacian, and AGQ algorithms.

Designed as production-grade infrastructure bridging statistical computing (R) with compiled estimation engines.

**Key Contributions**
- Engine wrapper architecture
- Cross-platform execution orchestration
- PML-based model specification pipeline
- Shiny-integrated interactive workflows
- CRAN-compliant package engineering

**Technologies:** R, NLME engine, PML, S4/R6 OOP, Shiny

[Documentation](https://certara.github.io/R-RsNLME)

---

# Optimization & Automated Model Search

## pyDarwin (Machine Learning–Driven Model Selection)

Architectural contributor to **pyDarwin**, a machine learning framework for automated population PK model selection integrating NONMEM and NLME engines.

Designed and validated large-scale search infrastructure spanning 1.57M model combinations to ensure reproducible global optimum discovery.

Supports multiple optimization strategies:
- Genetic Algorithms (GA)
- Gaussian Processes (GP)
- Random Forests (RF)
- Gradient Boosted Regression Trees (GBRT)
- Particle Swarm Optimization (PSO)

This work formalizes algorithmic model search as reproducible scientific infrastructure rather than heuristic exploration.

**Technologies:** Python, R, NONMEM, NLME, machine learning algorithms

[Documentation](https://certara.github.io/pyDarwin/html/index.html)  
[GitHub](https://github.com/certara/pyDarwin)

---

# Simulation Diagnostics & Visualization Systems

## tidyvpc

CRAN-distributed R package implementing simulation-based Visual Predictive Checks (VPCs) for NLME models.

Provides a structured, tidy interface for generating prediction-corrected, stratified, and binless VPCs with reproducible simulation diagnostics.

**Technologies:** R, tidyverse, simulation workflows

[Documentation](https://certara.github.io/tidyvpc/)

---

## vachette

CRAN-distributed R package introducing a novel covariate-harmonized visualization methodology for pharmacometric models.

Implements variability-aligned, time-transformation equivalent (vachette) plots that unify observations into a single reference-aligned diagnostic framework.

Published in *The AAPS Journal* (2025).

**Technologies:** R, ggplot2, NLME diagnostics

[CRAN](https://cran.r-project.org/web/packages/vachette/)  
[DOI: 10.1208/s12248-025-01131-9](https://doi.org/10.1208/s12248-025-01131-9)

---

# Integrated Modeling Workbench Systems

## Pirana Shiny Application Suite

Architect and contributor to interactive modeling applications integrated into the Pirana pharmacometric workbench.

Applications include:

- **Model Builder** — graphical NLME model construction and PML generation
- **Model Results** — diagnostic plots, tables, GOF analyses, and report shell generation
- **VPC Results** — interactive visual predictive check interface

Designed modular Shiny components interfacing directly with modeling engines and automated workflows.

**Technologies:** R Shiny, RsNLME, ggplot2, Pirana APIs

---

# R Ecosystem Infrastructure

## Certara.R

Central hub for open-source pharmacometric R packages developed within the Certara ecosystem.

Provides:
- Structured package distribution (including non-standard repositories)
- Documentation via pkgdown
- Interactive tutorials via learnr
- CI-driven build and release pipelines

All major packages (RsNLME, tidyvpc, vachette, XposeNLME) are publicly distributed and CRAN-compliant where applicable.

**Technologies:** R, pkgdown, learnr, GitHub Actions, CRAN infrastructure

[Documentation](https://certara.github.io/R-Certara/)

---

# Cloud-Native Modeling Platforms

Contributions to next-generation cloud-native pharmacometric modeling platforms within the Phoenix ecosystem.

Systems include model configuration environments, simulation orchestration layers, and modeling workflow management delivered via modern full-stack architecture.

**Key Areas**
- React/TypeScript front-end systems
- Node/Express and Java-based backend services
- API integration with modeling engines
- Containerized execution environments
- OAuth/OIDC-aware identity integration
- CI/CD-enabled deployment pipelines

These platforms translate complex modeling infrastructure into scalable, production-grade cloud systems.

**Technologies:** React, TypeScript, Node/Express, Java, Docker, OAuth/OIDC