---
title: "Computational success and residual-adequacy limits in a small US Bayesian VAR"
excerpt: "A diagnostic case study separating reliable BVAR computation and structural Monte Carlo precision from residual adequacy for substantive inference."
collection: portfolio

header:
  teaser: BVAR-residual-adequacy_Sastre_2026.svg

tags:
  - Econometrics
  - Time Series
  - Bayesian VAR
  - Model Diagnostics

paperurl: "https://github.com/roc-sastre/bvar-residual-adequacy/blob/main/manuscript/research_note.pdf"
githuburl: "https://github.com/roc-sastre/bvar-residual-adequacy"
---

## Overview

### Numerical Reliability Is Not Residual Adequacy

This research note examines why successful computation can still be insufficient for substantive inference in a monthly US Bayesian VAR.

The application separates implementation, convergence, stability and structural Monte Carlo precision from the residual conditions required to interpret model-implied responses.

## Research Goals

- Distinguish reliable model-conditional computation from empirical adequacy for substantive use.
- Document the residual-diagnostic limits of a small US BVAR under prespecified reporting criteria.
- Compare treated and untreated specifications without turning that contrast into a causal pandemic effect.
- Preserve an auditable public record while withholding response estimates that did not clear the interpretation gate.

## Methodology

The analysis uses a monthly Bayesian Vector Autoregression for the United States with industrial-production growth, CPI inflation and the two-year Treasury yield from January 1990 through September 2025.

The empirical strategy combines:

- Six-lag Bayesian VAR specifications
- Pandemic pulse treatment versus an untreated specification
- Constant-covariance and block-scale covariance formulations
- MCMC convergence and stability diagnostics
- Structural Monte Carlo precision checks
- Residual and posterior-predictive adequacy diagnostics
- Reproducibility and preserved-record validation

## Results

Both revised specifications pass the monitored numerical-integrity, convergence, stability and structural Monte Carlo precision criteria.

Residual adequacy does not clear the prespecified reporting gate. Material residual discrepancies and unresolved predictive cutoffs remain binding, so substantive impulse responses and policy conclusions are withheld.

The result is therefore diagnostic rather than substantive: successful computation is documented, but it is not treated as sufficient evidence for economic interpretation.

## Repository

The complete public diagnostic replication package, frozen research note, validation script and provenance documentation are available on GitHub.

A version-specific archive of the public package is preserved on Zenodo under DOI [10.5281/zenodo.23195194](https://doi.org/10.5281/zenodo.23195194).
