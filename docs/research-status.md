# Research status

## Status labels used in this project

The I·V·O project separates several states that are often blurred together:

- **Designed** — the instrument or module has been specified.
- **Stress-tested** — it has been applied to difficult or boundary cases to expose overreach and failure modes.
- **Refined** — the specification has changed in response to identified problems.
- **Frozen** — the specification may not be altered during a defined comparison or study period.
- **Executed** — the planned study has actually been run and raw outputs exist.
- **Validated** — empirical results support specific claims under stated conditions.

A frozen protocol is not automatically a validated protocol.

## Canonical version distinction

- Analysis specification: **I·V·O Lens Prompt v3.2**
- Validation Study Protocol: **v3.2.1**
- Frozen package: **Baseline 1.0** (`baseline-1.0-2026-07-13`)

No separate Analysis Prompt v3.2.1 exists. The v3.2 specification was frozen unchanged inside the v3.2.1 validation package.

## Baseline 1.0

The current baseline contains:

- the v3.2 canonical Analysis specification;
- a frozen validation-study protocol at v3.2.1;
- a 100-domain sampling frame;
- three planned model runs per domain;
- a 10-domain, three-repetition within-model variance sub-study;
- machine-readable activation logging;
- dependency validation;
- explicit criteria that can count against modules in the instrument.

Planned execution volume: 300 base calls plus 30 variance calls, 330 total.

## Current blocker

The study has not yet been executed because the required external model API usage has a material token cost and no suitable research budget or partner is currently attached to the run. This repository will not present fabricated, simulated, or plausibly reconstructed model outputs as empirical study data.

## What can be claimed now

Reasonable current claims:

- the framework has a specified operator and module structure;
- it has undergone iterative cross-domain stress testing;
- identifiable failure modes have produced concrete protocol refinements;
- the validation design is frozen and inspectable;
- the public Zenodo record shows continuing access and downloads.

Claims that are not yet justified:

- that the full instrument is empirically validated across domains;
- that one AI model implements it more reliably than another;
- that all modules engage as intended;
- that the framework improves decisions or outcomes in professional practice;
- that observed online interest demonstrates effectiveness.

## Research priorities

1. Secure execution funding or an API/research partner.
2. Run the frozen Baseline 1.0 study without methodological amendments.
3. Publish raw outputs, parsing decisions, matrices, limitations, and negative findings.
4. Compare later instrument versions against the frozen baseline.
5. Run small practice-based pilots separately from the model-behavior validation study.

## Research integrity rule

The instrument must be capable of producing evidence against itself. A module that rarely engages when applicable, fails dependency checks, or generates weak or decorative findings is a candidate for revision or removal, not protection.
