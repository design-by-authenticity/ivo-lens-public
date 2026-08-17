# I·V·O Lens

**A domain-independent framework for structural observation, instantiated relation, and structured possibility.**

[Website](https://design-by-authenticity.com/ivo-lens-canonical) · [Zenodo archive](https://doi.org/10.5281/zenodo.20189652) · [Latest archived version](https://doi.org/10.5281/zenodo.21202030)

---

## What this repository is

This is the public research and release layer of the **I·V·O Lens**, developed by **Ivo van der Wal** under **Design by Authenticity**. It is intentionally separate from the private canonical development environment.

> The private canonical repository is the source of truth. This public repository is a curated release surface.

## The three operators

The current operator terminology is:

- **O — Structured Possibility:** the structured field of conditions, boundaries, constraints and affordances that determines what can arise, persist, become reachable or remain excluded.
- **V — Instantiated Relation:** a relation that has actually come into existence. It may be inferred from interaction, motion, encounter, duration, continuity, constraint or relational state; current motion is neither necessary nor sufficient for V.
- **I — Situated Selectivity:** the situated distinguishing position or function from which available input is selected, distinguished and appraised. I makes explicit that every distinction is made from somewhere, under particular conditions and limits.

The generative reading is **O → V → I**: from a structured possibility space, relations can become instantiated, within which distinctions, identities or positions become visible.

The analytical or acting reading is **I → V → O**: a situated position enters into or reconstructs relations and thereby reveals or changes the relevant possibility structure.

These are complementary directions through one structure, not competing models.

### Terminology note

Earlier I·V·O material used terms including **Possibility Space**, **Relational Change**, **movement**, and **Observation / Distinction** as primary operator labels. These formulations belong to earlier stages of the framework and should not be used as the current canonical operator definitions.

In particular, **V is not synonymous with movement or change**. Movement and change can provide evidence of an instantiated relation, but a relation can persist without current movement and movement alone is not sufficient to establish the relevant relation.

When older publications conflict with the operator definitions above, the current canonical terminology in this repository takes precedence for the public release layer.

## Current canonical release

- **Analysis specification:** I·V·O Lens Prompt v3.2
- **Specification SHA-256:** `2b2b8721b2948d2df0966523a6afed8f47cec8fea293acefea196e4e841d22a6`
- **Validation protocol:** v3.2.1
- **Validation package:** Baseline 1.0 (`baseline-1.0-2026-07-13`)
- **Execution status:** frozen but not executed

There is no separate Analysis Prompt v3.2.1. The v3.2 specification was included unchanged in the validation package; v3.2.1 identifies study-protocol amendments and the frozen research baseline.

The planned 330-call validation run is paused because external model API execution has a material token cost. No synthetic or reconstructed outputs will be presented as empirical data.

See [Research status](docs/research-status.md) for the distinction between designed, stress-tested, frozen, executed, and validated.

## Repository map

```text
.
├── README.md
├── LICENSE.md
├── CITATION.cff
├── CHANGELOG.md
├── CONTRIBUTING.md
├── docs/
│   ├── core-concepts.md
│   ├── research-status.md
│   └── release-model.md
├── prompts/
│   └── README.md
├── research/
│   └── validation/
│       └── baseline-1.0/
├── examples/
│   └── README.md
└── assets/
    └── README.md
```

## Planned release sequence

1. Canonical Analysis Prompt v3.2 file
2. Canonical research visual
3. Stable Design and Cycle prompts
4. State Logger documentation and public entry point
5. Domain packs for GGZ / lived-experience practice and organizations / MKB
6. Worked cases and pilot findings
7. Validation results when the frozen study has actually been executed

## Use and attribution

Unless a file states otherwise, the conceptual and written material in this repository is licensed under **CC BY-NC-SA 4.0**. Attribution must name:

> Ivo van der Wal — Design by Authenticity — I·V·O Lens

For citation metadata, see [`CITATION.cff`](CITATION.cff).

## Boundaries

The I·V·O Lens is an analytical and design instrument. It is not a diagnostic system, clinical treatment, substitute for professional judgment, or claim to describe reality independently of observation. Outputs remain dependent on input quality, observer position, model behavior, domain knowledge, and explicit assumptions.

## Contact

**Ivo van der Wal**  
Design by Authenticity  
info@design-by-authenticity.org
