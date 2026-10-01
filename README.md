# I·V·O Lens Prompt v4.1 — Canonical Reference Version

Public source, versioning, provenance, and research repository for the **I·V·O Lens**, developed by **Ivo van der Wal** under **Design by Authenticity**.

[Public introduction and downloads](https://design-by-authenticity.com/ivo-lens) · [Readable canonical web version](https://design-by-authenticity.com/ivo-lens-canonical) · [Zenodo v4.1.0](https://doi.org/10.5281/zenodo.23083767)

## Current canonical release

- **Title:** I·V·O Lens Prompt v4.1 — Canonical Reference Version
- **Status:** Canonical v4.1 Release
- **Version:** 4.1.0
- **Release date:** 1 October 2026
- **Author:** Ivo van der Wal
- **Canonical file:** [`prompts/ivo-lens-prompt-v4.1.md`](prompts/ivo-lens-prompt-v4.1.md)
- **SHA-256:** `a9228051d2b86bddd06c143f1f065e0ac0c9acb6273b3a472deb087e8db8fc7b`
- **Version DOI:** [`10.5281/zenodo.23083767`](https://doi.org/10.5281/zenodo.23083767)
- **All-versions concept DOI:** [`10.5281/zenodo.20189652`](https://doi.org/10.5281/zenodo.20189652)

Version 4.1 retains the canonical O/V/I operator semantics frozen in v4.0 and adds epistemic safeguards developed from reproducible cross-model failure modes. The exact frozen v4.1 RC2 artifact used in the controlled Hessdalen regression is preserved in the published Zenodo v4.1.0 archive for provenance and reproducibility; it is not an alternative canonical prompt.

## Canonical identity

The I·V·O Lens is a domain-independent framework for structural analysis. It reconstructs three analytical functions within an explicitly stated scope:

- **O — Structured Possibility**
- **V — Instantiated Relation**
- **I — Situated Selectivity**

O, V, and I are functional assignments within scope, not ontological classes of entities. The canonical prompt contains the operative definitions, evidence requirements, epistemic safeguards, analysis procedure, output format, and falsifiability conditions.

## What changed in v4.1

Version 4.1 is an **epistemic-safeguard release**, not an operator-semantic revision. It adds or strengthens:

- evidence provenance and shared claim-status vocabulary;
- observation → event → class → membership → mechanism separation;
- unknown-state and negative-claim gating;
- hypothesized-mechanism gating;
- evidential-dependency controls;
- causal-status calibration within V;
- stricter requirements for assigning Situated Selectivity (I);
- claim-level reliability discipline;
- synthesis and intervention constraints.

The changes were derived from reproducible cross-model failures in Project Hessdalen analyses and were regression-tested across Claude, ChatGPT, and Gemini under a controlled no-external-source condition. See [`research/stress-tests/hessdalen-cross-model-regression-v4.1.md`](research/stress-tests/hessdalen-cross-model-regression-v4.1.md).

## Repository structure

```text
.
├── prompts/
│   ├── ivo-lens-prompt-v4.1.md
│   ├── ivo-lens-prompt-v4.1.sha256
│   ├── ivo-lens-prompt-v4.0.md
│   └── development-history/
│       ├── v4.0/
│       └── v4.1/
├── releases/
│   ├── v4.1.0.md
│   ├── v4.1.0-manifest.json
│   ├── v4.0.0.md
│   └── v4.0.0-manifest.json
├── research/
│   ├── stress-tests/
│   └── validation/baseline-1.0/
├── docs/
├── CITATION.cff
├── CHANGELOG.md
└── LICENSE.md
```

- **Current canonical prompt:** [`prompts/ivo-lens-prompt-v4.1.md`](prompts/ivo-lens-prompt-v4.1.md)
- **v4.1 provenance note:** [`prompts/development-history/v4.1/README.md`](prompts/development-history/v4.1/README.md)
- **Exact frozen RC2 artifact:** preserved in the [Zenodo v4.1.0 archive](https://doi.org/10.5281/zenodo.23083767)
- **v4.1 release notes:** [`releases/v4.1.0.md`](releases/v4.1.0.md)
- **Hessdalen regression note:** [`research/stress-tests/hessdalen-cross-model-regression-v4.1.md`](research/stress-tests/hessdalen-cross-model-regression-v4.1.md)
- **Previous frozen canonical v4.0:** [`prompts/ivo-lens-prompt-v4.0.md`](prompts/ivo-lens-prompt-v4.0.md)
- **Research status:** [`docs/research-status.md`](docs/research-status.md)

## Versioning and provenance

The public prompt line preserves released canonical prompts and the development artifacts needed to reconstruct why they changed.

- **v4.0.0** remains the frozen historical predecessor.
- **v4.1.0** is the current canonical release.
- **v4.1 RC2** is preserved as the exact regression artifact in the Zenodo v4.1.0 archive from which the final v4.1 release was promoted.

Released tags are treated as immutable. Corrections require a new patch release; backwards-compatible canonical development uses a minor release; a fundamentally new architecture uses a new major release.

## Website and archival roles

- [`/ivo-lens`](https://design-by-authenticity.com/ivo-lens) — accessible public introduction and downloads
- [`/ivo-lens-canonical`](https://design-by-authenticity.com/ivo-lens-canonical) — readable web representation of the current canonical prompt
- [GitHub](https://github.com/design-by-authenticity/ivo-lens-public) — source, versioning, provenance, and research
- [Zenodo v4.1.0](https://doi.org/10.5281/zenodo.23083767) — permanent archive and version-specific DOI

The all-versions concept DOI is [`10.5281/zenodo.20189652`](https://doi.org/10.5281/zenodo.20189652), which resolves to the latest version in this public version line. Use the version-specific DOI when citing v4.1.0.

## Citation

To cite the current release:

> Ivo van der Wal (2026). *I·V·O Lens Prompt v4.1 — Canonical Reference Version*. Design by Authenticity. Version 4.1.0. https://doi.org/10.5281/zenodo.23083767

Machine-readable metadata is available in [`CITATION.cff`](CITATION.cff).

## License and commercial use

Unless a file states otherwise, the material in this repository is licensed under **CC BY-NC-SA 4.0**. Attribution must name:

> Ivo van der Wal — Design by Authenticity — I·V·O Lens

Sharing and adaptation are permitted under the license for non-commercial use with attribution and ShareAlike. Commercial deployment, paid training, proprietary-product integration, organization-wide implementation, resale, and professional domain packs require a separate agreement with Design by Authenticity. See [`LICENSE.md`](LICENSE.md).

## Boundaries

The I·V·O Lens is an analytical and design instrument. It is not a diagnostic system, clinical treatment, substitute for professional judgment, or claim to describe reality independently of observation. A frozen, stress-tested, or regression-tested prompt is not automatically empirically validated; see [`docs/research-status.md`](docs/research-status.md).

## Contact

**Ivo van der Wal**  
Design by Authenticity  
info@design-by-authenticity.org
