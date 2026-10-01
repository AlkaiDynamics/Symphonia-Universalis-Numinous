# SUN_PROSPECTIVE_TRIAL_0_CANDIDATE_ELECTION

**Status:** CANDIDATE-ELECTION ARTIFACT  
**SUN version:** SUN V1 B — LOCKED FORMAL HYPOTHESIS  
**Purpose:** Select a *protocol-shakedown* candidate family for the first genuinely prospective execution of the SUN V1 B harness.  
**Empirical status:** **NO SUN EMPIRICAL PREDICTION EXISTS.**  
**Important:** This artifact selects a trial *family*. It does not instantiate \(\omega_0^+\), reveal a target, choose a SUN realization, or license a confirmatory claim.

---

## 1. Governing distinction

Retrospective cases may calibrate the harness, but they cannot become licensed confirmatory trials after the answer was already available.

The first prospective execution must therefore begin before the target truth is known and must preserve the V1 B sequence:

\[
\boxed{
\text{freeze}
\rightarrow
\text{close}
\rightarrow
\text{mask}
\rightarrow
\text{enumerate}
\rightarrow
\text{commit}
\rightarrow
\mathbf{MODELING\ STOPS}
\rightarrow
\text{reveal once}
\rightarrow
\text{score}.
}
\]

For Trial 0, the objective is **protocol shakedown**, not support for the full cross-domain SUN hypothesis. Trial 0 does not count toward the population-governed empirical program unless it is independently selected under the eventually frozen \((\Sigma_0,\nu_0)\) mechanism.

---

## 2. Candidate-election hard gates

A candidate family is ineligible unless all hard gates can be satisfied *before target reveal*.

| ID | Hard gate | Requirement |
|---|---|---|
| H1 | Genuine hiddenness | The concrete target truth must not be known to the SUN analyst/model before commitment. |
| H2 | Unambiguous reveal | A later truth oracle must return one evaluation-equivalent answer. |
| H3 | Native independence | The native state/model space must be defined without SUN. |
| H4 | Native headroom | The visible native information must leave at least two target possibilities before SUN enters. |
| H5 | Discovery auditability | \(K_{\rm seen}\) and its closure must be realistically auditable. |
| H6 | Realization exhaustibility | The admissible SUN realization/adapter space must be finite or certifiably exhaustible. |
| H7 | Nonvacuity testability | It must be possible to determine whether SUN strictly prunes the native target set/distribution. |
| H8 | Immutable commitment | The complete prereveal state and prediction can be hashed/timestamped before reveal. |
| H9 | Failure admissibility | A licensed miss will be recorded as a miss; no remapping, tolerance change, or target change is permitted after commitment. |

Any failure at H1–H9 excludes the candidate from Trial 0.

---

## 3. Feasibility score

Surviving candidates are scored only for **protocol feasibility**, never for aesthetic or structural resemblance to SUN.

Each dimension is scored:

- `2` = straightforward / finite / machine-certifiable
- `1` = feasible but materially expensive or assumption-sensitive
- `0` = presently not certifiable enough for Trial 0

Scored dimensions:

\[
\boxed{
(F_1,\ldots,F_{10})
}
\]

where:

1. hidden-target generation,
2. truth-oracle closure,
3. native-model exhaustion,
4. discovery-ledger closure,
5. noninterference verification,
6. native headroom certification,
7. SUN-adapter exhaustion,
8. prediction-equivalence/gauge handling,
9. commitment/reveal automation,
10. low implementation burden.

Maximum score: \(20\).

A high score means **easy to test correctly**, not “likely to confirm SUN.”

---

## 4. Candidate pool

### C1 — Small finite graph completion

**Native domain:** finite simple undirected graph theory.  
**Hidden target:** a Boolean or finite graph property of a freshly sampled complete graph whose small edge region is masked before analysis.  
**Native model:** every completion of the masked edge set consistent with the visible graph.  
**Reveal:** unseal the original full graph.

This is finite, exact, easy to enumerate, and permits explicit certificate generation. The concrete graph and target truth can be freshly generated after all trial machinery is frozen.

### C2 — Deterministic finite automaton completion

**Native domain:** automata theory.  
**Hidden target:** acceptance/output behavior on a held-out transition or word for a freshly sampled finite automaton.  
**Native model:** all transition/output tables consistent with visible entries and the declared automaton class.  
**Reveal:** unseal the original transition table.

Finite and highly certifiable. Care is required to avoid selecting an automaton family whose topology was designed from SUN.

