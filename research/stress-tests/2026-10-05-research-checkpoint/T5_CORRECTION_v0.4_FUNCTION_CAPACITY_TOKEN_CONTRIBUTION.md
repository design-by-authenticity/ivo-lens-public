# T5 CORRECTION NOTE / v0.4 AMENDMENT

## Functional Capacity versus Token-Level Causal Contribution

**Status:** EXPERIMENTAL / NON-CANONICAL  
**Applies to:** v0.4-amended-after-T4  
**Trigger:** T5 — Scale Interaction  
**Canonical baseline:** I·V·O Lens v4.1 remains frozen  
**Decision type:** semantic correction  
**Immediate canonical effect:** none

---

# 1. Purpose

T5 exposed a tension between the treatment of redundancy in T2 and compensation in T5.

T2 established that a selector does not lose I-function merely because its effect is masked in one baseline condition by a redundant selector.

T5 initially classified Cluster A as:

- I-function ESTABLISHED for local scope;
- I-function NOT ESTABLISHED for system scope under full compensation;
- causal capacity for system scope ESTABLISHED.

This created a semantic inconsistency.

If causal capacity across admissible contingencies is sufficient to preserve I-function under redundancy, then a function should not automatically disappear at a broader scope merely because one specific realised event is fully compensated.

The missing distinction is between:

1. **functional capacity**, and
2. **token-level causal contribution**.

This amendment introduces that distinction explicitly.

---

# 2. Core correction

## Previous formulation

v0.4 tied I-function too closely to:

> contribution to which continuation becomes realised within the declared scope.

This wording can be read as requiring a non-zero effect in the specific analysed event.

That is too restrictive.

It conflates:

- the existence of a selective function capable of affecting a continuation;
- the realised causal contribution of one particular selection event under one particular condition.

---

# 3. Revised distinction

## 3.1 I-function

An **I-function** is a positively evidenced selective function that has demonstrated causal capacity to affect which continuation becomes realised within an explicitly declared analytical scope across the relevant admissible contingency structure.

A function does not lose this status merely because:

- a redundant selector masks its effect;
- a downstream compensator cancels its effect;
- a particular event produces no net change;
- another causal pathway produces the same continuation.

The function must nevertheless have:

- independent selective structure;
- a selective state or event;
- demonstrated access to the relevant causal pathway;
- evidence that changing the selective structure can affect the declared continuation in at least some admissible conditions.

---

## 3.2 Token-level causal contribution

**Token-level causal contribution** asks:

> Did this particular selection event, under this particular realised condition, make a non-zero contribution to the declared continuation?

Allowed statuses:

- **ESTABLISHED**
- **SUPPORTED**
- **ZERO / MASKED**
- **UNRESOLVED**
- **NOT APPLICABLE**

This status is event- and condition-specific.

It is not identical to I-function status.

---

# 4. Key rule

> **I-function is a functional-capacity claim. Token-level causal contribution is a realised-event claim.**

Therefore:

- functional capacity can remain positive while token-level contribution is zero;
- token-level contribution can be non-zero only if the relevant causal pathway is active in that condition;
- repeated zero token-level contribution across the full admissible contingency space may revoke the I-function claim.

---

# 5. Why T2 and T5 now become consistent

## T2 — Redundant selectors

Baseline:

A = ON  
B = ON  
Actuator = ON

Disable A:

Actuator remains ON.

So:

**A token-level contribution in that baseline:**  
ZERO / MASKED

But:

A ON / B OFF  
→ Actuator ON

and:

disable A in that contingency  
→ Actuator OFF

Therefore:

**A functional capacity for actuator scope:**  
ESTABLISHED

Hence:

**A I-function:**  
ESTABLISHED

The same applies to B.

---

## T5 — Downstream compensation

Baseline:

A selects PERFORMANCE  
→ A-power rises  
→ B compensates  
→ TOTAL_POWER unchanged

Therefore:

**A token-level contribution to S4 under full compensation:**  
ZERO / MASKED

But when compensation is disabled:

A selection changes  
→ TOTAL_POWER changes

Therefore:

**A functional capacity for S4:**  
ESTABLISHED

Hence:

**A I-function relevant to S4:**  
ESTABLISHED

or, where evidence is weaker:

**SUPPORTED**

The original T5 result:

> I-function NOT ESTABLISHED for S4 under full compensation

is therefore corrected.

---

# 6. Corrected T5 classification

