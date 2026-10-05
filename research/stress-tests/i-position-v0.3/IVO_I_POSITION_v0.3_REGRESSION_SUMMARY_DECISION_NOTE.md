# I·V·O I-POSITION / I-FUNCTION / I-AUTONOMY
## v0.3 Regression Summary / Decision Note

**Status:** EXPERIMENTAL — NON-CANONICAL  
**Protocol under test:** I-position protocol v0.3  
**Canonical baseline:** I·V·O Lens v4.1 (frozen)  
**Purpose:** regression evaluation and revision decision support  
**Decision level:** experimental semantics only; no canonical change is made by this note

---

# 1. Purpose of this note

This note consolidates the v0.3 regression programme performed after the positive-I failure identified under the v4.1 semantics.

The central question was:

> Can functional selection be distinguished from structural underdetermination without weakening O/V, inflating I, or treating unexplained behaviour as evidence for I?

v0.3 introduced an experimental separation between:

- **I-position** — a situated analytical position that adds non-redundant information about access, distinction, visibility, relevance, exclusion, registration, or viewpoint;
- **I-function** — a positively evidenced selective function that contributes to which relevant continuation becomes realised;
- **I-autonomy** — residual structural openness after the strongest adequate O/V reconstruction.

Mechanistic implementation was treated as a separate dimension:

- **COMPLETE**
- **PARTIAL**
- **UNRESOLVED**

The purpose of the regression programme was not to confirm v0.3, but to try to break it.

---

# 2. Background: the v4.1 positive-I problem

Under canonical v4.1, I requires both:

1. positive evidence for a selective contribution; and
2. structural openness remaining after O/V reconstruction.

This protects the Lens against the inference:

> unexplained → I

but creates a potential failure mode.

In well-instrumented deterministic cases, stronger evidence for how selection occurs improves the O/V reconstruction. Once the mechanism becomes complete, structural openness disappears.

The resulting pattern was:

> better evidence for selection  
> → better mechanistic reconstruction  
> → less structural openness  
> → I-function disappears

This creates a possible false negative:

> the better a selective function is understood, the less eligible it becomes to count as I.

v0.3 therefore tested whether three analytically distinct questions had been conflated:

1. **Where is the relevant situated position?**
2. **Is there a positively evidenced selective function?**
3. **Does structural openness remain after strongest O/V reconstruction?**

---

# 3. Experimental v0.3 hypothesis

The v0.3 hypothesis was:

> Functional selection and structural underdetermination are separable analytical claims.

Under this proposal:

### I-position

asks whether a situated carrier adds analytically relevant information not reducible to ordinary O/V connectivity alone.

### I-function

asks whether there is positive evidence that:

- multiple relevant alternatives are available;
- those alternatives are functionally distinguished rather than merely physically different;
- a selective consequence occurs;
- a selection state or selective event is independently evidenced;
- that selection contributes to which relevant continuation becomes realised.

### I-autonomy

asks whether, after the strongest adequate O/V reconstruction:

> more than one continuation remains structurally open at the relevant transition.

This allows, in principle:

- function without autonomy;
- autonomy without function;
- position without function;
- function with complete mechanistic implementation;
- function with partial implementation and unresolved autonomy.

---

# 4. Regression design

The programme used two complementary test classes.

## 4.1 Near-miss / false-positive suite

These cases were designed to resemble selection without necessarily containing a function that should count as I.

The suite tested:

- filtering;
- thresholding;
- mapping;
- stochastic branching;
- physical bifurcation;
- sorting/ranking;
- passive information access and memory;
- ordinary sensor/channel access;
- epiphenomenal internal selection.

The purpose was to detect I-inflation.

## 4.2 Positive regression suite

Four previously positive cases were rerun after the near-miss boundaries had been established.

The purpose was to detect the opposite failure:

> whether anti-inflation safeguards now suppress genuine positive-I cases.

---

# 5. Near-miss results

