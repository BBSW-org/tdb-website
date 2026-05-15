---
title: Methodology
description: How TrialDesignBench tasks and evaluations are designed.
---

TrialDesignBench is built around clinically meaningful, reproducible evaluations.

## Task Construction

Tasks should be grounded in realistic trial design scenarios and reviewed by domain experts in clinical research, biostatistics, or regulatory science.

## Evaluation

Each task should be decomposed into checkpoints that capture the critical parts of the workflow: correct interpretation of evidence, appropriate endpoint selection, defensible statistical assumptions, safety-aware eligibility criteria, and coherent documentation.

## Reproducibility

Evaluation runs should use versioned task inputs, pinned harness dependencies, and recorded trajectories so results can be audited and compared over time.

## Safety

High-stakes clinical trial design requires conservative grading. Unsafe recommendations, unsupported assumptions, missing safeguards, or incoherent protocol elements should prevent a task from passing even when other checkpoints are correct.
