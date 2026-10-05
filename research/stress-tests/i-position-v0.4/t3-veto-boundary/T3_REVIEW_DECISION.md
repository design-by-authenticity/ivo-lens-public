# T3 — nested selection and veto-boundary failure record

Recorded: 5 October 2026. Experimental / non-canonical.

**Reviewed verdict: PASS ON NESTING / FAIL-OR-UNRESOLVED ON VETO BOUNDARY.**

Provenance: the [original supplied analysis](T3_ORIGINAL_ANALYSIS.txt) is preserved unchanged. This note records the user's explicit review and corrections, not a new execution of T3. The original all-PASS conclusion is superseded for this archived review by the verdict above.

## Corrected stage decisions

| Stage | Reviewed I-function status | Review |
|---|---|---|
| Stage 1 ranking | NOT ESTABLISHED | PASS; upstream causal contribution may remain SUPPORTED |
| Stage 2 shortlist | ESTABLISHED | PASS within supplied case; explicit top-k admission/exclusion |
| Stage 3 veto | UNRESOLVED | Boundary failure exposed; downstream exclusion alone does not distinguish thresholding |
| Stage 4 final selection | ESTABLISHED for S4 and baseline S5; NOT ESTABLISHED for S5 after execution disconnect | PASS on scope separation |
| Stage 5 execution | NOT ESTABLISHED | PASS |
| System-level aggregate | NOT REQUIRED | PASS on avoiding redundant aggregation |

The aggregate's NOT REQUIRED label is retained as the user's aggregation decision, not added to v0.4's I-function status vocabulary. Mechanistic implementation remains COMPLETE and I-autonomy NOT ESTABLISHED in the reviewed reconstruction.

## What survives review

The analysis separates ranking, shortlist, final selection, and execution without collapsing their carriers. Stage 1 orders all six projects without itself excluding candidates; Stage 2 retains three and excludes three from downstream processing. The execution-disconnect leaves Stage 4 positive for internal S4 final winner but removes its positive I-function status for S5 execution when fallback takes over. These are reported successes within the supplied case, not general validation.

## Boundary failure

The original Stage 3 justification is:

`project → compliance criterion → PASS/VETO → downstream admission/exclusion`

The same justification can be applied to:

`temperature → threshold → ON/OFF → downstream heating/no heating`

Calling the first admission/exclusion and the second thresholding does not establish a structural discriminator. A thermostat can also be described as admitting or excluding heating. Causal consequence and a gate output are therefore insufficient to justify the original positive Stage 3 assignment while retaining the NM-02 boundary.

**Stage 3 is UNRESOLVED, not disproven.** The failure is the absence of a demonstrated discriminator in the supplied analysis under current v0.4. A possible I-function remains an open question.

## Matrix correction and causal separation

The original function matrix cell **Stage 1 ranking × S1 Ranking = ESTABLISHED** is corrected to **NOT ESTABLISHED**. Producing an ordering is not the same claim as establishing I-function. Stage 1's upstream causal contribution may separately remain SUPPORTED.

The original Stage 3 positive I-function cells for S3/S4 and supported I-function cell for S5 are not accepted by this review: retain UNRESOLVED wherever the veto-versus-threshold distinction is decisive. This does not erase the reported causal effect of the gate on downstream availability. The other original cross-scope cells have not received an independent comprehensive re-evaluation here; use the corrected stage decisions above rather than treat the original mixed matrix as an approved I-function matrix.

FC-1 selectivity inflation can no longer be recorded as an unqualified PASS for the whole case. Veto inflation is FAIL-OR-UNRESOLVED pending the discriminator test. The original FC-37 through FC-42 labels are supplied analysis-specific extensions, not checks defined in the archived v0.4 protocol (which lists FC-1 through FC-28).

## Decision and next action

Register the failure before proceeding to T4. Prepare [T3B — veto versus threshold discriminator](T3B_VETO_VERSUS_THRESHOLD_TEST_DESIGN.md). Do not revise v0.4 semantics to force a preferred result. Any proposed semantic repair must receive a separate version and regression review.

Open question: **When does criterion-driven admission/exclusion constitute an evidenced selective function, and when is it a deterministic gate/threshold represented in V?**

The source analysis references T1, but no T1 source record or exact original T3 input was supplied with this submission. Run date, model/settings, and raw execution history are not available here. This review does not establish the result of T3B or cross-model reproducibility. Canonical v4.1 remains unchanged.