| Test | Core structure | I-position | I-function | Mechanistic implementation | I-autonomy | Decision |
|---|---|---|---|---|---|---|
| NM-01 | passive physical filter | NOT REQUIRED | NOT ESTABLISHED | COMPLETE | NOT ESTABLISHED | PASS |
| NM-02 | deterministic thermostat | NOT REQUIRED | NOT ESTABLISHED | COMPLETE | NOT ESTABLISHED | PASS |
| NM-03 | fixed lookup table | NOT REQUIRED | NOT ESTABLISHED | COMPLETE | NOT ESTABLISHED | PASS |
| NM-04 | stochastic RNG | NOT REQUIRED | NOT ESTABLISHED | COMPLETE within model | SUPPORTED | PASS |
| NM-05 | physical bifurcation | NOT REQUIRED | NOT ESTABLISHED | COMPLETE within model | UNRESOLVED | PASS |
| NM-06 | comparison + ranking | NOT REQUIRED | NOT ESTABLISHED | COMPLETE | NOT ESTABLISHED | PASS |
| NM-07 | passive register with retained history | ESTABLISHED | NOT ESTABLISHED | COMPLETE | NOT ESTABLISHED | PROVISIONAL PASS |
| NM-07B | passive sensor / communication port | NOT ESTABLISHED | NOT ESTABLISHED | COMPLETE | NOT ESTABLISHED | PASS |
| NM-08 | epiphenomenal committee selection | ESTABLISHED | scope-dependent | COMPLETE | NOT ESTABLISHED | PASS |

---

# 6. Near-miss findings

## 6.1 Physical exclusion is not functional selection

NM-01 showed that:

> some possibilities pass while others do not

is insufficient for I-function.

A direct physical relation:

property  
→ interaction  
→ passage/blockage

remains fully describable in O/V.

**Boundary established:**

> exclusion-by-physics ≠ functional selection

## 6.2 Thresholding is not functional selection

NM-02 added sensing, comparison, feedback, and switching.

The thermostat nevertheless remained:

temperature + threshold + rule  
→ unique output

The comparison itself was the transition.

There was no separately evidenced selection state.

**Boundary established:**

> sensing + comparison + thresholding + switching ≠ I-function

## 6.3 Mapping is not selection

NM-03 showed that symbolic or informational processing does not automatically establish I.

A lookup structure:

input + mapping  
→ one output

does not become a selectively functioning system merely because many mappings or possible outputs exist across cases.

**Boundary established:**

> fixed correspondence ≠ selection

## 6.4 Stochastic realisation is not functional selection

NM-04 produced the first important dissociation.

The RNG contained:

- multiple open outcomes within the stated stochastic model;
- one realised outcome;
- no evaluation;
- no ranking;
- no selective trace before realisation.

Result:

- **I-function NOT ESTABLISHED**
- **I-autonomy SUPPORTED**

This demonstrates that:

> structural openness does not imply functional selection.

It also supports the independence of I-function and I-autonomy.

## 6.5 Physical branching does not establish I-function

NM-05 tested bifurcation without an explicit selector.

A branch became realised through dynamical evolution, but no separate selective carrier was evidenced.

The case also distinguished:

- sensitivity to initial conditions;
- practical unpredictability;
- structural underdetermination.

Result:

- **I-function NOT ESTABLISHED**
- **I-autonomy UNRESOLVED**

because the source did not establish whether the branch remained structurally open after complete microstate specification.

**Boundary established:**

> branching ≠ selection  
> unknown microdynamics ≠ autonomy

## 6.6 Comparison and ranking are insufficient

NM-06 was deliberately stronger than the earlier near misses.

The system explicitly:

- compared alternatives;
- ranked them;
- changed ranking under criterion intervention.

But all candidates remained in the output.

Result:

- **I-function NOT ESTABLISHED**

The decisive missing feature was a selective consequence for continuation.

**Boundary established:**

> comparison + ranking ≠ functional selection

unless the ranking contributes to which continuation is actually realised.

---

# 7. The I-position boundary