### C3 — Finite algebra / Cayley-table completion

**Native domain:** finite algebra.  
**Hidden target:** one held-out product or structural property of a freshly sampled finite algebraic object.  
**Native model:** all completions satisfying the native axioms and visible table entries.  
**Reveal:** unseal the complete table.

Excellent exactness; associativity/isomorphism closure makes enumeration more expensive.

### C4 — Latin-square / quasigroup completion

**Native domain:** combinatorics.  
**Hidden target:** a held-out cell or finite invariant of a sealed Latin square/quasigroup.  
**Native model:** all completions satisfying the native Latin constraint.  
**Reveal:** unseal the original object.

Finite, independent, and easy to score. Adapter exhaustibility is somewhat more expensive than graph completion but still realistic at small order.

### C5 — Finite digital circuit fault/completion

**Native domain:** digital logic.  
**Hidden target:** output/fault state under a masked internal gate/connection.  
**Native model:** all circuit completions consistent with visible netlist and native Boolean semantics.  
**Reveal:** unseal the complete circuit/testbench.

Strong oracle and failure semantics; model/adapter enumeration is larger.

### C6 — Small constraint-satisfaction instance

**Native domain:** finite CSP.  
**Hidden target:** one hidden variable/class of a sealed CSP instance with several native completions visible before reveal.  
**Native model:** all native satisfying assignments under the visible constraints.  
**Reveal:** unseal the selected original solution/target.

Extremely tractable, but the oracle must distinguish “the generating hidden solution” from “any satisfying completion”; otherwise the truth class is not unique.

### C7 — Crystallographic symmetry classification from masked observations

**Native domain:** crystallography.  
**Hidden target:** a symmetry/space-group property withheld from a real or simulated structure record.  
**Native model:** native crystallographic models compatible with visible observations.  
**Reveal:** unseal the full structure record.

Scientifically attractive but considerably harder to certify for exhaustive native closure and contamination.

### C8 — Network fault localization

**Native domain:** network/reliability engineering.  
**Hidden target:** the sealed failed component or finite fault class after selected telemetry is withheld.  
**Native model:** all faults consistent with the visible telemetry and declared network model.  
**Reveal:** unseal the injected/known fault.

Good oracle and failure semantics; model completeness depends heavily on how the network is bounded.

### C9 — Astronomical/orbital classification from masked measurements

**Native domain:** celestial mechanics / astronomy.  
**Hidden target:** a held-out finite orbital class or property.  
**Native model:** models compatible with visible observations.  
**Reveal:** unmask the withheld measurement/classification.

Real-domain appeal is high, but continuous uncertainty, model completeness, and oracle dependence make this unsuitable for the first shakedown.

### C10 — Historical/textual stemmatic placement

**Native domain:** textual criticism.  
**Hidden target:** held-out witness placement/reading class.  
**Native model:** admissible native stemmata/readings.  
**Reveal:** an independently held source or later-opened witness.

This is important for later SUN work but presently weak for Trial 0 because oracle uniqueness and exhaustive native closure are difficult to certify.

---

## 5. Feasibility matrix

| Candidate | H1–H9 | Hidden | Oracle | Native exhaustion | Discovery | NI | Headroom | Adapter exhaustion | Gauge/equiv | Commit/reveal | Burden | Total /20 |
|---|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|
| **C1 finite graph completion** | PASS | 2 | 2 | 2 | 2 | 2 | 2 | 2 | 2 | 2 | 2 | **20** |
| **C2 DFA completion** | PASS | 2 | 2 | 2 | 2 | 2 | 2 | 2 | 2 | 2 | 2 | **20** |
| **C4 Latin/quasigroup completion** | PASS | 2 | 2 | 2 | 2 | 2 | 2 | 1 | 2 | 2 | 2 | **19** |
| **C3 finite algebra completion** | PASS | 2 | 2 | 2 | 2 | 2 | 2 | 1 | 1 | 2 | 1 | **17** |
| **C6 finite CSP** | CONDITIONAL | 2 | 1 | 2 | 2 | 2 | 2 | 1 | 2 | 2 | 2 | **18*** |
| **C5 digital circuit** | PASS | 2 | 2 | 1 | 2 | 2 | 2 | 1 | 1 | 2 | 1 | **16** |
| **C8 network fault** | CONDITIONAL | 2 | 2 | 1 | 2 | 2 | 2 | 1 | 1 | 2 | 1 | **16*** |
| **C7 crystallography** | CONDITIONAL | 2 | 2 | 1 | 1 | 1 | 1 | 1 | 1 | 2 | 0 | **12*** |
| **C9 astronomy/orbital** | DEFER | 2 | 2 | 0 | 1 | 1 | 1 | 0 | 1 | 2 | 0 | **10** |
| **C10 textual/stemmatic** | DEFER | 2 | 1 | 0 | 1 | 1 | 2 | 0 | 1 | 2 | 0 | **10** |

