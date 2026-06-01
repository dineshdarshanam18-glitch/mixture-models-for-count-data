# Mixture Models for Multivariate Count Data

## Master's Thesis

This repository contains the thesis, simulation data, and analysis code for comparing clustering approaches for multivariate count data.

### Methods

- Poisson Mixture Models
- Anscombe Transformation + Gaussian Mixtures (Mclust)
- Poisson Log-Normal (PLN) Mixture Models

### Simulation Design

- Clusters: 2
- Variables: 3
- Sample sizes: 100, 250, 500
- Replications: 20

### Evaluation Metrics

- Adjusted Rand Index (ARI)
- Runtime

### Repository Contents

| File | Description |
|------|-------------|
| thesis10.Rmd | Thesis source |
| thesis10.html | Thesis report |
| sim_study1_poisson_mixture.csv | Simulation results (Poisson mixture) |
| sim_study2_pln_mixture.csv | Simulation results (PLN mixture) |

### Key Findings

- PLN mixtures model overdispersion and dependence effectively.
- Anscombe + Mclust is computationally faster.
- Clustering performance is comparable across methods under the simulation settings.

### Author

Dinesh Kumar Darshnam  
Maynooth University
