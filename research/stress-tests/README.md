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
