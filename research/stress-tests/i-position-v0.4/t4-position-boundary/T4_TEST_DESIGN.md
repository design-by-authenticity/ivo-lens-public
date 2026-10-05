# T4 — open I-position boundary

Test design 0.1 — 5 October 2026.
Status: EXPERIMENTAL / NON-CANONICAL / PREPARED, NOT EXECUTED.
Protocol: [unchanged v0.4](../IVO_I_POSITION_PROTOCOL_v0.4_EXPERIMENTAL_DRAFT.md).
Context: [qualified T3B decision](../t3b-qualified-result/T3B_REVIEW_DECISION.md).

## Question

When does persistent, situated access add non-redundant analytical information beyond ordinary O/V connectivity, and when is I-position merely a new label for a sensor, channel, or memory?

T3B's sufficient function discriminator is not a necessary position criterion. No candidate below is granted a position because it stores data, has an observer label, or affects a choice. Do not demand a selective function as a prerequisite for position.

## Shared constructed fixture

A deterministic system reports three events: at tick 1 valve=OPEN, at tick 2 valve=CLOSED, at tick 3 valve=OPEN. A separate fixed controller produces these events and cannot be affected by any observation device. At tick 3 each device is queried about current state and the ordered events at ticks 1 and 2.

Devices only expose records through fixed read operations; they do not rank candidates, choose actions, or control the valve. All hardware, retention, and access rules below are fully specified at this resolution. Keep this fixture fixed across comparisons. These are synthetic test inputs, not observed results.

Primary scope: what event distinctions are available from each declared endpoint at tick 3. Separate scope: influence on valve continuation. Do not substitute epistemic usefulness to an external analyst for evidence that a device carries an I-position.

## Case packets

### P1 — live sensor / port

The endpoint exposes only the latest state. Earlier values are overwritten. At tick 3 it returns OPEN; ticks 1 and 2 are unavailable. Moving the endpoint to an identical live channel changes no accessible distinctions.

### P2 — complete passive history

The endpoint appends each timestamped event and exposes the complete record. At tick 3 it returns current OPEN and history [1:OPEN, 2:CLOSED]. No information is used to alter continuation. Erasing history leaves only the current value; compare the resulting endpoint with P1.

### P3 — inaccessible stored history

The same complete history is stored, but the declared endpoint can read only current state. No query path to the history exists within the endpoint's boundary. An external maintainer can read the storage through a separate physical port. Report endpoint and maintainer-port scopes separately; do not treat stored existence as endpoint access.

### P4 — complementary historical access

Two endpoints share the same complete backing record. Endpoint L can read current state and tick 1 but not tick 2. Endpoint R can read current state and tick 2 but not tick 1. Permissions are fixed lookup masks, not an adaptive decision process. Neither endpoint affects the valve.

Swap the masks while preserving endpoint names, physical wiring, backing data, and read operations. The accessible historical distinctions swap. Remove L: tick 1 becomes unavailable to the remaining endpoint. State whether the full O/V model of masks and read relations already explains this loss; a loss alone must not predetermine I-position.

### P5 — equivalent duplicate

Duplicate L with the same source, mask, record, and query interface. The duplicate exposes exactly the same facts at the same times. Compare one versus two proposed position carriers. Do not multiply positions solely because two devices exist.

### P6 — storage relocation with identical access

Move L's record from local memory to a remote store reached by a lossless channel with identical timing, permissions, content, and reliability. Every possible query answer remains identical. Assess whether changing physical location alone warrants a different position status or carrier.

## Required comparisons

For every case reconstruct two explicit accounts:

1. **O/V account:** include retention state, time, permissions, read paths, and the declared system boundary. Do not weaken this reconstruction to manufacture a position.
2. **O/V plus proposed position:** name the carrier and state exactly what additional distinction the position description supplies.

State whether the claimed gain is an empirical difference, a scope-indexed access distinction, useful explanatory compression, or only a renamed O/V relation. Do not silently equate explanatory compression with evidence of independent structure; if the protocol does not decide which form of gain qualifies, mark the boundary UNRESOLVED.

Use P1/P2 for retention, P2/P3 for access versus mere storage, P4 for complementary situated access, P5 for redundancy, and P6 for implementation/relocation invariance. Do not require inexplicability in O/V as evidence for position; explicitly identify any tension between that requirement and the protocol's non-redundant-gain language.

## Shared execution instruction

Analyse the supplied packet using canonical v4.1 as reference and unchanged experimental v0.4. Declare scope before classification. Separate I-position, I-function, causal contribution to the valve, mechanism, and autonomy. For each candidate position perform remove-and-compare and the strongest ordinary-connectivity challenge, including all stated retention and permission mechanisms. Cite the clause and supplied evidence supporting the status. Do not infer function from memory, or position from the word observer. Report unresolved semantic criteria rather than inventing a rule. Give a revocation condition for every positive claim.

## Output record

| Case/run | Scope/carrier | Accessible history | Outside view | Full O/V account | Claimed positional gain | Position status | Function status | Mechanism | Autonomy | Clause / revocation |
|---|---|---|---|---|---|---|---|---|---|---|

Keep causal influence on the valve separate from information access. Use the protocol's distinction between NOT REQUIRED, NOT ESTABLISHED, and UNRESOLVED; justify each rather than interchange them.

## Execution and assessment

Archive exact inputs/outputs, source artifact checksums, model/version/settings, and run dates. Run packets independently in fresh contexts before a joint comparison. Counterbalance paired order in repeat runs; assess at least two model families where available. Missing repetitions must be reported as a limitation. No run is performed by this design document.

A useful boundary must distinguish materially different access structures without granting every sensor or memory a position, remain invariant under duplicate/relocation controls where distinctions are preserved, and expose any genuinely missing criterion. No positive result is prescribed for P2 or P4. Uniform negative results are not automatically failure; determine whether v0.4 can justify them without contradicting its own position claims. Uniform positive results require scrutiny for sensor/memory inflation.

Report separately: retention discrimination, access discipline, anti-proliferation, representation invariance, scope discipline, and adequacy of the positive-position criterion. Overall outcome may be PASS, FAIL, or UNRESOLVED with scope-specific qualifications. A merely useful vocabulary is not automatically a validated dimension.

If a new semantic criterion is needed, record it as a proposed future amendment and preserve the unmodified-v0.4 result. Do not patch the protocol between cases or present this design as a completed regression.