NM-07 exposed the main unresolved pressure point in the first v0.3 draft.

A passive register:

- received realised events;
- encoded them;
- retained historical information;
- had asymmetrical access to realised versus non-realised states;
- had no selective influence on continuation.

The result was:

- **I-position ESTABLISHED**
- **I-function NOT ESTABLISHED**

This was useful because it demonstrated position/function separation, but it raised a possible inflation problem:

> if asymmetric access alone establishes I-position, then almost every sensor, port, buffer, endpoint, and signal-bearing component might qualify.

NM-07B was added specifically to test that risk.

A passive sensor and communication port had asymmetric access, but that access was fully described by:

source  
→ coupling  
→ signal

No additional explanatory gain remained after V reconstruction.

Result:

- **I-position NOT ESTABLISHED**
- **I-function NOT ESTABLISHED**

NM-07B therefore supports a stronger boundary:

> asymmetric access alone is insufficient for I-position.

The emerging criterion is:

> I-position requires analytical gain beyond ordinary V-connectivity.

NM-07 remains a provisional positive position case because it adds retained history and a persistent information structure. However, this does **not** establish that memory alone is sufficient for I-position.

This boundary remains suitable for further testing.

---

# 8. Causal contribution to continuation

NM-08 tested the strongest selection-like false positive.

The committee contained:

- multiple alternatives;
- evaluation;
- weighting;
- ranking;
- voting;
- a winner state;
- a pre-execution selection trace.

However, the actual project executed was determined entirely by an external rule.

Changing the committee decision did not change execution.

Changing the external rule did.

For the primary scope, actual project execution:

- **I-function NOT ESTABLISHED**

For the narrower scope, registered internal committee choice:

- **I-function ESTABLISHED**

This yields a major v0.3 boundary condition:

> A selection trace can establish that an internal selection event occurred, but I-function relative to a given continuation requires evidence that the selection contributes to which continuation is realised.

This also establishes that I-function is scope-sensitive.

A selection may be functionally real at one scope and epiphenomenal at another.

---

# 9. Positive regression reruns

After the near-miss suite, the four positive cases were rerun against the stricter discrimination criteria.

| Case | I-position | I-function | Mechanistic implementation | I-autonomy | Result |
|---|---|---|---|---|---|
| AB-01 deterministic algorithm | ESTABLISHED | ESTABLISHED | COMPLETE | NOT ESTABLISHED | PASS |
| AB-02 autonomous energy controller | ESTABLISHED | ESTABLISHED | COMPLETE | NOT ESTABLISHED | PASS |
| AB-03 human route choice | ESTABLISHED | ESTABLISHED | PARTIAL | UNRESOLVED | PASS with correction |
| AB-04 organisational project selection | ESTABLISHED | ESTABLISHED | COMPLETE | NOT ESTABLISHED | PASS |

---

# 10. Positive-case findings

## 10.1 AB-01 — deterministic algorithm

The algorithm contains:

multiple alternatives  
→ explicit comparison  
→ criterion-dependent scoring  
→ ranking  
→ selection state  
→ execution of selected candidate

Intervention on selection parameters changes the selected candidate.

The case remains fully mechanistically reconstructable.

Result:

- **I-function ESTABLISHED**
- **Mechanistic implementation COMPLETE**
- **I-autonomy NOT ESTABLISHED**

This directly supports:

> mechanistic completeness does not eliminate an evidenced selective function.

## 10.2 AB-02 — autonomous energy controller

The controller contains:

multiple available sources  
→ scoring  
→ weighting  
→ explicit selection  
→ command register  
→ relay action  
→ realised source

Changing priority weights changes both the selection state and the realised source.

Result:

- **I-function ESTABLISHED**
- **Mechanistic implementation COMPLETE**
- **I-autonomy NOT ESTABLISHED**

The case survives NM-02, NM-06, and especially NM-08 because the selection state has a causal contribution to the realised continuation.

## 10.3 AB-03 — human route choice

The human route-choice case contains:

