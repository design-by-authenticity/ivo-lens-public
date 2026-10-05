# Changelog

All notable public releases of the I·V·O Lens repository are recorded here. This changelog tracks the public release layer and preserves earlier development and validation history.

## [Unreleased]

No unreleased canonical changes.

### Research archive — 2026-10-05

- Archived the [matched A/B regression summary](research/stress-tests/i-position-v0.2/IVO_I_POSITION_AB_REGRESSION_SUMMARY_v0.2.md) with its own checksum manifest. Recorded reported model differences, evidence limitations, and the source's preliminary experimental-v0.3 decision; no canonical change.

- Added the [positive-I regression follow-up](research/stress-tests/i-position-v0.2/IVO_I_POSITION_v0.2_POSITIVE_I_REGRESSION_FINDING.md), preserved byte-for-byte with a separate checksum manifest. Records four reported cases, a possible false-negative hypothesis, and a proposed A/B comparison; no canonical or protocol revision adopted.

- Archived the supplied experimental I-position v0.1/v0.2 protocols and preliminary four-case v0.2 regression summary, with the exact supplied v4.1 baseline and SHA-256 manifest.
- Recorded reported positional gains, zero established I-functions, evidence limitations, and the proposed positive-I test phase. See [the archive](research/stress-tests/i-position-v0.2/README.md).

## [4.1.0] — 2026-10-01

### Epistemic safeguard release

Released **I·V·O Lens Prompt v4.1 — Canonical Reference Version**. Operator semantics remain unchanged from v4.0.

- Added shared evidence provenance and claim-status vocabularies.
- Added observation → event → class → membership → mechanism separation.
- Added explicit negative-claim and unknown-state gating.
- Added hypothesized-mechanism and evidential-dependency gates.
- Added causal-status discipline within V.
- Made claim-level reliability primary and constrained synthesis/intervention strength.
- Preserved the exact frozen v4.1 RC2 artifact used in the controlled Hessdalen cross-model regression.
- Published the version-specific Zenodo DOI `10.5281/zenodo.23083767`.

See `releases/v4.1.0.md` and `research/stress-tests/hessdalen-cross-model-regression-v4.1.md`.

## [4.0.0] — 2026-08-19

### Major canonical revision

Released **I·V·O Lens Prompt v4.0 — Canonical Reference Version** as the sole current public canonical prompt at the time of release.

- **Canonical file:** `prompts/ivo-lens-prompt-v4.0.md`
- **SHA-256:** `52ad1a66ee938e1e154651d398b68865c303cf9c6c53d1a624042b7c0353a0dc`
- **Author:** Ivo van der Wal
- **License:** CC BY-NC-SA 4.0

### Canonical changes since v3.2

- Introduced **function-per-scope** assignments: O, V, and I classify functions or aspects within an explicit scope, not entities as ontological categories.
- Tightened the **I-boundary** around structural openness within the reconstructed scope.
- Added a **positive-evidence requirement** for the selective step itself.
- Added the **ignorance-bucket safeguard**: unexplained behavior is not automatically I.
- Added the **system-boundary evidence rule**: boundary expansion may reveal I only through positive evidence and does not create I.
- Added **remove-and-compare** to reject I-assignments that add no independent analytical consequence.
- Made I-assignments explicitly **provisional and revocable** when stronger scope-matched O/V evidence supports revision.
- Added explicit **unresolved I-candidates** when positive evidence is insufficient.
- Added **cross-scale non-cancellation** so valid scale-indexed reconstructions do not automatically revoke one another.
- Added **domain function ≠ I-function**: words such as selection, choice, recognition, filtering, or function are not evidence by themselves.
- Clarified that **separability and multiple realizability are insufficient evidence for I**.

### Provenance

- Preserved RC1, RC2, RC3, and RC4 under `prompts/development-history/v4.0/` as non-canonical development history.
- Added a dedicated stress-test provenance location under `research/stress-tests/`.
- Retained Analysis v3.2 and Baseline 1.0 as historical research provenance; neither is the current public canonical release.

## [Operator terminology alignment] — 2026-08-17

Aligned the public explanatory layer around Structured Possibility, Instantiated Relation, and Situated Selectivity. This pre-v4.0 alignment remains part of the development history and is superseded where the frozen v4.0 prompt is more specific.

## [Analysis v3.2 and Baseline 1.0 staging] — 2026-07-15

### Added

- Analysis specification identified as I·V·O Lens Prompt v3.2
- Public SHA-256 identity for the frozen specification
- Validation Study Protocol identified separately as v3.2.1
- Baseline 1.0 identifier and research-package structure
- Explicit statement that no separate Analysis Prompt v3.2.1 exists

### Research status

- Baseline 1.0 is frozen but unexecuted
- Planned study remains 300 base runs plus 30 variance runs
- No empirical validation outcome is claimed before execution

## [Baseline 1.0 public shell] — 2026-07-15

### Added

- Public repository architecture
- Framework overview and operator definitions
- Citation metadata
- CC BY-NC-SA 4.0 licensing notice
- Research-status statement
- Public/private release-governance model
- Contribution guidance
- Placeholders for prompts, examples, and visual assets
