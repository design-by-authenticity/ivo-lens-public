# T4 decision note / v0.4 amendment proposal

Recorded: 5 October 2026. Status: EXPERIMENTAL / NON-CANONICAL.
Source: [supplied T4 analysis](T4_ORIGINAL_ANALYSIS.txt), preserved unchanged, and the user's explicit accompanying review. This note records that review and its amendment proposal; it is not a new test execution or an amended protocol.

## Formal result

**T4 RESULT: POSITIVE I-POSITION HYPOTHESIS NOT ESTABLISHED**

**Regression discipline: PASS**

**Independent I-position dimension: UNRESOLVED / unsupported by current tests**

The discipline verdict recognises that the test did not manufacture a positive position result. It does not turn the unresolved position boundary or the source's open FC-21 position-suppression assessment into a clean semantic PASS.

## Decisive finding

The supplied cases test location, asymmetric access, persistence, memory, history-conditioned baselines, relocation, and identical current inputs with different retained histories. Once history, memory states, baselines, relocation trajectories, and update rules are included in the full O/V reconstruction, the reported differences remain representable without an independent I-position assignment.

Case B retains every relevant distinction when the position label is removed but the histories are preserved. Cases C and D are stronger candidates: equal current inputs, and in D equal current location and connectivity, can coexist with different registered results. However, retained history, state, and update mechanism still reconstruct those differences. Defeating a current-connectivity-only account does not defeat a full O/V account.

Retain the following negative decision rule as the reviewed experimental finding:

> If full O/V reconstruction preserves every analytically relevant distinction attributed to position, an independent I-position assignment is not warranted.

This is a rule against an unsupported positive assignment, not proof that an independent position dimension could never be evidenced. It must not be weakened to a requirement that a candidate merely exceed current connectivity while omitting history from O/V.

## Recorded classifications

| Supplied case | I-position | I-function | Implementation | I-autonomy |
|---|---|---|---|---|
| A — instantaneous sensor | NOT ESTABLISHED | NOT ESTABLISHED | COMPLETE | NOT ESTABLISHED |
| B — persistent logger | NOT ESTABLISHED | NOT ESTABLISHED | COMPLETE | NOT ESTABLISHED |
| C — position-relative baseline | UNRESOLVED | NOT ESTABLISHED | COMPLETE | NOT ESTABLISHED |
| D — relocated history-bearing node | UNRESOLVED | NOT ESTABLISHED | COMPLETE | NOT ESTABLISHED |
| E — asymmetric access only | NOT ESTABLISHED | NOT ESTABLISHED | COMPLETE | NOT ESTABLISHED |

The user's reviewed historical corrections are:

- **NM-07: POSITION UNRESOLVED**, replacing its earlier provisional POSITION ESTABLISHED in the research interpretation.
- **NM-07B: POSITION NOT ESTABLISHED**.

Earlier source reports remain intact. These are retrospective reviewed classifications, not claims that original NM-07/NM-07B inputs were independently rerun in this archival update.

## Proposed architectural amendment

**Demote I-position from independent experimental dimension to an unresolved research hypothesis.**

For a possible separately versioned v0.4.1, retain three working analytical dimensions:

1. I-function;
2. mechanistic implementation;
3. I-autonomy.

Retain the following as mandatory situated-analysis elements:

- scope;
- carrier;
- access structure;
- history;
- outside view.

Do not discard positional information. Record it through these elements and the O/V reconstruction, without a routine separate positive I-position classification. Reopening the independent-position hypothesis would require a case whose claimed additional distinction survives the full-O/V-exhaustion challenge, including history and internal state. A useful label or descriptive compression alone is not enough.

This proposal changes the experimental architecture, not merely the wording of an open issue. It should be recorded before T5 rather than silently continuing with four presumed independent dimensions. The archived v0.4 draft is not edited by this note; no v0.4.1 protocol is created or adopted here.

## Asymmetry with I-function

The earlier qualified T3B finding supports an evidenced functional classification even when its implementation is fully reconstructed. T4 has not demonstrated an equivalent independent analytical contribution for position. There is no requirement that the two dimensions succeed symmetrically.

The working interpretation is that positionality may remain analytically important without needing separate operator status. The three retained dimensions remain experimental: this small supplied series does not establish universal robustness or independence across all domains. T3B's sufficient-not-necessary qualification also remains in force.

## Evidence limits and provenance

The submitted T4 report covers Cases A–E, including baselines and relocation. It is not a complete execution record of the earlier archived [P1–P6 T4 design](T4_TEST_DESIGN.md). Do not mark every control from that design completed on the basis of this submission.

Exact original case prompts, model/version/settings, execution dates, and complete run histories were not supplied. This publication does not independently verify cross-model reproducibility or rerun the tests. Source-specific FC-49 through FC-54 are not additions to the archived v0.4 protocol's FC-1 through FC-28.

## Decision boundary

Record the result and amendment proposal on GitHub only. T5 is not started. No amended protocol, additional test execution, canonical promotion, or v4.1 revision is performed. Canonical v4.1 and the archived v0.4 draft remain unchanged.
