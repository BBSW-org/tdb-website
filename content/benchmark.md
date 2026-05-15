---
title: Benchmark
description: Scope, design principles, and release status for TrialDesignBench.
---

TrialDesignBench focuses on clinical trial design tasks that require agents to reason across medical evidence, statistical tradeoffs, patient safety, feasibility, and protocol documentation.

## What Agents Receive

Each task should provide the materials a human trial designer would need: disease context, target population, candidate interventions, prior evidence, design constraints, and required deliverables.

## What Agents Produce

Agents may be asked to draft protocol components, select design parameters, justify endpoints, identify risks, propose adaptations, or produce machine-checkable artifacts for downstream evaluation.

## Evaluation Signal

The benchmark should combine deterministic checks, rubric-based clinical and statistical review, and structured artifact validation. A task should pass only when the full design is coherent, clinically defensible, and aligned with the stated constraints.

## Release Status

The public benchmark specification, task examples, evaluation harness, and submission process are under development.
