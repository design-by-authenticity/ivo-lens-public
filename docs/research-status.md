# Research status

## Current public canonical prompt

- **Title:** I·V·O Lens Prompt v4.1 — Canonical Reference Version
- **Status:** Canonical v4.1 Release
- **Version:** 4.1.0
- **Release date:** 1 October 2026
- **Author:** Ivo van der Wal
- **Canonical file:** [`../prompts/ivo-lens-prompt-v4.1.md`](../prompts/ivo-lens-prompt-v4.1.md)
- **SHA-256:** `a9228051d2b86bddd06c143f1f065e0ac0c9acb6273b3a472deb087e8db8fc7b`
- **DOI:** [`10.5281/zenodo.23083767`](https://doi.org/10.5281/zenodo.23083767)

Version 4.1 retains the operator semantics frozen in v4.0 and adds epistemic safeguards derived from reproducible cross-model failure modes. The frozen v4.1 RC2 candidate was run across Claude, ChatGPT, and Gemini in a controlled Project Hessdalen regression. The targeted failure modes were substantially reduced without collapsing the analyses into blanket uncertainty. This supports the tested safeguards under the tested conditions; it does not establish universal robustness or empirical validation.

## Status labels used in this project

- **Designed** — the instrument or module has been specified.
- **Stress-tested** — it has been applied to difficult or boundary cases to expose overreach and failure modes.
- **Regression-tested** — a frozen candidate has been rerun against previously observed failure modes under a controlled comparison condition.
- **Refined** — the specification has changed in response to identified problems.
- **Frozen** — the specification may not be altered during a defined comparison or release period.
- **Executed** — the planned study has actually been run and raw outputs exist.
- **Validated** — empirical results support specific claims under stated conditions.

A frozen, stress-tested, or regression-tested prompt is not automatically an empirically validated prompt.

## Current evidence base

What is currently supported by the public record:

- v4.1.0 is the current public canonical prompt;
- the O/V/I operator semantics remain unchanged from frozen v4.0;
- the framework has explicit evidence provenance, claim-status, dependency, causal-status, and negative-claim safeguards;
- the Hessdalen cross-model regression documents reproducible failure modes and their behavior under v4.1 RC2;
- Claude and ChatGPT passed the controlled regression; Gemini passed with residual execution issues;
- the remaining observed variance centered mainly on epistemic ambiguity versus structural openness in human classification;
- the exact tested RC2 artifact is preserved separately from the canonical release.

Claims not established by this record:

- universal validity or completeness of the Lens;
- empirical superiority over competing frameworks;
- reliable benefit to professional decisions or outcomes;
- immunity to model bias or execution error;
- general cross-model equivalence beyond the tested cases and conditions.

## Historical Baseline 1.0

Baseline 1.0 remains a frozen, unexecuted research design tied to:

- Analysis specification: **v3.2**
- Validation Study Protocol: **v3.2.1**
- Frozen package: **Baseline 1.0** (`baseline-1.0-2026-07-13`)

No separate Analysis Prompt v3.2.1 exists. Version v3.2 remains canonical only for reproducing that historical baseline; it is not the current public canonical prompt.

The baseline contains a 100-domain sampling frame, three planned model runs per domain, a 10-domain variance sub-study, activation logging, dependency validation, and explicit falsification criteria. Planned execution volume remains 330 calls.

## Execution status

The Baseline 1.0 study has not been executed. The Hessdalen regression is a separate executed regression test targeting specific observed failure modes; it is not a substitute for the broader Baseline 1.0 empirical validation design.

## Research priorities

1. Extend frozen-case regression testing beyond Hessdalen without rewriting the released v4.1 prompt.
2. Preserve hypotheses, counterexamples, failures, negative findings, and limitations alongside successful runs.
3. Secure execution funding or a research partner for broader empirical validation work.
4. Keep validation packages and prompt releases explicitly version-separated.
5. Publish raw outputs and analysis decisions when rights and privacy permit.

## Research integrity rule

The instrument must be capable of producing evidence against itself. A rule or assignment that fails evidence, dependency, remove-and-compare, cross-domain, or regression checks is a candidate for documented revision in a later version, not silent repair in a released prompt.
