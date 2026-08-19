# Research status

## Current public canonical prompt

- **Title:** I·V·O Lens Prompt v4.0 — Canonical Reference Version
- **Status:** Frozen v4.0 Release
- **Release date:** 19 August 2026
- **Author:** Ivo van der Wal
- **Canonical file:** [`../prompts/ivo-lens-prompt-v4.0.md`](../prompts/ivo-lens-prompt-v4.0.md)
- **SHA-256:** `52ad1a66ee938e1e154651d398b68865c303cf9c6c53d1a624042b7c0353a0dc`

Version 4.0 was refined through systematic falsification and cross-domain stress testing. Its release candidates are preserved as development provenance. Frozen and stress-tested do not mean empirically validated.

## Status labels used in this project

- **Designed** — the instrument or module has been specified.
- **Stress-tested** — it has been applied to difficult or boundary cases to expose overreach and failure modes.
- **Refined** — the specification has changed in response to identified problems.
- **Frozen** — the specification may not be altered during a defined comparison or release period.
- **Executed** — the planned study has actually been run and raw outputs exist.
- **Validated** — empirical results support specific claims under stated conditions.

A frozen protocol or prompt is not automatically a validated protocol or prompt.

## Historical Baseline 1.0

Baseline 1.0 remains a frozen, unexecuted research design tied to:

- Analysis specification: **v3.2**
- Validation Study Protocol: **v3.2.1**
- Frozen package: **Baseline 1.0** (`baseline-1.0-2026-07-13`)

No separate Analysis Prompt v3.2.1 exists. Version v3.2 remains canonical only for reproducing that historical baseline; it is not the current public canonical prompt.

The baseline contains a 100-domain sampling frame, three planned model runs per domain, a 10-domain variance sub-study, activation logging, dependency validation, and explicit falsification criteria. Planned execution volume remains 330 calls.

## Execution status

The Baseline 1.0 study has not been executed because the required external model API usage has a material token cost and no suitable research budget or partner is attached to the run. This repository will not present fabricated, simulated, or reconstructed outputs as empirical study data.

## What can be claimed now

Reasonable current claims:

- v4.0 is a frozen public canonical prompt;
- the framework has a specified operator and analysis architecture;
- systematic cross-domain stress tests exposed identifiable failure modes;
- those failure modes produced concrete v4.0 safeguards;
- the RC series preserves the development path;
- a separate historical validation design is frozen and inspectable.

Claims that are not yet justified:

- that v4.0 is empirically validated across domains;
- that one AI model implements it more reliably than another;
- that the framework improves decisions or outcomes in professional practice;
- that online interest or archive downloads demonstrate effectiveness.

## Research priorities

1. Publish a documented stress-test dossier without rewriting the frozen v4.0 prompt.
2. Preserve hypotheses, counterexamples, failures, resulting changes, negative findings, and limitations.
3. Secure execution funding or a research partner for empirical validation work.
4. Keep future validation packages and prompt releases explicitly version-separated.
5. Publish raw outputs and analysis decisions when execution occurs and rights permit.

## Research integrity rule

The instrument must be capable of producing evidence against itself. A rule or assignment that fails evidence, dependency, remove-and-compare, or cross-domain checks is a candidate for documented revision in a later version, not silent repair in frozen v4.0.