multiple simultaneously available routes  
→ comparison  
→ criterion-sensitive ranking  
→ selection  
→ realised route

Intervention on criterion weight changes ranking and chosen route.

This supports:

- **I-position ESTABLISHED**
- **I-function ESTABLISHED**

However, the available evidence does not warrant a complete mechanistic reconstruction of the selection process.

Therefore:

- **Mechanistic implementation PARTIAL**
- **I-autonomy UNRESOLVED**

This is an important safeguard.

The case does not infer autonomy from incomplete mechanism, but it also does not infer absence of autonomy from incomplete mechanism.

## 10.4 AB-04 — organisational project selection

The committee evaluates multiple admissible projects, ranks them, selects a subset, and the selected projects are actually executed while the non-selected projects are not.

Changing criterion weights changes:

ranking  
→ selected projects  
→ realised organisational continuation

Result:

- **I-position ESTABLISHED**
- **I-function ESTABLISHED**
- **Mechanistic implementation COMPLETE**
- **I-autonomy NOT ESTABLISHED**

This case survives the NM-08 comparison because committee selection is not epiphenomenal: it contributes to execution.

---

# 11. Cross-case result

The regression programme now contains empirically distinct combinations.

## Pattern A — no function, no autonomy

Examples:

- passive filter;
- thermostat;
- lookup table;
- sorting algorithm.

## Pattern B — no function, autonomy supported

Example:

- stochastic RNG.

## Pattern C — no function, autonomy unresolved

Example:

- physical bifurcation.

## Pattern D — position without function

Example:

- passive historical register, provisionally.

## Pattern E — function established, complete mechanism, no autonomy

Examples:

- deterministic algorithm;
- autonomous energy controller;
- formal organisational selection.

## Pattern F — function established, partial mechanism, autonomy unresolved

Example:

- human route choice.

## Pattern G — selection event at one scope, no function at another scope

Example:

- epiphenomenal committee in NM-08.

These combinations are not cosmetic relabellings.

They show that the three experimental dimensions produce different classifications under different structural conditions.

---

# 12. Main regression finding

The strongest cross-case finding is:

> **Functional selection, mechanistic implementation, and structural underdetermination behave as analytically separable dimensions across the tested cases.**

Specifically:

1. A selective function can be **ESTABLISHED** while its mechanism is **COMPLETE**.
2. A complete mechanism can coexist with **I-autonomy NOT ESTABLISHED** without eliminating the function.
3. Structural openness can be **SUPPORTED** while I-function is **NOT ESTABLISHED**.
4. I-autonomy can remain **UNRESOLVED** where mechanism is incomplete without being inferred from ignorance.
5. An I-position can, at least provisionally, exist without an I-function.
6. An internal selection event can exist without being an I-function for a broader continuation when causal contribution is absent.

This directly addresses the positive-I failure identified under v4.1.

---

# 13. Anti-inflation findings

v0.3 did not classify the following as I-function merely because they superficially resemble selection:

- physical filtering;
- thresholding;
- state switching;
- fixed mapping;
- random outcome generation;
- physical branching;
- comparison;
- ranking;
- passive recording;
- memory alone;
- winner state;
- selection trace without causal consequence.

The suite therefore did not reveal systematic selectivity inflation.

Likewise:

- stochasticity did not automatically become I-function;
- uncertainty did not automatically become I-autonomy;
- sensor access did not automatically become I-position;
- group procedures did not require group-mind claims;
- scope changes were required to be explicit.

---

# 14. Emerging minimal discriminator for I-function

The test programme supports the following provisional discriminator.

An I-function claim becomes materially stronger when all of the following are evidenced:

1. **Multiple relevant alternatives** are available at the relevant stage.
2. Alternatives are **functionally distinguished** rather than merely physically different.
3. A **selective consequence** occurs: admission, exclusion, routing, commitment, prioritisation, or selection of a continuation.
4. The selective state/event is **independently evidenced**, preferably before execution.
5. Intervention on selective parameters changes the selective result.
6. The selective result **contributes to which relevant continuation becomes realised**.
7. The claim remains tied to an explicit scope.
8. The function is not inferred merely from randomness, thresholding, mapping, ranking, recording, or missing knowledge.

