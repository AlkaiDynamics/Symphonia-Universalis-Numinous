# SUN V1 C

## FORMAL HYPOTHESIS AND PREDICTIVE REGISTRATION PROTOCOL

### STATUS

$$
\boxed{\textbf{CANDIDATE REVISION — NOT YET LOCKED}}
$$

V1 C preserves the anti-fitting, closure, blindness, exhaustion, commitment, single-reveal, and no-remapping protections of SUN V1 B.

Its principal correction is to formalize the intended application mechanism:

$$
\boxed{
\text{KNOWN PARTIAL ALIGNMENT MAY LOCATE AND CONSTRAIN AN UNKNOWN}
}
$$

without implying

$$
\boxed{
\text{THE UNKNOWN'S TRUTH IS ALREADY KNOWN}.
}
$$

Observed alignment is registration evidence.

It is not held-out confirmation.

---

# I. FIXED SUN GRAMMAR

Define the fixed relational grammar

$$
\boxed{
\mathcal G_{\rm SUN}
=
(R,L,\mathcal C,\mathcal B,\mathcal I,h,g).
}
$$

The ordinary transition cell is

$$
\boxed{
C_n
\longrightarrow
\{R(C_n),L(C_n)\}
\longrightarrow
C_{n+1}.
}
$$

The grammar contains exactly three ordinary recursive generations

$$
\boxed{
C_0\to C_1\to C_2\to C_3
}
$$

followed by a structurally distinct boundary transition

$$
\boxed{
C_3\xrightarrow{\mathcal B}C_4.
}
$$

The canonical harmonic realization remains

$$
\boxed{
R=\frac23,
\qquad
L=\frac34,
\qquad
RL=\frac12,
}
$$

with inverse orientation

$$
\boxed{
R^{-1}=\frac32,
\qquad
L^{-1}=\frac43,
\qquad
R^{-1}L^{-1}=2.
}
$$

The boundary may preserve a registered local invariant

$$
\boxed{
\mathcal I(\mathcal Bs)=\mathcal I(s)
}
$$

without requiring complete state identity:

$$
\boxed{
\mathcal Bs\neq s.
}
$$

The generation/register coordinate remains

$$
\boxed{
g(C_{n+1})=g(C_n)+1.
}
$$

This statement means only:

$$
\boxed{
\text{ONE GENERATION HAS BEEN ADVANCED}.
}
$$

It does **not** encode the proposed one-note, one-class, or positional displacement.

That question is separated below.

---

# II. GENERATION IS NOT CLASS POSITION

Introduce a distinct candidate class/address coordinate

$$
\boxed{
\chi.
}
$$

Depending on the native domain, \(\chi\) may represent:

* note position;
* class address;
* orientation class;
* fiber address;
* residue class;
* categorical position;
* or another preregistered native analogue.

The coordinates

$$
\boxed{
g
\qquad\text{and}\qquad
\chi
}
$$

are explicitly distinct.

Thus:

$$
\boxed{
\Delta g=+1
}
$$

does not imply

$$
\boxed{
\Delta\chi=+1.
}
$$

Nor does a shift in \(\chi\) imply a generation increment.

No later analysis may identify these coordinates merely because they happen to covary in one realization.

---

# III. DISPLACEMENT HYPOTHESIS

The proposed systematic class displacement is **not presently built into \(H_{\rm grammar}\)**.

Define instead the separately falsifiable hypothesis

$$
\boxed{
H_{\rm displacement}.
}
$$

Let \(\mathcal X_\chi\) be a preregistered class/address space.

Let

$$
\boxed{
\delta_\chi:
\mathcal X_\chi\rightarrow\mathcal X_\chi
}
$$

be a candidate displacement operator.

Then

$$
\boxed{
H_{\rm displacement}:
\quad
\chi(C_{n+1})
=
\delta_\chi(\chi(C_n))
}
$$

for the class of ordinary generations to which the claim applies.

The stronger **one-note displacement hypothesis** is

$$
\boxed{
H_{+1}:
\quad
\delta_\chi=\operatorname{Succ}_{\mathcal X_\chi},
}
$$

where \(\operatorname{Succ}\) is the preregistered one-position successor on the relevant ordered or cyclic class space.

For a cyclic realization of size \(q\),

$$
\boxed{
\chi(C_{n+1})
=
\chi(C_n)+1
\pmod q.
}
$$

Neither \(q\) nor the \(+1\) law is assumed merely from SUN terminology.

They must be established or tested independently.

---

# IV. THREE NESTED EMPIRICAL CLAIMS

The proposed gap mechanism is decomposed into three logically distinct claims.

### H1 — Registration reduction

$$
\boxed{
H_1:
\text{independent anchors reduce admissible registration/orientation uncertainty}.
}
$$

### H2 — Gap illumination

$$
\boxed{
H_2:
\text{the reduced registration space decreases uncertainty about an unresolved}
\atop
\text{native location, class, relation, continuation, or property}.
}
$$

### H3 — Reality retention

$$
\boxed{
H_3:
\text{the subsequently revealed native reality lies inside the preregistered}
\atop
\text{SUN-constrained possibility set}.
}
$$

Therefore SUN can fail locally and diagnostically:

$$
H_1=0
$$

means the anchors failed to orient/register the system.

$$
H_1=1,\ H_2=0
$$

means registration succeeded but provided no predictive gap constraint.

$$
H_1=1,\ H_2=1,\ H_3=0
$$

means SUN made a genuine novel prediction and reality contradicted it.

This decomposition is preserved in all scoring.

---

# V. CANDIDATE PARTIAL REGISTRATIONS

SUN does not begin by freezing one preferred anchor map.

Let

$$
\boxed{
\mathcal L_{\rm anchor}^{(0)}
}
$$

be the frozen language of admissible partial SUN-to-native registrations.

Define

$$
\boxed{
\mathfrak A_D^{(0)}
=
\left\{
A_{\rm anchor}\in\mathcal L_{\rm anchor}^{(0)}
:
V_{\rm anchor}(A_{\rm anchor})=1
\right\}.
}
$$

Every admissible partial registration remains alive.

No registration may be discarded merely because another registration gives a more attractive prediction.

Require certified exhaustion:

$$
\boxed{
Q_D^{\rm anchor}=1.
}
$$

Define

$$
\boxed{
\mathsf{AnchorClosed}
\iff
Q_D^{\rm anchor}=1
\land
|\mathfrak A_D^{(0)}|>0.
}
$$

Gauge-equivalent registrations may be quotiented only under a frozen anchor-equivalence relation

$$
\boxed{
\sim_{\rm anchor}.
}
$$

Thus

$$
\boxed{
\mathfrak A_D^{(0)}/\!\sim_{\rm anchor}
}
$$

is the complete empirical partial-registration space.

---

# VI. ANCHOR CONSTRAINT RANK

Merely counting anchors is insufficient.

Let

$$
A=\{a_1,\ldots,a_k\}
$$

be an observed candidate anchor set.

Let

$$
\mathfrak R(A)
$$

denote the admissible realization space after applying all constraints induced by \(A\).

Define the **anchor constraint rank**

$$
\boxed{
\rho_{\rm anchor}(A)
}
$$

as the greatest integer \(r\) for which there exists an ordering

$$
a_{i_1},\ldots,a_{i_r}
$$

such that, modulo frozen gauge equivalence,

$$
\boxed{
\mathfrak R_0
\supsetneq
\mathfrak R_1
\supsetneq
\cdots
\supsetneq
\mathfrak R_r,
}
$$

where \(\mathfrak R_j\) is the surviving realization space after introducing the first \(j\) anchor constraints.

Thus each counted rank increment must contribute genuinely new restriction.

Three visible correspondences do not automatically imply

$$
\rho_{\rm anchor}=3.
$$

The proposed three-anchor mechanism therefore becomes:

$$
\boxed{
H_{\rm triangulation}:
\quad
\rho_{\rm anchor}\ge3
\Longrightarrow
\text{gap uncertainty is sometimes strictly reduced}.
}
$$

The threshold three remains empirical.

Possible alternatives include:

$$
\rho_{\rm anchor}=2,
$$

$$
\rho_{\rm anchor}=3,
$$

$$
\rho_{\rm anchor}=3+\text{orientation datum},
$$

or another threshold discovered empirically.

---

# VII. REGISTRATION CONSISTENCY

Candidate registrations must preserve more than labels.

Where applicable:

$$
\boxed{
A\circ R=R_D\circ A,
}
$$

$$
\boxed{
A\circ L=L_D\circ A,
}
$$

$$
\boxed{
A\circ(RL)
=
(R_DL_D)\circ A.
}
$$

If a displacement hypothesis is under test, also require

$$
\boxed{
\chi_D(A(C_{n+1}))
=
\delta_{\chi,D}
\bigl(
\chi_D(A(C_n))
\bigr).
}
$$

This is separate from

$$
g(C_{n+1})=g(C_n)+1.
$$

Define

$$
\boxed{
\mathsf{DisplacementConsistent}(A,\delta_\chi)=1
}
$$

iff every registered generation to which the displacement claim applies satisfies the preregistered class-displacement relation.

A candidate registration may fail this gate.

Its failure is evidence against that registration and, where applicable, against the proposed displacement law.

---

# VIII. GAP IDENTIFICATION

Given the complete admissible partial-registration space

$$
\mathfrak A_D^{(0)},
$$

define a frozen gap-selection procedure

$$
\boxed{
F_{\rm gap}.
}
$$

It may use:

* visible native evidence;
* all registered candidate anchors;
* the complete admissible anchor space;
* frozen SUN structural relations;
* and any preregistered displacement hypothesis being tested.

It may not use the hidden target truth.

The procedure returns a **registered selection event**

$$
\boxed{
E_{\rm sel}.
}
$$

This event contains at minimum:

$$
\boxed{
E_{\rm sel}
=
(
D,
\text{gap identity},
\text{target variable},
\text{selection rule},
\text{anchor evidence used}
).
}
$$

Define

$$
\boxed{
\mathsf{GapDerived}=1
}
$$

iff \(E_{\rm sel}\) was produced exclusively by the frozen prereveal procedure.

Therefore:

$$
\boxed{
\text{SUN MAY HELP DETERMINE WHICH QUESTION IS WORTH TESTING}.
}
$$

But:

$$
\boxed{
\text{THE ANSWER TO THAT QUESTION MUST REMAIN UNRESOLVED}.
}
$$

---

# IX. SELECTION-CONDITIONED NATIVE BASELINE

Target selection itself contains information.

SUN may not receive that information twice.

Once

$$
E_{\rm sel}
$$

has been registered, the native baseline is given the **same public target-selection event**.

For every native model \(M\), define

$$
\boxed{
S_{E,M}^{(0)}
\bigm|
E_{\rm sel}.
}
$$

The corresponding native target set is

$$
\boxed{
\mathcal C_0(M\mid E_{\rm sel})
=
T
\left(
S_{E,M}^{(0)}
\mid E_{\rm sel}
\right).
}
$$

After native-model closure define

$$
\boxed{
\mathcal C_0^{\rm eval}(E_{\rm sel}).
}
$$

The native model receives:

> this is the location/question now being evaluated.

It does **not** receive SUN's reasoning for why that target was selected.

Thus answer-level information gain is always evaluated conditionally:

$$
\boxed{
G_T
=
G_T\mid E_{\rm sel}.
}
$$

This prevents gap selection from being counted a second time as answer prediction.

---

# X. TWO DISTINCT INFORMATION GAINS

SUN may contribute information at two stages.

## X.A Registration/gap gain

Let

$$
\mathcal X_{\rm gap}^{\rm native}
$$

be the native set of possible unresolved locations/classes/properties before SUN registration is propagated.

Let

$$
\mathcal X_{\rm gap}^{\rm SUN}
$$

be the common surviving gap set across all admissible SUN registrations.

Define

$$
\boxed{
G_{\rm gap}
=
1-
\frac{
\mathcal U_{\rm gap}
(
\mathcal X_{\rm gap}^{\rm SUN}
)
}{
\mathcal U_{\rm gap}
(
\mathcal X_{\rm gap}^{\rm native}
)
}.
}
$$

For finite equally weighted sets:

$$
\boxed{
G_{\rm gap}
=
1-
\frac{
|\mathcal X_{\rm gap}^{\rm SUN}|
}{
|\mathcal X_{\rm gap}^{\rm native}|
}.
}
$$

This measures the ability of SUN to illuminate:

* location;
* class;
* orientation;
* relation;
* or another preregistered gap property.

## X.B Conditional target-answer gain

After \(E_{\rm sel}\) has become public to both sides:

$$
\boxed{
G_T
=
1-
\frac{
\mathcal U_T
(
\mathcal C_{\rm SUN}^{\rm eval}
\mid E_{\rm sel}
)
}{
\mathcal U_T
(
\mathcal C_0^{\rm eval}
\mid E_{\rm sel}
)
}.
}
$$

The two gains must remain separate.

They may not be summed without a separately justified information measure.

---

# XI. FROZEN CANDIDATE-SEARCH PROGRAM

Alignment discovery itself is a selection mechanism.

It must therefore be registered.

Define

$$
\boxed{
u\sim\nu_0,
\qquad
D=\Sigma_0(u).
}
$$

The frozen empirical program must specify:

* candidate-system population;
* candidate sampling rule;
* alignment-search procedure;
* qualification criteria;
* exclusion criteria;
* anchor admissibility rules;
* gap-selection rule;
* and all stopping conditions.

Every screened candidate enters an immutable search ledger

$$
\boxed{
\mathcal J_0.
}
$$

The ledger records:

$$
\boxed{
\text{ALL CANDIDATES}
\rightarrow
\text{ALL DETECTED ANCHOR SETS}
\rightarrow
\text{ALL QUALIFYING REGISTRATIONS}
\rightarrow
\text{ALL GAP TARGETS}
\rightarrow
\text{ALL LICENSE DECISIONS}
\rightarrow
\text{ALL OUTCOMES}.
}
$$

Failed alignments may not disappear from the empirical record.

Nonqualifying systems may not disappear.

Licensed misses may not disappear.

Define at least the descriptive quantities

$$
\boxed{
P(
\mathsf{GapIlluminated}=1
\mid
\mathsf{AnchorQualified}=1
)
}
$$

and

$$
\boxed{
P(
\operatorname{Retain}_T=1
\mid
\mathsf L_{\rm SUN}=1
).
}
$$

These are distinct empirical questions.

---

# XII. COMPLETE PREREGISTRATION OBJECT

A prospective trial begins with

$$
\boxed{
\omega_0^{+}
=
\left(
\begin{array}{l}
D,
\mathscr D,
K_{\rm seen},
\mathcal L_{\rm anchor}^{(0)},
V_{\rm anchor},
\sim_{\rm anchor},
\rho_{\rm anchor},
\\
H_{\rm displacement}^{(0)},
\mathcal L_{\delta}^{(0)},
F_{\rm gap},
E_{\rm sel},
T,
\\
\mathcal L_\Gamma^{(0)},
\mathcal L_{\rm dep}^{(0)},
\mathcal L_K^{(0)},
\widehat\mu_T,
O,
\\
\approx_T^{\rm eval},
\mathcal U_T,
m_T,
\mathcal L_M^{(0)},
\mathcal L_G^{(0)},
\mathcal L_A^{(0)},
\Theta_0
\end{array}
\right).
}
$$

The semantic and verification package is

$$
\boxed{
\Theta_0
=
\left(
\begin{array}{l}
Y_D,
W_D,
V_D,
\mathsf{Elig}_D,
V_{\rm anchor},
V_\delta,
\\
\equiv_T^\Gamma,
\equiv_T^0,
\equiv_T,
\cong_T,
\mathcal V_0,
\\
\mathsf{RetainRule}_T,
\Psi_T^{(0)},
\ell_T
\end{array}
\right).
}
$$

No later certificate counts unless its verifier was frozen beforehand.

---

# XIII. TRUTH-ORACLE TYPES

SUN permits two kinds of truth acquisition.

## XIII.A Static truth oracle

For a truth already contained in a sealed dataset:

$$
\boxed{
\Gamma_{\rm static}(\mathscr D).
}
$$

## XIII.B Directed acquisition oracle

For predictions that direct later investigation, define

$$
\boxed{
\Gamma_{\rm search}
=
(
\mathscr S,
P_{\rm acq},
\tau_{\rm stop},
V_{\rm evidence},
E_{\rm adjudicate}
).
}
$$

Where:

$$
\mathscr S
$$

is the admissible search/source universe;

$$
P_{\rm acq}
$$

is the frozen acquisition procedure;

$$
\tau_{\rm stop}
$$

is the stopping rule;

$$
V_{\rm evidence}
$$

defines what evidence is admissible;
and

$$
E_{\rm adjudicate}
$$

maps acquired evidence to the target evaluation class or an explicit unresolved outcome.

Before commitment, freeze at minimum:

1. admissible databases, archives, physical regions, corpora, instruments, or source classes;
2. allowed search/query operations;
3. search ordering where relevant;
4. positive-hit criterion;
5. miss criterion;
6. contradictory-evidence procedure;
7. ambiguity procedure;
8. resource/time/source stopping rule;
9. adjudication rule.

Directed search may not continue indefinitely until compatible evidence appears.

If the stopping rule is reached without a decisive truth class, record

$$
\boxed{
\mathbf{SEARCH\mbox{-}EXHAUSTED\mbox{-}UNRESOLVED}.
}
$$

That result is not converted into confirmation.

---

# XIV. TRUTH-ORACLE CLOSURE

Define

$$
\boxed{
\mathfrak\Gamma_T^{(0)}
=
\{
\Gamma\in\mathcal L_\Gamma^{(0)}
:
Y_D(\Gamma)=1
\}.
}
$$

Require

$$
\boxed{
Q_T^\Gamma=1
}
$$

and one evaluation-equivalent oracle class:

$$
\boxed{
\left|
\mathfrak\Gamma_T^{(0)}
/
\!\equiv_T^\Gamma
\right|
=1.
}
$$

The target firewall is

$$
\boxed{
\Lambda_T^\star
=
\bigcup_{\Gamma\in\mathfrak\Gamma_T^{(0)}}
\operatorname{Dep}^{*}(\Gamma).
}
$$

For acquisition trials, this includes prereveal channels capable of leaking the eventual answer before commitment.

---

# XV. DISCOVERY CLOSURE

Expand

$$
\boxed{
K_{\rm seen}^{+}
=
\operatorname{Dep}^{*}_{\mathcal L_K^{(0)}}
(K_{\rm seen}).
}
$$

Require

$$
\boxed{
Q_K=1.
}
$$

The known anchors belong inside \(K_{\rm seen}^{+}\).

The registered target-selection event belongs inside \(K_{\rm seen}^{+}\).

Neither causes contamination merely by existing.

Discovery blindness fails only when the target evaluation class is already explicitly present or deterministically recoverable:

$$
\boxed{
\mathcal U_T(
T
\mid
K_{\rm seen}^{+},
E_{\rm sel}
)>0.
}
$$

Thus:

$$
\boxed{
\text{KNOWN REGISTRATION}
\neq
\text{KNOWN ANSWER}.
}
$$

---

# XVI. NATIVE-DOMAIN CLOSURE

SUN may not construct the native models.

Define

$$
\boxed{
\mathfrak M_D^{(0)}
=
\{
M\in\mathcal L_M^{(0)}
:
W_D(M)=1
\}.
}
$$

Require

$$
\boxed{
Q_D^M=1.
}
$$

For every \(M\),

$$
\boxed{
S_{E,M}^{(0)}
\mid E_{\rm sel}
}
$$

is constructed from native evidence and the publicly registered target identity.

Define

$$
\boxed{
\mathcal C_0(M\mid E_{\rm sel}).
}
$$

Native closure requires all admissible models to induce the same evaluation-level native target baseline.

Only then define

$$
\boxed{
\mathcal C_0^{\rm eval}(E_{\rm sel}).
}
$$

Require native headroom:

$$
\boxed{
H_D(T)
=
\mathbf1
\left[
0<
\mathcal U_T(
\mathcal C_0^{\rm eval}
\mid E_{\rm sel}
)
<\infty
\right].
}
$$

---

# XVII. COMPLETE SUN REALIZATION SPACE

Each complete realization extends one admissible partial registration.

Define

$$
\boxed{
\mathfrak R_D^{(0)}
=
\left\{
r=(M,G,A_{\rm anchor},A,\delta_\chi)
:
\begin{array}{l}
M\in\mathfrak M_D^{(0)},\\
A_{\rm anchor}\in\mathfrak A_D^{(0)},\\
G\in\mathfrak G_D^{(0)}(M),\\
A\text{ extends }A_{\rm anchor},\\
V_D(A\mid M,G)=1,\\
V_\delta(A,\delta_\chi)=1
\text{ when displacement is tested}
\end{array}
\right\}.
}
$$

Require

$$
\boxed{
Q_D^R=1.
}
$$

All admissible partial registrations must be extended or formally ruled out.

No preferred anchor map is silently chosen.

No preferred orientation is silently chosen.

No realization is discarded because it predicts the wrong outcome.

---

# XVIII. SUN-CONSTRAINED NATIVE STATES

For every realization \(r\),

$$
\boxed{
S_E^{(\rm SUN)}(r)
=
\{
s\in
S_{E,M}^{(0)}
\mid E_{\rm sel}
:
s\models A(G)
\}.
}
$$

Require

$$
\boxed{
S_E^{(\rm SUN)}(r)
\subseteq
S_{E,M}^{(0)}
\mid E_{\rm sel}.
}
$$

SUN may remove native possibilities.

It may not create them.

Require

$$
\boxed{
S_E^{(\rm SUN)}(r)\neq\varnothing.
}
$$

Define

$$
\boxed{
\mathcal C_{\rm SUN}(r)
=
T(S_E^{(\rm SUN)}(r)).
}
$$

---

# XIX. PREDICTIVE UNIQUENESS

For SET mode:

$$
\boxed{
r_i\equiv_T r_j
\iff
\mathcal C_{\rm SUN}^{\rm eval}(r_i)
=
\mathcal C_{\rm SUN}^{\rm eval}(r_j).
}
$$

A single confirmatory target prediction exists only when

$$
\boxed{
\left|
\mathfrak R_D^{(0)}
/
\!\equiv_T
\right|
=1.
}
$$

If exact coordinates remain ambiguous but every realization forces a property \(P\), then SUN predicts only

$$
\boxed{
P(z_{\rm true}).
}
$$

No stronger claim is permitted.

---

# XX. REGISTRATION REDUCTION

Let

$$
\mathfrak R_D^{\rm prior}
$$

be the admissible realization/orientation space before the qualifying anchor constraints are applied.

Let

$$
\mathfrak R_D^{\rm anchor}
$$

be the corresponding space after anchor closure.

Define

$$
\boxed{
\mathsf{RegistrationReduced}
=
\mathbf1
\left[
\mathfrak R_D^{\rm anchor}/\!\sim
\subsetneq
\mathfrak R_D^{\rm prior}/\!\sim
\right].
}
$$

This directly tests \(H_1\).

---

# XXI. GAP ILLUMINATION

Let

$$
\mathcal X_{\rm gap}^{0}
$$

be the native pre-SUN possibilities for the unresolved gap.

Let

$$
\boxed{
\mathcal X_{\rm gap}^{\rm SUN}
=
\bigcap_{r\in\mathfrak R_D^{(0)}}
\mathcal X_{\rm gap}(r).
}
$$

Define

$$
\boxed{
\mathsf{GapIlluminated}
=
\mathbf1
\left[
\mathcal X_{\rm gap}^{\rm SUN}
\subsetneq
\mathcal X_{\rm gap}^{0}
\right].
}
$$

Further distinguish:

$$
\boxed{
\mathsf{LocationGain}
}
$$

for contraction of possible locations,

and

$$
\boxed{
\mathsf{ClassGain}
}
$$

for contraction of possible native classes.

This directly tests \(H_2\).

---

# XXII. NONVACUOUS TARGET CONSTRAINT

For SET mode:

$$
\boxed{
\mathsf{ConstraintActive}
=
\mathbf1
\left[
\mathcal C_{\rm SUN}^{\rm eval}
\subsetneq
\mathcal C_0^{\rm eval}(E_{\rm sel})
\right].
}
$$

This is answer-level narrowing after both systems know which target is being tested.

Therefore:

$$
\boxed{
\mathsf{GapIlluminated}
}
$$

and

$$
\boxed{
\mathsf{ConstraintActive}
}
$$

are different.

SUN might successfully identify a promising gap yet add no information about its answer.

Or it might both identify the gap and constrain the answer.

---

# XXIII. COMPLETE INDIVIDUAL-TRIAL LICENSE

The confirmatory trial license is

$$
\boxed{
\mathsf L_{\rm SUN}(\omega_1)=1
}
$$

iff:

$$
\boxed{
\begin{aligned}
&D\in\mathfrak D_{\rm SUN}^{(0)}
\\
&\land\;Q_D^{\rm anchor}=1
\\
&\land\;\mathsf{AnchorClosed}=1
\\
&\land\;\mathsf{GapDerived}=1
\\
&\land\;\mathsf{OracleClosed}=1
\\
&\land\;Q_K=1
\\
&\land\;\mathsf{DiscoveryBlind}_T=1
\\
&\land\;\operatorname{NONINTERFERENCE}=1
\\
&\land\;\mathsf{NativeClosed}=1
\\
&\land\;H_D(T)=1
\\
&\land\;Q_D^R=1
\\
&\land\;\mathsf{RealizationClosed}=1
\\
&\land\;\mathsf{ConstraintActive}=1
\\
&\land\;
\forall r\in\mathfrak R_D^{(0)},
\quad
S_E^{(\rm SUN)}(r)\neq\varnothing.
\end{aligned}
}
$$

For a claim specifically invoking the triangulation/gap mechanism additionally require

$$
\boxed{
\rho_{\rm anchor}\ge\rho_{\rm preregistered}
}
$$

and

$$
\boxed{
\mathsf{RegistrationReduced}=1,
\qquad
\mathsf{GapIlluminated}=1.
}
$$

For a displacement claim additionally require the preregistered displacement test.

---

# XXIV. COMMITMENT

Before reveal freeze and immutably commit:

$$
\boxed{
\begin{array}{l}
\text{candidate identity},\\
\text{all observed anchors},\\
\text{complete admissible partial-registration space},\\
\text{anchor rank rule},\\
\text{candidate displacement law if tested},\\
\text{gap-selection event},\\
\text{target definition},\\
\text{native baseline conditioned on target selection},\\
\text{complete realization language},\\
\text{prediction equivalence},\\
\text{truth/acquisition protocol},\\
\text{search stopping rule},\\
\text{prediction object},\\
\text{scoring rules}.
\end{array}
}
$$

At commitment:

$$
\boxed{
\mathbf{MODELING\ STOPS}.
}
$$

No subsequent alteration is permitted to:

* anchors;
* anchor classification;
* displacement rule;
* gap;
* target;
* admissibility criteria;
* realization language;
* acquisition region;
* search procedure;
* stopping rule;
* evidence criterion;
* prediction;
* equivalence relation;
* or scoring rule.

---

# XXV. DIRECTED INVESTIGATION

After commitment:

$$
\boxed{
\text{SEARCHING WHERE SUN SAID TO LOOK IS PERMITTED}.
}
$$

For acquisition trials the permitted sequence is:

$$
\boxed{
\text{REGISTER}
\rightarrow
\text{DERIVE GAP}
\rightarrow
\text{PREDICT}
\rightarrow
\text{COMMIT}
\rightarrow
\text{SEARCH}
\rightarrow
\text{STOP BY RULE}
\rightarrow
\text{ADJUDICATE}.
}
$$

The forbidden sequence is:

$$
\boxed{
\text{SEARCH}
\rightarrow
\text{FIND SOMETHING INTERESTING}
\rightarrow
\text{ALTER REGISTRATION}
\rightarrow
\text{ALTER CLASS}
\rightarrow
\text{CALL IT THE PREDICTION}.
}
$$

---

# XXVI. REVEAL AND RETENTION

For a static trial:

$$
\boxed{
z_{\rm true}
=
\Gamma_{\rm static}(\mathscr D).
}
$$

For a directed-search trial:

$$
\boxed{
z_{\rm true}
=
\Gamma_{\rm search}
(
\text{acquired evidence before }\tau_{\rm stop}
).
}
$$

Reveal/adjudicate once.

No remapping follows.

For SET mode:

$$
\boxed{
\operatorname{Retain}_T
=
\mathbf1
\left[
[z_{\rm true}]_{\rm eval}
\in
\mathcal C_{\rm SUN}^{\rm eval}
\right].
}
$$

This directly tests \(H_3\).

---

# XXVII. OUTCOME TAXONOMY

A licensed triangulation trial can therefore produce diagnostically distinct results.

### Registration failure

$$
\boxed{
\mathsf{RegistrationReduced}=0.
}
$$

The anchors did not reduce orientation/registration uncertainty.

### Gap failure

$$
\boxed{
\mathsf{RegistrationReduced}=1
\land
\mathsf{GapIlluminated}=0.
}
$$

The system was registered, but no unresolved gap became more constrained.

### Noninformative target

$$
\boxed{
\mathsf{GapIlluminated}=1
\land
\mathsf{ConstraintActive}=0.
}
$$

SUN localized/classified the gap but did not narrow the answer after target selection was public.

### Licensed retained prediction

$$
\boxed{
\mathsf L_{\rm SUN}=1
\land
\operatorname{Retain}_T=1.
}
$$

### Licensed miss

$$
\boxed{
\mathsf L_{\rm SUN}=1
\land
\operatorname{Retain}_T=0.
}
$$

### Search exhausted without decisive reveal

$$
\boxed{
\mathbf{SEARCH\mbox{-}EXHAUSTED\mbox{-}UNRESOLVED}.
}
$$

This is neither silently discarded nor promoted to confirmation.

---

# XXVIII. POPULATION-LEVEL TESTS

The empirical program must separately measure:

$$
\boxed{
H_1:
\text{Do qualifying anchors reduce registration uncertainty?}
}
$$

$$
\boxed{
H_2:
\text{Does reduced registration illuminate genuinely unresolved gaps?}
}
$$

$$
\boxed{
H_3:
\text{Does reality subsequently fall inside those preregistered constraints?}
}
$$

The candidate-search ledger must allow estimation of:

$$
P(H_1\mid\text{screened candidate}),
$$

$$
P(H_2\mid H_1),
$$

and

$$
P(H_3\mid H_1,H_2,\mathsf L_{\rm SUN}=1).
$$

This prevents successful end cases from concealing a very low alignment-discovery or gap-illumination rate.

---

# XXIX. FULL FORMAL HYPOTHESIS FAMILY

SUN V1 C therefore distinguishes:

$$
\boxed{
H_{\rm grammar}
}
$$

the fixed SUN relational grammar;

$$
\boxed{
H_{\rm displacement}
}
$$

the existence of a stable class/address displacement law;

$$
\boxed{
H_{\rm triangulation}
}
$$

the ability of sufficiently independent anchors to constrain unresolved registration/gap structure;

$$
\boxed{
H_{\rm retention}
}
$$

the requirement that licensed predictions retain revealed reality;

and

$$
\boxed{
H_{\rm information}
}
$$

the requirement that SUN adds information beyond the properly conditioned native baseline.

The strongest overall claim is therefore not assumed monolithically.

It is:

$$
\boxed{
H_{\rm SUN}^{+}
=
H_{\rm grammar}
\land
H_{\rm displacement}
\land
H_{\rm triangulation}
\land
H_{\rm licensability}^{+}
\land
H_{\rm retention}
\land
H_{\rm information}.
}
$$

Failures identify which component failed.

---

# XXX. COMPACT SCIENTIFIC CLAIM

$$
\boxed{
\begin{gathered}
\textbf{SUN POSITS A FIXED DOMAIN-INDEPENDENT RELATIONAL GRAMMAR.}
\\[1mm]
\textbf{IT FURTHER TESTS WHETHER SUCCESSIVE GENERATIONS CARRY}
\\
\textbf{A STABLE, NONTRIVIAL CLASS/ADDRESS DISPLACEMENT DISTINCT}
\\
\textbf{FROM THE GENERATION COUNTER ITSELF.}
\\[1mm]
\textbf{WHEN MULTIPLE INDEPENDENT NATIVE RELATIONS REGISTER AGAINST}
\\
\textbf{THAT STRUCTURE, THEIR JOINT CONSTRAINTS MAY REDUCE THE}
\\
\textbf{ADMISSIBLE ORIENTATION AND REGISTRATION SPACE.}
\\[1mm]
\textbf{THAT REDUCTION MAY IN TURN IDENTIFY WHERE NATIVE STRUCTURE}
\\
\textbf{IS MISSING OR UNRESOLVED AND WHICH CLASSES OR PROPERTIES}
\\
\textbf{CAN CONSISTENTLY OCCUPY THE GAP.}
\\[1mm]
\textbf{THE RESULTING GAP MAY THEN BE TESTED BLINDLY BY A FROZEN}
\\
\textbf{STATIC OR DIRECTED-ACQUISITION PROTOCOL.}
\\[1mm]
\textbf{ALL CANDIDATES, FAILURES, REGISTRATIONS, PREDICTIONS, SEARCH}
\\
\textbf{PATHS, AND OUTCOMES REMAIN IN THE EMPIRICAL RECORD.}
\\[1mm]
\textbf{A LICENSED PREDICTION COUNTS ONLY WHEN IT NARROWS POSSIBILITY}
\\
\textbf{BEYOND A NATIVE BASELINE GIVEN THE SAME TARGET-SELECTION EVENT,}
\\
\textbf{AND THE SUBSEQUENTLY REVEALED REALITY REMAINS INSIDE THAT}
\\
\textbf{PREREGISTERED POSSIBILITY SET WITHOUT REMAPPING.}
\end{gathered}
}
$$

---

# XXXI. OPERATIONAL PROTOCOL

The complete application sequence is:

$$
\boxed{
\begin{array}{c}
\textbf{SCREEN CANDIDATE SYSTEMS UNDER A FROZEN SEARCH RULE}
\\
\downarrow
\\
\textbf{RECORD EVERY CANDIDATE, INCLUDING FAILURES}
\\
\downarrow
\\
\textbf{IDENTIFY ALL ADMISSIBLE PARTIAL REGISTRATIONS}
\\
\downarrow
\\
\textbf{CERTIFY ANCHOR CONSTRAINT RANK}
\\
\downarrow
\\
\textbf{TEST RELATIONAL AND, WHERE REGISTERED, CLASS-DISPLACEMENT CONSISTENCY}
\\
\downarrow
\\
\textbf{MEASURE WHETHER THE ANCHORS REDUCE REGISTRATION UNCERTAINTY}
\\
\downarrow
\\
\textbf{DERIVE THE UNRESOLVED GAP USING THE FROZEN GAP RULE}
\\
\downarrow
\\
\textbf{REGISTER THE TARGET-SELECTION EVENT}
\\
\downarrow
\\
\textbf{GIVE THAT SAME TARGET IDENTITY TO THE NATIVE BASELINE}
\\
\downarrow
\\
\textbf{VERIFY THAT THE TARGET TRUTH REMAINS HIDDEN}
\\
\downarrow
\\
\textbf{EXHAUST NATIVE MODELS}
\\
\downarrow
\\
\textbf{EXHAUST ALL SUN REALIZATIONS EXTENDING ALL SURVIVING ANCHOR MAPS}
\\
\downarrow
\\
\textbf{INTERSECT THEIR FORCED GAP/TARGET CONSEQUENCES}
\\
\downarrow\\
\textbf{MEASURE GAP GAIN AND CONDITIONAL TARGET GAIN SEPARATELY}
\\
\downarrow
\\
\textbf{FREEZE THE STATIC OR DIRECTED-SEARCH TRUTH PROTOCOL}
\\
\downarrow
\\
\textbf{COMMIT THE PREDICTION}
\\
\downarrow
\\
\boxed{\mathbf{MODELING\ STOPS}}
\\
\downarrow
\\
\textbf{SEARCH THE PREDICTED GAP IF DIRECTED ACQUISITION IS REQUIRED}
\\
\downarrow
\\
\textbf{STOP BY THE PREREGISTERED RULE}
\\
\downarrow
\\
\textbf{REVEAL / ADJUDICATE ONCE}
\\
\downarrow
\\
\textbf{SCORE H1, H2, H3, RETENTION, AND INFORMATION GAIN SEPARATELY}
\end{array}
}
$$

The central methodological principle is:

$$
\boxed{
\textbf{KNOWN STRUCTURE MAY ORIENT THE SEARCH.}
}
$$

$$
\boxed{
\textbf{ORIENTATION MAY IDENTIFY THE GAP.}
}
$$

$$
\boxed{
\textbf{A GAP MAY BECOME A PREDICTION TARGET.}
}
$$

$$
\boxed{
\textbf{BUT THE TARGET'S TRUTH MUST STILL BE UNKNOWN,}
\atop
\textbf{AND EVERY DEGREE OF FREEDOM MUST BE FROZEN BEFORE LOOKING.}
}
$$