`*` Conditional candidates are not eligible until their stated oracle/model-completeness problem is resolved.

The two perfect feasibility scores are a tie. The tie is resolved without reference to expected SUN success:

1. prefer the candidate with the simpler machine-verifiable native completion certificate;
2. prefer the candidate with the simpler masking/noninterference proof;
3. prefer the candidate whose symmetry/gauge group is straightforward to enumerate;
4. if still tied, use a predeclared random tie-breaker.

Under criteria 1–3, **C1 small finite graph completion** is elected for Trial 0 because graph completion, graph automorphisms, finite property evaluation, and exhaustive injective adapter enumeration can all be expressed in one simple discrete representation. This is an engineering-feasibility decision, not evidence that graph theory is “more SUN-like.”

---

# 6. Elected Trial-0 family

\[
\boxed{
\textbf{SUN-PROSPECTIVE-TRIAL-0}
=
\textbf{SEALED SMALL-FINITE-GRAPH COMPLETION}
}
\]

## 6.1 Native domain

Let

\[
D=\mathsf{FinSimpleUndirectedGraph}_{n,m}
\]

for a small preregistered range of \(n\) and a bounded number \(m\) of masked edge bits.

The native domain definition contains no SUN concepts.

## 6.2 Fresh hidden-instance generation

A concrete full graph \(G^\star\) must be generated **after** the trial generator, target-family rules, masks, verifier suite, and random seed protocol are frozen.

The analyst receives only

\[
G_{\rm vis}=\mu(G^\star).
\]

The full graph is placed in a sealed truth artifact and cryptographically committed without being shown to the analyst/model.

## 6.3 Native completion space

If \(m\) edge bits are hidden, define

\[
\mathfrak M_D^{(0)}
=
\{
G:\;G|_{\rm visible}=G_{\rm vis}
\}.
\]

Before any SUN mapping, exhaust all \(2^m\) completions (or a smaller subset if native constraints remove some) and certify the enumeration.

This yields the native target set

\[
\mathcal C_0^{\rm eval}.
\]

Trial generation must terminate with `NO-HEADROOM` if

\[
|\mathcal C_0^{\rm eval}|<2.
\]

That termination is not a SUN failure.

## 6.4 Target-family selection

The target **property family must be frozen before the concrete graph is sampled**.

A safe Trial-0 target library should contain finite native graph properties only, for example:

- specified-vertex connectivity class,
- existence/nonexistence of a specified local motif,
- parity/cardinality class of a specified native substructure,
- articulation/separation property,
- bounded path-class property.

The property selector is part of the frozen trial sampler. No property may be chosen after seeing \(G_{\rm vis}\) because it gives a more attractive SUN consequence.

The exact target must be finite and machine-verifiable.

## 6.5 Discovery contamination

Because \(G^\star\) is freshly generated after the protocol is frozen, the concrete target truth cannot already exist in the prior SUN conversation history.

Nevertheless \(K_{\rm seen}\) must record:

- the complete Trial-0 generator specification,
- all graph-theoretic facts inspected before commitment,
- all candidate target families,
- all SUN realizations/adapters considered,
- every rejected mapping,
- all code/version hashes.

The discovery closure still requires a certificate; freshness alone does not waive it.

## 6.6 SUN realization language

Only after native closure/headroom is established may the frozen SUN grammar enter.

The adapter language must be fixed before the hidden graph is sampled. It should enumerate every admissible type/operation-preserving embedding permitted by the declared graph interpretation.

No realization is selected because it gives the desired answer.

Require

\[
Q_D^R=1.
\]

Possible outcomes include:

- `NO-REALIZATION`,
- `NONUNIQUE`,
- `PREREVEAL-INCONSISTENT`,
- `NONINFORMATIVE`,
- or a licensed prereveal consequence.

Each is a legitimate Trial-0 outcome.

## 6.7 Nonvacuity

A confirmatory prediction is impossible unless

\[
\mathcal C_{\rm SUN}^{\rm eval}
\subsetneq
\mathcal C_0^{\rm eval}.
\]