This is not yet a canonical definition.

It is the strongest discriminator currently supported by the regression set.

---

# 15. Emerging minimal discriminator for I-position

The regression programme does **not** yet support:

> asymmetric access → I-position

as a sufficient rule.

NM-07B shows that ordinary sensor/channel asymmetry can be completely reducible to V-topology.

The strongest current experimental boundary is:

> **I-position requires non-redundant analytical gain beyond ordinary O/V connectivity.**

Candidate supporting features may include:

- retained history;
- persistent access structure;
- context-sensitive relevance;
- stable exclusion structure;
- scope-specific informational asymmetry with consequences not exhausted by connectivity.

However, these are not yet individually sufficient conditions.

The I-position boundary therefore remains less mature than the I-function boundary.

---

# 16. Emerging minimal discriminator for I-autonomy

The current tests support:

> I-autonomy concerns residual structural openness after the strongest adequate O/V reconstruction.

The following are insufficient:

- unpredictability;
- incomplete knowledge;
- complexity;
- sensitivity to initial conditions;
- randomness terminology alone;
- multiple possible outcomes across different inputs.

The RNG case supports autonomy only within the explicitly stated stochastic model.

The bifurcation case remains unresolved because the source does not establish whether fuller microstate information would close the branch.

The autonomy safeguard therefore survives the regression programme.

---

# 17. Failure-check status

Across the regression programme, no systematic failure was found in the following tested classes:

- selectivity inflation;
- unknown → autonomy leakage;
- human privilege;
- position proliferation;
- group-mind inflation;
- procedure reification;
- O/V erasure;
- function suppression;
- randomness inflation;
- recording inflation;
- sorting inflation;
- carrier drift;
- mapping inflation;
- probability-weighting inflation;
- branching inflation;
- instability inflation;
- ranking inflation;
- comparison inflation;
- memory inflation;
- observer inflation;
- position suppression;
- epiphenomenal-selection inflation;
- trace inflation;
- scope rescue;
- access inflation;
- topology inflation;
- sensor inflation;
- channel inflation.

This does not prove these failure modes impossible.

It means the current regression suite did not produce a reproducible failure in them.

---

# 18. What v0.3 appears to fix

The original failure pattern was:

positive selection evidence  
+ complete mechanism  
→ no structural openness  
→ I disappears

v0.3 replaces this with:

positive selection evidence  
+ complete mechanism  
→ I-function may remain ESTABLISHED

while:

complete O/V reconstruction  
→ I-autonomy NOT ESTABLISHED

This preserves the anti-confabulation protection of v4.1 while avoiding suppression of well-evidenced deterministic selective functions.

---

# 19. What remains unresolved

The regression programme does not justify declaring v0.3 final.

At least four issues remain.

## 19.1 I-position boundary

NM-07 versus NM-07B suggests a real distinction, but the exact positive criterion for I-position remains under-specified.

Retained history may matter.

It is not yet established that retained history is sufficient.

## 19.2 Degree of causal contribution

NM-08 establishes that zero causal contribution is insufficient for I-function relative to the broader continuation.

Cases with partial, probabilistic, redundant, or overdetermined causal contribution remain to be tested.

## 19.3 Multi-stage selection

Real systems may contain:

ranking  
→ shortlist  
→ selection  
→ veto  
→ execution

Different carriers may contribute at different stages.

The current protocol needs testing against chained selective architectures.

## 19.4 Scale and nested scope

A component may be:

- non-selective at one scale;
- selective at another;
- causally relevant locally;
- epiphenomenal globally.

NM-08 demonstrates the problem but does not exhaust it.

---

# 20. Decision

## Decision question

> Does the v0.3 regression programme provide sufficient evidence that the experimental separation of I-position, I-function, and I-autonomy is analytically superior to the unsplit positive-I semantics for the tested cases?

