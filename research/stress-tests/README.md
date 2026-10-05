# I·V·O Lens stress-test provenance

Status: **Research / Provenance — Not Canonical Prompt Content**

This location documents falsification, stress-test, and regression evidence behind public canonical releases. It complements, but never modifies or replaces, a released canonical prompt.

## Current v4.1 regression record

- [`hessdalen-cross-model-regression-v4.1.md`](hessdalen-cross-model-regression-v4.1.md) documents the controlled Claude / ChatGPT / Gemini regression that informed the v4.1 epistemic-safeguard release.
- The exact frozen RC2 prompt used in that run is preserved under [`../../prompts/development-history/v4.1/`](../../prompts/development-history/v4.1/).

## Provenance expectations

Stress-test dossiers should document:

- which hypotheses or operator boundaries were attacked;
- which counterexamples and domains were used;
- which rules failed or produced overreach;
- which canonical changes followed from those failures;
- which tests the final prompt survived;
- test dates, prompt identities, model/tool versions, inputs, outputs, and interpretation decisions where publication rights permit;
- negative findings, unresolved cases, and limitations.

The v4.0 RC1–RC4 series remains preserved separately under [`../../prompts/development-history/v4.0/`](../../prompts/development-history/v4.0/) as release-candidate provenance.

The historical Baseline 1.0 package remains under [`../validation/baseline-1.0/`](../validation/baseline-1.0/) and is not moved or rewritten. A frozen, stress-tested, or regression-tested prompt is not automatically an empirically validated prompt.

## Experimental I-position research

- [I-position v0.2 preliminary regression archive](i-position-v0.2/README.md) preserves the supplied v0.1/v0.2 protocols, four-case summary, and exact v4.1 baseline. Reported findings are preliminary and non-canonical; raw runs and execution metadata were not supplied. Archived 5 October 2026.

- [Positive-I follow-up finding](i-position-v0.2/IVO_I_POSITION_v0.2_POSITIVE_I_REGRESSION_FINDING.md) records four further constructed cases and a possible false-negative hypothesis, with a proposed targeted A/B comparison; experimental, with no canonical revision adopted.

- [Matched A/B regression summary](i-position-v0.2/IVO_I_POSITION_AB_REGRESSION_SUMMARY_v0.2.md) reports four comparisons of current v4.1 logic with an experimental position/function/autonomy split, and records the source's preliminary decision to formulate experimental v0.3. No canonical change is adopted by this archive.

## Experimental I-position v0.3 protocol

- [v0.3 protocol archive](i-position-v0.3/README.md) preserves the supplied position/function/autonomy experimental protocol with its checksum and testing status. It supersedes v0.2 for experimental testing only; no v0.3 results are recorded by this update, and canonical v4.1 remains unchanged.

- [v0.3 regression summary / decision note](i-position-v0.3/IVO_I_POSITION_v0.3_REGRESSION_SUMMARY_DECISION_NOTE.md) subsequently reports nine near-miss cases and four positive reruns, with an open I-position boundary and a recorded decision toward experimental v0.4. See the archive readme for evidence limitations and differences from earlier records.