## Cluster A — S1 internal selection

**I-function:** ESTABLISHED  
**Token-level contribution:** ESTABLISHED

---

## Cluster A — S2 local execution

### Baseline

**I-function:** ESTABLISHED  
**Token-level contribution:** ESTABLISHED

### Hardware override

The selection state still exists, but execution ignores it.

Therefore:

**I-function for S2 under active architecture:** SUPPORTED / ESTABLISHED as functional capacity  
**Token-level contribution in override condition:** ZERO / MASKED

If the override is permanent and structurally removes any possible effect on S2 across all admissible conditions, then the S2 I-function claim must be revoked.

---

## Cluster A — S4 total system power

### Full compensation

**I-function relevant to S4:** ESTABLISHED  
**Functional capacity for S4:** ESTABLISHED  
**Token-level causal contribution:** ZERO / MASKED

### Partial compensation

**I-function relevant to S4:** ESTABLISHED  
**Functional capacity:** ESTABLISHED  
**Token-level causal contribution:** ESTABLISHED

### Compensation disabled

**I-function relevant to S4:** ESTABLISHED  
**Functional capacity:** ESTABLISHED  
**Token-level causal contribution:** ESTABLISHED

---

# 7. Revised causal-contribution gate

Replace the previous single gate with two gates.

## Gate A — Functional-capacity gate

Ask:

> Does intervention on the selective structure change the declared continuation in at least one relevant admissible condition?

If yes:

functional capacity is supported or established.

If no across the relevant contingency space:

I-function is not established for that scope.

---

## Gate B — Token-contribution gate

Ask:

> In the specific analysed condition, does this selection event produce a non-zero net contribution to the declared continuation?

Possible result:

- ESTABLISHED
- SUPPORTED
- ZERO / MASKED
- UNRESOLVED

Gate B does not by itself determine Gate A.

---

# 8. Revised I-function definition

The previous experimental definition:

> An I-function is a positively evidenced selective function whose operation contributes to which continuation becomes realised within an explicitly declared analytical scope.

is replaced by:

> **An I-function is a positively evidenced selective function with demonstrated causal capacity to affect which continuation becomes realised within an explicitly declared analytical scope across the relevant admissible contingency structure.**

This definition preserves:

- T1 partial causation;
- T2 redundancy;
- T3/T3B nested and relational selection;
- T5 compensation;
- NM-08 epiphenomenality exclusion.

---

# 9. Revised NM-08 comparison

NM-08 remains negative for the broader execution scope because the internal committee selection had no demonstrated causal capacity to affect actual execution across the relevant admissible contingency structure.

The external rule bypassed it.

Therefore:

**I-function for execution:** NOT ESTABLISHED

This differs from T5.

In T5:

A demonstrably can affect S4 when compensation is absent or incomplete.

Therefore:

A possesses causal capacity for S4 even when the realised baseline contribution is masked.

---

# 10. Revised T1 interpretation

T1 remains unchanged in substance.

The triage function has:

**I-function:** ESTABLISHED

because intervention on the selective structure changes route probabilities.

For a particular patient:

the token-level causal contribution may be:

- ESTABLISHED;
- MASKED by veto;
- or UNRESOLVED.

This does not remove the triage I-function.

Thus T1 becomes more precise:

> partial causation establishes functional capacity without requiring every token event to alter the realised continuation.

---

# 11. Revised T2 interpretation

T2 remains unchanged in substance.

Each redundant selector has:

**I-function:** ESTABLISHED

because each can affect actuator continuation in admissible contingencies.

In the overdetermined baseline:

**token-level contribution:** ZERO / MASKED

with respect to necessity-based net change.

This prevents redundancy suppression.

---

# 12. Revised T3 interpretation

For nested selection:

- shortlist;
- relational allocation;
- final selection

may each possess I-function if they have demonstrated causal capacity for their relevant scope.

A later stage may mask, override, or cancel an earlier event.

That can change token-level contribution without retroactively erasing functional capacity.

T3 Stage 4 after execution disconnect therefore becomes:

### S4 — internal final winner

I-function ESTABLISHED  
Token contribution ESTABLISHED

### S5 — actual execution

If the disconnect is a temporary/conditional override and other admissible conditions retain the execution link:

I-function relevant to S5 may remain SUPPORTED/ESTABLISHED as capacity, while token contribution in the disconnected condition is ZERO / MASKED.