## Decision

**YES — provisionally, at experimental level.**

The evidence is sufficient to conclude that v0.3 deserves continuation as the preferred experimental semantic model.

The evidence is **not yet sufficient to replace canonical v4.1**.

---

# 21. Grounds for the decision

The decision rests on five findings.

### 1. The original false-negative is repaired

Deterministic but genuinely selective systems retain I-function under complete mechanistic reconstruction.

### 2. Anti-inflation safeguards survive

The near-miss suite does not promote filtering, thresholding, mapping, ranking, randomness, branching, recording, or epiphenomenal winner states into I-function.

### 3. Autonomy remains evidence-bound

Unknown mechanism is not converted into autonomy.

### 4. Scope sensitivity is explicit

A selection can be functional for one continuation and irrelevant for another.

### 5. The dimensions show independent variation

The test set contains multiple distinct combinations of:

- position;
- function;
- implementation;
- autonomy.

This supports the claim that the dimensions are doing genuine analytical work.

---

# 22. Canonical decision

**Do not revise v4.1 yet.**

v4.1 remains frozen.

v0.3 remains:

**EXPERIMENTAL / NON-CANONICAL / TEST-ONLY**

The regression programme supports moving to a next experimental drafting phase, not directly to canonical replacement.

---

# 23. Recommended next step

The next version should be a **v0.4 experimental draft**, not a v4.2 canonical release.

v0.4 should incorporate only findings that survived regression.

At minimum it should:

1. make explicit that mechanistic completeness does not revoke I-function;
2. move structural underdetermination entirely into I-autonomy;
3. require causal contribution to the relevant continuation for I-function claims at that scope;
4. make scope explicit for every I-function claim;
5. strengthen remove-and-compare for I-position by requiring analytical gain beyond ordinary V-connectivity;
6. preserve `UNKNOWN / UNRESOLVED` as valid outcomes;
7. preserve the rule `unexplained ≠ I`;
8. preserve O/V semantics unchanged;
9. preserve revocability of all positive I assignments;
10. carry forward the complete near-miss regression suite.

---

# 24. Proposed v0.4 gate

Do not freeze v0.4 until it passes at least:

- NM-01 through NM-08 unchanged;
- NM-07B unchanged;
- AB-01 through AB-04 unchanged;
- at least one partial-causation case;
- at least one redundant-selector case;
- at least one nested/multi-stage selection case;
- at least one additional I-position boundary case;
- cross-model reproducibility check.

A v0.4 failure must produce either:

- protocol revision;
- explicit scope limitation;
- or abandonment of the proposed semantic distinction.

No local patch should be added merely to save a preferred result.

---

# 25. Final regression statement

The current regression evidence supports the following experimental conclusion:

> **I-position, I-function, mechanistic implementation, and I-autonomy should be treated as separable analytical dimensions during further testing.**

The most important correction relative to the earlier positive-I semantics is:

> **A selective function does not cease to be a function merely because its mechanism is well understood.**

Mechanistic reconstruction determines how the function is implemented.

It does not, by itself, determine whether the function exists.

Structural openness belongs to the stronger autonomy question.

At the same time:

> **not every distinction, mapping, ranking, random branch, record, or winner state is a selective function.**

A positive I-function claim requires independent evidence of selection that contributes to the relevant realised continuation.

This combination currently provides the strongest tested balance between:

- avoiding I-inflation;
- avoiding positive-I suppression;
- preserving O/V explanatory strength;
- maintaining epistemic discipline.

---

# 26. Decision status

**v0.3 regression result:** PASS WITH OPEN POSITION BOUNDARY  
**Experimental split:** RETAIN  
**Canonical v4.1:** REMAINS FROZEN  
**Immediate canon revision:** NO  
**Proceed to v0.4 experimental draft:** YES  
**Primary unresolved issue:** positive boundary condition for I-position  
**Secondary unresolved issues:** partial causation, redundant selection, nested selection, scale/scope interaction