If SUN leaves the native target set unchanged, record:

\[
\boxed{\mathbf{NONINFORMATIVE}}
\]

and stop.

## 6.8 Commitment

If and only if every V1 B licensing gate succeeds, serialize the complete prereveal state, including:

\[
\omega_0^+,
\quad
\mathfrak\Gamma_T^{(0)},
\quad
\Lambda_T^\star,
\quad
K_{\rm seen}^{+},
\quad
\mu_T^\star,
\quad
\mathfrak M_D^{(0)},
\quad
\mathfrak R_D^{(0)},
\quad
\mathcal C_0^{\rm eval},
\quad
\mathcal C_{\rm SUN}^{\rm eval}.
\]

Compute and externally record its cryptographic hash.

Then:

\[
\boxed{\mathbf{MODELING\ STOPS}.}
\]

## 6.9 Reveal

Unseal \(G^\star\) exactly once and evaluate

\[
z_{\rm true}=T(G^\star).
\]

No target, adapter, equivalence relation, tolerance, model, or score may change afterward.

## 6.10 Scoring

For finite SET mode:

\[
\operatorname{Retain}_T
=
\mathbf 1
\left[
[z_{\rm true}]_{\rm eval}
\in
\mathcal C_{\rm SUN}^{\rm eval}
\right].
\]

and

\[
G_T
=
1-
\frac{
|\mathcal C_{\rm SUN}^{\rm eval}|
}{
|\mathcal C_0^{\rm eval}|
}.
\]

A positive Trial-0 result requires:

\[
\boxed{
\mathsf L_{\rm SUN}=1
\land
\operatorname{Retain}_T=1
\land
G_T>0.
}
\]

A licensed miss is recorded as a miss. Under V1 B it falsifies the universal retention claim for the registered empirical program to which the trial belongs; Trial 0 itself remains explicitly designated as a shakedown unless it was sampled under the final frozen population mechanism.

---

# 7. Pre-instantiation freeze checklist

Before a concrete graph is generated, freeze:

1. \(n\) and the bounded mask size \(m\);
2. full-graph sampling law;
3. mask-selection law;
4. target-property library;
5. target-property selector;
6. truth-oracle code and verifier;
7. discovery-inference language;
8. mask/noninterference verifier;
9. native completion enumerator and certificate verifier;
10. SUN subgrammar language;
11. adapter language;
12. adapter validity predicate;
13. realization equivalence relation;
14. target evaluation equivalence;
15. gauge/automorphism treatment;
16. retention rule;
17. information-gain formula;
18. serialization format;
19. hash algorithm / timestamp procedure;
20. all stop conditions.

Only after these are frozen may Trial 0 generate \(G^\star\).

---

# 8. Stop conditions

The implementation must stop, without attempting to rescue the trial, at any of:

\[
\boxed{
\begin{array}{l}
\mathbf{ORACLE\mbox{-}UNCLOSED}\\
\mathbf{DISCOVERY\mbox{-}CONTAMINATED}\\
\mathbf{NONINTERFERENCE\mbox{-}UNVERIFIED}\\
\mathbf{NATIVE\mbox{-}UNCLOSED}\\
\mathbf{NO\mbox{-}HEADROOM}\\
\mathbf{NO\mbox{-}REALIZATION}\\
\mathbf{NONUNIQUE}\\
\mathbf{PREREVEAL\mbox{-}INCONSISTENT}\\
\mathbf{NONINFORMATIVE}
\end{array}
}
\]

None of these may be converted post hoc into a new target or adapter.

---

# 9. What this artifact does and does not establish

This artifact establishes:

\[
\boxed{
\text{a preregisterable Trial-0 candidate family has been elected by protocol feasibility}.
}
\]

It does **not** establish:

- that a concrete Trial-0 instance is licensed;
- that a SUN realization exists in the sampled graph;
- that SUN will constrain the hidden target;
- that the hidden truth will be retained;
- that \(G_T>0\);
- that the full SUN V1 B hypothesis has empirical support.

Therefore, at the end of candidate election:

\[
\boxed{\textbf{THERE IS STILL NO SUN EMPIRICAL PREDICTION.}}
\]

---

# 10. Next admissible artifact

The next artifact is:

\[
\boxed{
\texttt{SUN\_PROSPECTIVE\_TRIAL\_0\_PREREGISTRATION}
}
\]

It must freeze the twenty pre-instantiation items above **before any concrete hidden graph is generated**.

Only after that preregistration is immutable may the first sealed Trial-0 instance be created.