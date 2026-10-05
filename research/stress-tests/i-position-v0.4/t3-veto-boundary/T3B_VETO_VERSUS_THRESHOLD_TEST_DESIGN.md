# T3B — veto versus threshold discriminator

Version: test design 0.1. Prepared: 5 October 2026.
Status: EXPERIMENTAL / NON-CANONICAL / NOT EXECUTED.
Protocol under test: [unaltered v0.4 draft](../IVO_I_POSITION_PROTOCOL_v0.4_EXPERIMENTAL_DRAFT.md), with [canonical v4.1](../../../../prompts/ivo-lens-prompt-v4.1.md) retained as the canonical reference.
Trigger: [T3 reviewed boundary failure](T3_REVIEW_DECISION.md).

## Question and falsification target

Can the current protocol distinguish a veto gate from ordinary thresholding on structural evidence, without using admission/exclusion vocabulary, a stored state, or downstream influence alone as the discriminator?

Do not assume that a veto must qualify, that deterministic systems cannot qualify, or that a desired near-miss label is itself evidence. A defensible UNRESOLVED result is preferable to an invented boundary. This test may expose an unresolved defect rather than repair it.

## Fixed case packets

All packets below are constructed test fixtures, not measurements from real systems. Rules and traces are stipulated in full. Analyse each at its declared scope; do not infer motives, hidden controllers, or residual openness. Each packet is deterministic and completely specified at the stated resolution. Independent I-position evidence must still be assessed rather than inferred from an output register or I-function label.

### G1 — heating gate

Input temperature t=18; adjustable threshold h=20. Compute g=1 if t<h, otherwise g=0. Store g in a command register, then set heater H=g one tick later. No other inputs or paths exist. Scope: whether heating is active on the next tick.

Traces with t held at 18: h=20 gives g=1,H=1; h=17 gives g=0,H=0; restoring h=20 gives g=1,H=1. A direct intervention fixing g=0 or g=1 before execution fixes H correspondingly. Bypassing the register and directly implementing the same rule produces identical heating results.

### G2 — single-project compliance gate

One project Q awaits an eligibility gate. Its risk score r=18; adjustable limit c=20. Compute g=1 if r<c, otherwise g=0. Store g as PASS/VETO, then admit Q to the downstream queue A=g one tick later. No comparison with another project, capacity constraint, or other rule exists. Scope: whether Q enters that queue on the next tick; do not switch to ultimate project execution.

Traces with r held at 18: c=20 gives g=1,A=1; c=17 gives g=0,A=0; restoring c=20 gives g=1,A=1. Directly fixing g fixes A. Bypassing the register while implementing the same rule preserves results.

G1 and G2 share the same scalar comparison, register, actuator delay, and interventions. Whether different domain interpretations provide a relevant difference must be justified from supplied structure, not their labels.

### G3 — parallel independent vetoes

Projects P,Q,R have fixed risk scores 12,18,24. Apply the G2 gate independently to each with common c=20. Output admitted set {P,Q}; c=17 gives {P}; restoring c=20 gives {P,Q}. Store the complete admission vector before queue update. There is no capacity limit or comparison across projects. Changing Q's score does not alter P's or R's gate result. Scope: membership of the admitted set.

Compare with three independent heating gates with temperatures 12,18,24 and the same common threshold and vector of outputs. Merely presenting repeated gates as a candidate set does not add an interaction between them.

### G4 — capacity-constrained allocation

Projects P,Q,R are all eligible for execution, but only two can receive resources this cycle. Fixed scores are P=9,Q=7,R=5. A deterministic top-2 rule, with alphabetical tie-break, records the selected set before execution. Only members of that set are executed. Baseline selects and executes {P,Q}. Change only R's score to 8: select and execute {P,R}. Restore R=5: {P,Q}. Change capacity to 3: {P,Q,R}.

Scope: which projects execute this cycle. Record that Q's own score is unchanged when R displaces Q. This is a candidate structural contrast with independent gates, not a pre-approved sufficient condition or a proposed universal definition of I-function.

Implement the same allocation in two ways: (a) sorting then top-2 membership; (b) computing each project's rank by pairwise comparisons then admitting rank<=2. Both implement the same tie-break, membership, and execution mapping. Classifications must not depend solely on whether the implementation is called selection or thresholding.

### G5 — nested veto plus final choice