If the disconnect permanently removes the causal route across all admissible conditions:

I-function for S5 = NOT ESTABLISHED.

This distinction must be made explicitly in future reruns.

---

# 13. Architectural consequence

The experimental architecture is now:

## Situated analysis

- scope
- carrier
- access
- history/state
- outside view

## I-function

- functional selective capacity

## Token-level causal contribution

- realised contribution in a particular condition

## Mechanistic implementation

- COMPLETE
- PARTIAL
- UNRESOLVED

## I-autonomy

- residual structural openness after strongest adequate O/V reconstruction

Independent I-position remains demoted after T4.

---

# 14. Revised output schema

Every relevant analysis should now report:

**Primary analytical scope:**  
[scope]

**Carrier:**  
[carrier]

**Situated analysis:**  
[access / history / outside view]

**I-function:**  
[ESTABLISHED / SUPPORTED / UNRESOLVED / NOT ESTABLISHED]

**Functional causal capacity:**  
[ESTABLISHED / SUPPORTED / UNRESOLVED / NOT ESTABLISHED]

**Token-level causal contribution:**  
[ESTABLISHED / SUPPORTED / ZERO-MASKED / UNRESOLVED / NOT APPLICABLE]

**Selective consequence:**  
[description]

**Mechanistic implementation:**  
[COMPLETE / PARTIAL / UNRESOLVED]

**I-autonomy:**  
[ESTABLISHED / SUPPORTED / UNRESOLVED / NOT ESTABLISHED]

**O/V-only reconstruction:**  
[sufficient / insufficient / unresolved]

**Failure checks:**  
[status]

**Revocation conditions:**  
[criteria]

---

# 15. Revocation rule for I-function

A positive I-function claim must be revoked if:

1. the apparent selector has no independent selective structure;
2. its output does not enter the relevant causal pathway;
3. no admissible intervention on the selective structure changes the declared continuation;
4. all observed effects reduce to correlation, logging, thresholding, mapping, or downstream state description;
5. the supposed function is epiphenomenal across the full relevant contingency space.

A single masked event is not sufficient for revocation.

---

# 16. New failure checks

Add:

## FC-66 Capacity/contribution collapse

Does the analysis confuse functional causal capacity with realised token-level contribution?

## FC-67 Token suppression

Does one zero-effect event incorrectly revoke an otherwise demonstrated I-function?

## FC-68 Capacity inflation

Is mere hypothetical possibility treated as causal capacity without intervention or equivalent evidence?

## FC-69 Masking inflation

Is every zero-effect event excused as “masking” without evidence of a genuine causal pathway?

## FC-70 Contingency overreach

Is I-function preserved using remote or irrelevant hypothetical contingencies rather than the declared admissible contingency structure?

---

# 17. Corrected T5 decision

## Previous

**PASS ON SCALE/SCOPE DISCIPLINE, semantic tension exposed**

## Corrected

**PASS AFTER SEMANTIC CORRECTION**

T5 establishes that:

1. local I-function can remain positive despite system-level masking;
2. function status is scope-specific;
3. causal capacity and token-level contribution must be reported separately;
4. complete compensation can reduce token-level system contribution to zero without erasing functional capacity;
5. partial compensation produces a non-zero token-level contribution;
6. deterministic feedback control still does not automatically establish I-function;
7. local function does not automatically imply a new system-level aggregate function.

---

# 18. Corrected central rule

> **Function belongs to a selective architecture relative to a declared scope; contribution belongs to a particular realised event under a particular condition.**

And:

> **Masking can suppress realised contribution without suppressing function, provided causal capacity is independently demonstrated across the relevant admissible contingency structure.**

---

# 19. Canonical status

No canonical change is made.

Canonical v4.1 remains:

**FROZEN**

This correction applies only to the experimental v0.4 line.

---

# 20. Experimental status

**T1:** PASS  
**T2:** PASS  
**T3:** PASS WITH T3B CORRECTION  
**T3B:** PASS WITH SEMANTIC QUALIFICATION  
**T4:** positive independent I-position NOT ESTABLISHED; architecture amended  
**T5:** PASS AFTER FUNCTION/CAPACITY/CONTRIBUTION CORRECTION

**Current experimental architecture:**

Situated analysis  
+ I-function  
+ functional causal capacity  
+ token-level causal contribution  
+ mechanistic implementation  
+ I-autonomy

**Next step:** full regression rerun before any freeze or canonical proposal.