Use G3 eligibility first. Among admitted projects select the highest benefit: P=9,Q=7,R=5, alphabetical tie-break; record winner W, then execute W. If none is admitted, execute nothing. Baseline c=20 gives admitted {P,Q}, W=P, execution=P. Intervene only on P's gate, forcing veto: admitted {Q}, W=Q, execution=Q. Restore P's gate: execution=P.

Analyse separately S-admission (gate output membership), S-winner (recorded winner), and S-execution (executed project). Do not transfer a positive final-choice status back to the veto automatically.

Disconnect variant: keep the admission and winner computation, but execution always uses external fallback R. Under the same gate intervention W changes P→Q while execution remains R. Report each scope separately; the fallback must not be used to deny an internal effect that remains evidenced.

## Paired representation controls

For G1–G3 make a second presentation that changes only terminology: ON/OFF ↔ PASS/VETO, activation ↔ admission, sensor value ↔ criterion value. Keep the numeric rules, available states, scopes, and interventions identical. Also compare explicit register versus an equivalent implementation without an added register. A register may change observability; do not assume it creates a selective function.

For G4 retain the sorting and rank-threshold implementations as equivalent representations of the same allocation. For G5 retain separate stage and system scopes, both with and without execution disconnect. Record any changed classification and the exact factual difference said to warrant it.

## Execution procedure

1. Record the exact v4.1/v0.4 artifacts and checksums, this design's checksum, model/version, settings, date, and complete prompt/output. Do not edit semantic rules during the batch.
2. Run each packet independently in a fresh context with the same protocol texts and the instruction below. Do not include the T3 verdict, desired labels, or this design's candidate-discriminator commentary in the first-pass case prompt.
3. Run representation pairs in separate fresh contexts; record case order. Then supply the paired outputs for a consistency audit. Keep original outputs intact.
4. Where feasible repeat across at least two model families and two fresh runs per packet/presentation. If not done, explicitly limit reproducibility claims. These are planned repetitions, not completed runs.
5. Any semantic repair belongs in a separately versioned candidate. Keep its results separate from current-v0.4 results; rerun the same packets and the original NM-01/NM-02 and positive-case inputs when available. These synthetic packets are not substitutes for unavailable original inputs.

### Shared first-pass instruction

Analyse the supplied constructed case under the attached experimental v0.4 protocol. Declare scope and available alternatives; reconstruct O and V; assess position, function, implementation, and autonomy separately. Keep causal contribution distinct from I-function status. Cite the exact protocol clause and supplied evidence for each positive claim. State whether the protocol leaves a decisive boundary unresolved. Include revocation conditions. Do not assume a case's name establishes its classification. Do not infer unprovided facts.

## Required comparison record

| Packet / representation / run | Scope | Carrier / position status | I-function | Causal contribution | Implementation | Autonomy | Exact clause and evidence | Boundary unresolved? |
|---|---|---|---|---|---|---|---|---|

Separately answer:

- Does independent scalar gating differ structurally from candidate-relative allocation, and does the existing protocol actually encode that distinction?
- Does increasing the number of independent gates alter anything beyond repetition?
- Do logging, terminology, or downstream placement alone change the I-function result?
- Does a candidate distinction survive the equivalent rank-threshold implementation of G4?
- Can the veto and final-selection stages remain separate in G5 without granting the veto the final selector's evidence?
- Does disconnect remove only the effect on execution while preserving appropriately scoped internal effects?

## Decision criteria

**Boundary supported under current v0.4:** an explicit, evidence-grounded discriminator already supported by the protocol survives the paired representations, differentiates ordinary gating from any positively assigned function without relabelling, and preserves scope discipline. Record limits; do not generalise from this small suite.

**Boundary unresolved:** no justified distinction is found, or a proposed distinction requires additional semantics not present in v0.4. Keep T3 Stage 3 UNRESOLVED. A plausible new criterion is a proposal, not a passed regression.

**Boundary failure:** positive I-function assignments arise merely from renamed gating, logging, or downstream consequences, or equivalent representations receive incompatible statuses without a supported reason. Also record if a putative repair suppresses evidenced allocation solely because it has a deterministic or threshold-based implementation.

Assess nesting/scope and veto discrimination separately. Do not compress mixed outcomes into a clean PASS. Record the outcome even if all gate cases classify alike; explain what that means for the existing NM-02 boundary and do not silently redefine it.

T4 remains deferred for this work. This file specifies T3B only; no T3B execution, semantic amendment, or canonical change is implied by publication.
