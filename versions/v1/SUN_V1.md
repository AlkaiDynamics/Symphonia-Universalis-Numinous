SUN V1

The full hypothesis becomes a conjunction of four clauses rather than the earlier three:

$$ \boxed{ H_{\rm SUN} = H_{\rm grammar} \;\land\; H_{\rm licensability} \;\land\; H_{\rm retention} \;\land\; H_{\rm information}. } $$

The added clause,

$$ \boxed{H_{\rm licensability}}, $$

is necessary because SUN now makes an empirical claim only about trials for which blindness, closure, exhaustion, and scoring are demonstrably valid.

I. THE STRUCTURAL HYPOTHESIS

Define the SUN relational grammar

$$ \boxed{ \mathcal G_{\rm SUN} = (R,L,\mathcal C,\mathcal B,\mathcal I,h,g). } $$

Its ordinary recursive transition cell is

$$ \boxed{ C_n \longrightarrow \{R(C_n),L(C_n)\} \longrightarrow C_{n+1} } $$

for exactly three ordinary generations:

$$ \boxed{ C_0\to C_1\to C_2\to C_3. } $$

These are followed by a structurally distinct boundary operation

$$ \boxed{ C_3\xrightarrow{\mathcal B}C_4. } $$

The canonical harmonic realization is

$$ \boxed{ R=\frac23, \qquad L=\frac34, \qquad RL=\frac12, } $$

with inverse orientation

$$ \boxed{ R^{-1}=\frac32, \qquad L^{-1}=\frac43, \qquad R^{-1}L^{-1}=2. } $$

Hence

$$ \boxed{ \left(\frac23,\frac34\right)^{-1} = \left(\frac32,\frac43\right). } $$

The boundary satisfies local invariant preservation

$$ \boxed{ \mathcal I(\mathcal Bs)=\mathcal I(s) } $$

without global-state identity:

$$ \boxed{ \mathcal Bs\neq s. } $$

In the canonical register realization,

$$ \boxed{ g(\mathcal Bs)=g(s)+1. } $$

Completed Harmony gives the canonical local closure

$$ \boxed{ \frac{16}{15}\frac{15}{16}=1, } $$

while permitting

$$ \boxed{ \Delta g=+1. } $$

Therefore SUN's primary transition invariant is

$$ \boxed{ \text{LOCAL RELATIONAL CLOSURE} \not\Rightarrow \text{GLOBAL-STATE CLOSURE}. } $$

SUN also permits observational equivalence without provenance equivalence:

$$ \Phi(s_A)=\Phi(s_B), $$

possibly together with

$$ \mathcal I(s_A)=\mathcal I(s_B), $$

while

$$ \boxed{ (h_A,g_A)\neq(h_B,g_B). } $$

Therefore

$$ \boxed{ \text{SAME OBSERVABLE RELATION} \neq \text{SAME HIDDEN PATH/REGISTER}. } $$

Whenever hidden provenance is causally operative,

$$ \boxed{ \operatorname{Post}^{+}(s_A) \not\sim \operatorname{Post}^{+}(s_B) } $$

may follow even when the present observable states coincide.

Thus:

$$ \boxed{ \begin{aligned} H_{\rm grammar}:\quad \exists\,\mathcal G_{\rm SUN}\text{ such that }& \\ &\mathcal G_{\rm SUN} \text{ is a domain-independent relational transition grammar} \\ &\text{containing complementary generation, recursive closure,} \\ &\text{a distinguished boundary class preserving a local invariant} \\ &\text{while permitting genuine displacement of global state/register,} \\ &\text{and hidden path/register can constrain subsequent reachability} \\ &\text{whenever that hidden provenance is causally operative.} \end{aligned} } $$
II. THE PREREGISTERED TRIAL OBJECT

A trial begins not with a completed experiment but with a preregistration record

$$ \boxed{ \omega_0 = \left( D, \mathscr D, K_{\rm seen}, T, \mathcal L_\Gamma^{(0)}, \mathcal L_{\rm dep}^{(0)}, \mathcal L_K^{(0)}, \widehat\mu_T, O, \approx_T^{\rm eval}, \mathcal U_T, m_T, \mathcal L_M^{(0)}, \mathcal L_G^{(0)}, \mathcal L_A^{(0)}, \Sigma_0 \right). } $$

Here:

$$ D $$

is the candidate domain;

$$ \mathscr D $$

is the immutable dataset snapshot;

$$ K_{\rm seen} $$

is the complete registered discovery-contamination ledger;

$$ T $$

is the held-out target;

$$ \mathcal L_\Gamma^{(0)} $$

is the frozen truth-oracle language;

$$ \mathcal L_{\rm dep}^{(0)} $$

is the frozen dependency language;

$$ \mathcal L_K^{(0)} $$

is the frozen discovery-inference language;

$$ \widehat\mu_T $$

is the frozen mask constructor;

$$ O $$

is the frozen observation/preprocessing operator;

$$ \approx_T^{\rm eval} $$

is the empirical evaluation equivalence;

$$ \mathcal U_T $$

is the registered uncertainty functional when the target is set-valued;

$$ m_T\in \{\mathrm{SET},\mathrm{PROBABILISTIC}\} $$

is the prediction mode;

and

$$ \Sigma_0 $$

is the immutable trial-selection mechanism generating

$$ \boxed{ \omega_0\sim\Pi_0. } $$

Therefore the population being tested is explicitly

$$ \boxed{ \Pi_0=\operatorname{Law}(\Sigma_0). } $$

Neither \(\Sigma_0\) nor \(\Pi_0\) may change after outcomes are observed.

III. CERTIFIED EXHAUSTION

Every closure assertion must carry a machine-verifiable certificate.

For every relevant search space \(X\),

$$ \boxed{ Q_X=1 \iff \exists\,\pi_X: \operatorname{Verify}_X(\pi_X)=1. } $$

The corresponding closure state is

$$ \boxed{ \operatorname{ClosureStatus}(X)= \begin{cases} \mathbf{UNEXHAUSTED}, &Q_X=0, \\[1mm] \mathbf{EMPTY}, &Q_X=1\land|X/\!\sim|=0, \\[1mm] \mathbf{UNIQUE}, &Q_X=1\land|X/\!\sim|=1, \\[1mm] \mathbf{NONUNIQUE}, &Q_X=1\land|X/\!\sim|>1. \end{cases} } $$

Hence

$$ \boxed{ \mathbf{UNEXHAUSTED} \neq \mathbf{EMPTY} \neq \mathbf{NONUNIQUE} \neq \mathbf{GAUGE\mbox{-}EQUIVALENT}. } $$
IV. TRUTH-ORACLE CLOSURE

The admissible truth extractors are

$$ \boxed{ \mathfrak\Gamma_T^{(0)} = \{ \Gamma\in\mathcal L_\Gamma^{(0)} : Y_D(\Gamma)=1 \}. } $$

Oracle closure requires

$$ \boxed{ Q_T^\Gamma=1 } $$

and

$$ \boxed{ \left| \mathfrak\Gamma_T^{(0)} / \!\equiv_T^\Gamma \right| =1. } $$

Define

$$ \boxed{ \mathsf{OracleClosed} \iff \operatorname{ClosureStatus} (\mathfrak\Gamma_T^{(0)}) = \mathbf{UNIQUE}. } $$

Because equivalent truth oracles may have different dependencies, the leakage closure is not defined from an arbitrary representative.

Instead:

$$ \boxed{ \Lambda_T^\star = \bigcup_{\Gamma\in\mathfrak\Gamma_T^{(0)}} \operatorname{Dep}^{*}_{\mathcal L_{\rm dep}^{(0)}}(\Gamma). } $$

This is the complete target-information firewall.

V. DISCOVERY-CONTAMINATION CLOSURE

Expand the discovery ledger under the frozen admissible inference language:

$$ \boxed{ K_{\rm seen}^{+} = \operatorname{Dep}^{*}_{\mathcal L_K^{(0)}}(K_{\rm seen}). } $$

Its completeness must itself be certified:

$$ \boxed{ Q_K=1 \iff \exists\pi_K: \operatorname{Verify}_K(\pi_K)=1. } $$

Define:

$$ \boxed{ \mathsf{DiscoveryBlind}_T(K_{\rm seen}^{+})=1 } $$

iff the target evaluation class is neither explicitly present in nor deterministically recoverable from \(K_{\rm seen}^{+}\) under the frozen discovery-inference language.

Equivalently, discovery information must leave nonzero uncertainty about the target:

$$ \boxed{ \mathcal U_T \left( T\mid K_{\rm seen}^{+} \right)>0 } $$

for set-valued trials, or the corresponding frozen nonrecoverability criterion for probabilistic trials.

Thus previously observed SUN-like features may motivate \(D\), but cannot themselves constitute confirmation.

VI. MASKING AND NONINTERFERENCE

Instantiate the mask only after oracle closure:

$$ \boxed{ \mu_T^\star = \widehat\mu_T(\Lambda_T^\star). } $$

The visible dataset is

$$ \boxed{ \mathscr D_{\rm vis} = \mu_T^\star(\mathscr D). } $$

The confirmatory evidence is

$$ \boxed{ E_T = O(\mathscr D_{\rm vis}). } $$

The truth channel remains separate:

$$ \boxed{ z_{\rm true} = \Gamma(\mathscr D), \qquad \Gamma\in\mathfrak\Gamma_T^{(0)}, } $$

where all admissible \(\Gamma\)'s agree under

$$ \approx_T^{\rm eval}. $$

The preprocessing channel must satisfy

$$ \boxed{ d|_{\neg\Lambda_T^\star} = d'|_{\neg\Lambda_T^\star} \Longrightarrow O(\mu_T^\star(d)) = O(\mu_T^\star(d')). } $$

And this too requires certification:

$$ \boxed{ \operatorname{NONINTERFERENCE}=1 \iff \exists\pi_{\rm NI}: \operatorname{Verify}_{\rm NI} ( \pi_{\rm NI}, \mu_T^\star, O, \Lambda_T^\star )=1. } $$

After these quantities are mechanically instantiated, the sealed trial becomes

$$ \boxed{ \omega_1 = \omega_0 \cup \{ \mathfrak\Gamma_T^{(0)}, \Lambda_T^\star, K_{\rm seen}^{+}, \mu_T^\star \}. } $$
VII. NATIVE-DOMAIN CLOSURE

Construct the admissible native models without SUN:

$$ \boxed{ \mathfrak M_D^{(0)} = \{ M\in\mathcal L_M^{(0)}(D): W_D(M)=1 \}. } $$

Require certified exhaustion:

$$ \boxed{ Q_D^M=1. } $$

And target-baseline equivalence:

$$ \boxed{ \left| \mathfrak M_D^{(0)} / \!\equiv_T^0 \right| =1. } $$

Therefore

$$ \boxed{ \mathsf{NativeClosed} \iff \operatorname{ClosureStatus} (\mathfrak M_D^{(0)}) = \mathbf{UNIQUE}. } $$

From visible evidence define the unconstrained native state space

$$ \boxed{ S_E^{(0)} = \{ s: s\models M, \; s\models E_T \}. } $$

Its target projection is

$$ \boxed{ \mathcal C_0 = T(S_E^{(0)}). } $$

For set-valued targets:

$$ \boxed{ \mathcal C_0^{\rm eval} = \mathcal C_0/\!\approx_T^{\rm eval}. } $$

Predictive headroom requires

$$ \boxed{ H_D(T)=1. } $$

For set-valued trials:

$$ \boxed{ H_D(T) = \mathbf 1 \left[ 0< \mathcal U_T(\mathcal C_0^{\rm eval}) < \infty \right]. } $$

If not:

$$ \boxed{\mathbf{NO\mbox{-}HEADROOM}.} $$
VIII. SUN REALIZATION CLOSURE

Only after native headroom survives may SUN be applied.

Let

$$ \mathfrak G_D^{(0)}(M) \subseteq \mathcal L_G^{(0)} $$

be the permitted SUN subgrammars legitimately testable by native domain \(D\).

The complete realization space is

$$ \boxed{ \mathfrak R_D^{(0)} = \left\{ r=(M,G,A): \begin{array}{l} M\in\mathfrak M_D^{(0)}, \\ G\in\mathfrak G_D^{(0)}(M), \\ A\in\mathcal L_A^{(0)}(M,G), \\ V_D(A\mid M,G)=1 \end{array} \right\}. } $$

Each adapter must preserve all frozen types, transformations, compositions, distinctions, and invariants.

For example:

$$ \boxed{ A\circ R = R_D\circ A, } $$ $$ \boxed{ A\circ L = L_D\circ A, } $$

and where applicable,

$$ \boxed{ A(RL) = R_DL_DA. } $$

Realization exhaustion requires

$$ \boxed{ Q_D^R=1. } $$

Prediction equivalence is

$$ \boxed{ r_i\equiv_T r_j } $$

iff their committed empirical target predictions are identical under

$$ \approx_T^{\rm eval}. $$

A single SUN prediction is licensed only if

$$ \boxed{ \left| \mathfrak R_D^{(0)} / \!\equiv_T \right| =1. } $$

Thus

$$ \boxed{ \mathsf{RealizationClosed} \iff \operatorname{ClosureStatus} (\mathfrak R_D^{(0)}) = \mathbf{UNIQUE}. } $$

If exhaustive search returns

$$ |\mathfrak R_D^{(0)}|=0, $$

the result is explicitly

$$ \boxed{\mathbf{NO\mbox{-}REALIZATION},} $$

not underdetermination.

IX. SUN-CONSTRAINED STATE SPACE

For realization \(r=(M,G,A)\),

$$ \boxed{ S_E^{(\rm SUN)}(r) = \{ s\in S_E^{(0)}: s\models A(G) \}. } $$

SUN must constrain rather than enlarge the native state space:

$$ \boxed{ S_E^{(\rm SUN)}(r) \subseteq S_E^{(0)}. } $$

And every prediction-equivalent admissible realization must remain nonempty:

$$ \boxed{ S_E^{(\rm SUN)}(r)\neq\varnothing. } $$

Otherwise:

$$ \boxed{\mathbf{PREREVEAL\mbox{-}INCONSISTENT}.} $$

Its target consequence is

$$ \boxed{ \mathcal C_{\rm SUN}(r) = T(S_E^{(\rm SUN)}(r)). } $$

Because realization closure requires prediction equivalence, these induce one empirical prediction class:

$$ \boxed{ \mathcal C_{\rm SUN}^{\rm eval}. } $$

Exact target determination is not mandatory.

SUN may instead force a weaker property \(P\):

$$ \boxed{ \forall z\in \mathcal C_{\rm SUN}, \qquad P(z). } $$

Then \(P\), and only \(P\), is the registered prediction.

X. REALIZATION-SPECIFIC GAUGE

For each complete realization

$$ r=(M,G,A), $$

define

$$ \boxed{ G_E(r) = \operatorname{Aut} ( M, A(G), E_T ). } $$

Gauge symmetry is not empirical evaluation equivalence.

Thus:

$$ \boxed{ G_E(r) \text{ governs inferential identifiability;} } $$

while

$$ \boxed{ \approx_T^{\rm eval} \text{ governs empirical scoring.} } $$

If SUN makes the stronger statement that a target is determined up to genuine conditioned symmetry, require cross-realization gauge coherence:

$$ \boxed{ \left| \left\{ T(S_E^{(\rm SUN)}(r))/G_E(r): r\in\mathfrak R_D^{(0)} \right\} /\!\cong_T \right| =1. } $$

Without this condition, SUN may still issue its common empirical evaluation-class prediction, but may not claim unique determination up to gauge.

XI. THE COMPLETE LICENSE PREDICATE

The SUN confirmatory license is now stage-correct:

$$ \boxed{ \mathsf L_{\rm SUN}(\omega_1)=1 } $$

iff

$$ \boxed{ \begin{aligned} &D\in\mathfrak D_{\rm SUN}^{(0)} \\ &\land\; \mathsf{OracleClosed} \\ &\land\; Q_K=1 \\ &\land\; \mathsf{DiscoveryBlind}_T(K_{\rm seen}^{+})=1 \\ &\land\; \operatorname{NONINTERFERENCE} ( \mu_T^\star,O,\Lambda_T^\star )=1 \\ &\land\; \mathsf{NativeClosed} \\ &\land\; H_D(T)=1 \\ &\land\; \mathsf{RealizationClosed} \\ &\land\; \forall r\in\mathfrak R_D^{(0)}, \quad S_E^{(\rm SUN)}(r)\neq\varnothing. \end{aligned} } $$

No empirical SUN prediction exists unless

$$ \boxed{ \mathsf L_{\rm SUN}=1. } $$
XII. COMMITMENT AND REVEAL

Before truth is revealed, SUN commits to its complete prediction object:

$$ \boxed{ \mathcal P_{\rm SUN}^{(0)} } $$

where

$$ \mathcal P_{\rm SUN}^{(0)} = \begin{cases} \mathcal C_{\rm SUN}^{\rm eval}, &m_T=\mathrm{SET}, \\ P_{\rm SUN}, &m_T=\mathrm{PROBABILISTIC}. \end{cases} $$

The commitment must be immutable and externally auditable.

Only then evaluate:

$$ \boxed{ z_{\rm true} = \Gamma(\mathscr D). } $$

No change is permitted after commitment to:

$$ \boxed{ T,\Gamma,\Lambda^\star,\mu^\star,O, \approx_T^{\rm eval}, \mathcal U_T, M,G,A, \Sigma_0, \text{ or scoring rule}. } $$
XIII. RETENTION HYPOTHESIS

For set-valued targets:

$$ \boxed{ \operatorname{Retain}_T = \mathbf1 \left[ [z_{\rm true}]_{\rm eval} \in \mathcal C_{\rm SUN}^{\rm eval} \right]. } $$

For probabilistic predictions, retention is defined by the preregistered support/admissibility rule rather than set membership.

The universal retention clause is

$$ \boxed{ H_{\rm retention}: \quad \forall\omega_1\in\operatorname{supp}(\Pi_0), \quad \mathsf L_{\rm SUN}(\omega_1)=1 \Longrightarrow \operatorname{Retain}_T(\omega_1)=1. } $$

Therefore one licensed trial satisfying

$$ \boxed{ \operatorname{Retain}_T=0 } $$

falsifies

$$ \boxed{ H_{\rm retention}. } $$

No remapping is permitted.

XIV. INFORMATION-GAIN HYPOTHESIS

Define one typed information-gain variable

$$ \boxed{ G_T(\omega). } $$

For

$$ m_T=\mathrm{SET}, $$

require an admissible monotone uncertainty functional:

$$ A\subseteq B \Longrightarrow \mathcal U_T(A) \le \mathcal U_T(B), $$

and define

$$ \boxed{ G_T = 1- \frac{ \mathcal U_T ( \mathcal C_{\rm SUN}^{\rm eval} ) }{ \mathcal U_T ( \mathcal C_0^{\rm eval} ) }. } $$

For finite equally weighted targets,

$$ \boxed{ G_T = 1- \frac{ |\mathcal C_{\rm SUN}^{\rm eval}| }{ |\mathcal C_0^{\rm eval}| }. } $$

For

$$ m_T=\mathrm{PROBABILISTIC}, $$

freeze a strictly proper loss

$$ \ell_T $$

before reveal and define

$$ \boxed{ G_T = \ell_T ( P_{\rm native},z_{\rm true} ) - \ell_T ( P_{\rm SUN},z_{\rm true} ). } $$

Thus in every mode:

$$ \boxed{ G_T>0 } $$

means SUN contributed positive held-out information, while

$$ \boxed{ G_T\le0 } $$

means it did not.

The population claim is non-vacuous only if

$$ \boxed{ \Pr_{\omega\sim\Pi_0} [ \mathsf L_{\rm SUN}(\omega)=1 ] >0. } $$

Therefore:

$$ \boxed{ H_{\rm information}: \quad \Pr_{\Pi_0}[\mathsf L_{\rm SUN}=1]>0 \quad\land\quad \mathbb E_{\omega\sim\Pi_0} \left[ G_T(\omega) \mid \mathsf L_{\rm SUN}(\omega)=1 \right] >0. } $$

This claim applies only to the trial population generated by the frozen

$$ \boxed{\Sigma_0.} $$
XV. LICENSABILITY HYPOTHESIS

The new clause is:

$$ \boxed{ H_{\rm licensability}: \quad \Pr_{\omega\sim\Pi_0} [ \mathsf L_{\rm SUN}(\omega)=1 ] >0. } $$

This is worth making explicit rather than burying it inside \(H_{\rm information}\).

Otherwise a purported universal grammar could evade empirical evaluation by producing no valid prediction on any target.

SUN therefore asserts not merely that its grammar exists, but that it can generate at least some nonempty class of closed, blind, genuinely predictive experiments.

XVI. FULL FORMALIZED SUN HYPOTHESIS

The final hypothesis is therefore:

$$ \boxed{ \begin{aligned} \mathbf H_{\rm SUN}:\qquad & \exists\, \mathcal G_{\rm SUN} = (R,L,\mathcal C,\mathcal B,\mathcal I,h,g) \\ &\text{constituting a domain-independent relational transition grammar} \\ &\text{with complementary generation, three ordinary recursive transitions,} \\ &\text{and a distinguished boundary transition capable of preserving} \\ &\text{a local relational invariant while changing global state/register;} \\ &\text{the grammar permits observationally equivalent states with} \\ &\text{inequivalent hidden provenance, and where that provenance is causally} \\ &\text{operative it constrains subsequent reachability;} \\[2mm] & \text{and there exists a preregistered trial population } \Pi_0=\operatorname{Law}(\Sigma_0) \\ &\text{generated by a frozen selection mechanism }\Sigma_0, \text{ for which all target oracles,} \\ &\text{dependency closures, discovery exposures, preprocessing rules, native models,} \\ &\text{SUN subgrammars, adapters, equivalence relations, uncertainty measures,} \\ &\text{prediction modes, and scoring rules are frozen independently of outcomes;} \\[2mm] & \text{and every exhaustion or noninterference assertion required for licensing} \\ &\text{is backed by a mechanically verifiable certificate;} \\[2mm] & \Pr_{\omega\sim\Pi_0} [ \mathsf L_{\rm SUN}(\omega)=1 ] >0; \\[2mm] & \forall\omega\in\operatorname{supp}(\Pi_0), \quad \mathsf L_{\rm SUN}(\omega)=1 \\ &\qquad\Longrightarrow \operatorname{Retain}_T(\omega)=1; \\[2mm] & \mathbb E_{\omega\sim\Pi_0} \left[ G_T(\omega) \mid \mathsf L_{\rm SUN}(\omega)=1 \right] >0. \end{aligned} } $$

Equivalently:

$$ \boxed{ H_{\rm SUN} = H_{\rm grammar} \land H_{\rm licensability} \land H_{\rm retention} \land H_{\rm information}. } $$

Its empirical success event for an individual licensed trial is exactly

$$ \boxed{ \mathsf L_{\rm SUN}(\omega)=1 \;\land\; \operatorname{Retain}_T(\omega)=1 \;\land\; G_T(\omega)>0. } $$

Its individual-trial falsifier for the universal retention claim is exactly

$$ \boxed{ \mathsf L_{\rm SUN}(\omega)=1 \;\land\; \operatorname{Retain}_T(\omega)=0. } $$

Its population information claim fails when

$$ \boxed{ \Pr_{\Pi_0}[\mathsf L_{\rm SUN}=1]=0 } $$

or

$$ \boxed{ \mathbb E \left[ G_T \mid \mathsf L_{\rm SUN}=1 \right] \le0. } $$

And its strongest compact scientific statement is:

$$ \boxed{ \begin{gathered} \textbf{A FIXED DOMAIN-INDEPENDENT RELATIONAL GRAMMAR EXISTS.} \\[1mm] \textbf{IT CAN GENERATE BLIND, CLOSED, NONVACUOUS EMPIRICAL PREDICTIONS.} \\[1mm] \textbf{ON EVERY LICENSED TRIAL, ITS CONSTRAINTS RETAIN THE HELD-OUT REALITY.} \\[1mm] \textbf{ACROSS THE FROZEN TRIAL POPULATION, THOSE CONSTRAINTS REDUCE} \\ \textbf{HELD-OUT UNCERTAINTY BEYOND THE INFORMATION ALREADY AVAILABLE} \\ \textbf{TO THE NATIVE DOMAIN MODEL.} \end{gathered} } $$

Or at maximum compression:

$$ \boxed{ \textbf{RELATIONAL GRAMMAR CONSTRAINS UNSEEN POSSIBILITY SPACE} } $$
IN A BLIND, EXHAUSTIVE, REALITY-RETAINING, INFORMATION-POSITIVE WAY.
	​

The governing rule is:

$$ \boxed{ \textbf{DO NOT ASK WHETHER THE CANDIDATE LOOKS LIKE SUN.} } $$

Ask:

$$ \boxed{ \textbf{AFTER REMOVING EVERYTHING THAT MADE US SUSPECT SUN,} \atop \textbf{WHAT PREVIOUSLY UNRESOLVED FACT DOES SUN FORCE?} } $$

The application procedure is:

Quarantine the discovery. Record exhaustively
$$ \boxed{ K_{\rm seen} = \{\text{everything already known that suggested SUN}\}. } $$

If \(72\), \(2/3\), \(3/4\), pairing, three generations, a \(3+1\) pattern, boundary behavior, local closure, register displacement, etc. caused the candidate to be noticed, none of those observations can later count as confirmation.

Certify the discovery ledger:

$$ \boxed{ Q_K=1. } $$

Then compute its frozen inferential closure:

$$ \boxed{ K_{\rm seen}^{+} = \operatorname{Dep}^{*}_{\mathcal L_K^{(0)}}(K_{\rm seen}). } $$
Test native eligibility before mapping SUN. Define \(D\) entirely in its own disciplinary language. It must independently contain objects capable of supporting a relational test: states/roles, transformations, composition, observables, invariants, boundaries or transitions, and an unresolved target.

Test:

$$ \boxed{ D\in\mathfrak D_{\rm SUN}^{(0)}. } $$

If SUN terminology is required merely to construct the native system, terminate:

$$ \boxed{\mathbf{INELIGIBLE}.} $$
Preregister the experiment. Before reconstructing SUN inside \(D\), freeze
$$ \boxed{ \omega_0= ( D,\mathscr D,K_{\rm seen},T, \mathcal L_\Gamma^{(0)}, \mathcal L_{\rm dep}^{(0)}, \mathcal L_K^{(0)}, \widehat\mu_T, O, \approx_T^{\rm eval}, \mathcal U_T, m_T, \mathcal L_M^{(0)}, \mathcal L_G^{(0)}, \mathcal L_A^{(0)}, \Sigma_0 ). } $$

Most importantly, freeze the hidden target

$$ \boxed{ T:X_D\rightarrow Z_T. } $$

The target could be a missing node, next transition, boundary position, operator class, hidden provenance, future state, fiber membership, etc.

It must not have been chosen because its answer is already known.

Close the truth oracle first. Enumerate every admissible way to obtain the true target from the immutable dataset:
$$ \boxed{ \mathfrak\Gamma_T^{(0)} = \{ \Gamma\in\mathcal L_\Gamma^{(0)} :Y_D(\Gamma)=1 \}. } $$

Require certified exhaustion and one evaluation-equivalent truth:

$$ \boxed{ Q_T^\Gamma=1, \qquad \left| \mathfrak\Gamma_T^{(0)}/\!\equiv_T^\Gamma \right|=1. } $$

Do not select a favorite oracle.

If exhaustive closure has not been proved, stop as UNEXHAUSTED. If no valid oracle exists, stop as EMPTY/UNSCORABLE TARGET. If inequivalent truths remain, stop as NONUNIQUE.

Construct the complete target leakage firewall. Because equivalent truth oracles can depend on different raw data, mask the union of every admissible dependency:
$$ \boxed{ \Lambda_T^\star = \bigcup_{\Gamma\in\mathfrak\Gamma_T^{(0)}} \operatorname{Dep}^{*}_{\mathcal L_{\rm dep}^{(0)}}(\Gamma). } $$

This is everything through which the held-out answer could leak.

Prove discovery blindness. With the target now formally defined, test whether \(K_{\rm seen}^{+}\) already determines its evaluation class:
$$ \boxed{ \mathsf{DiscoveryBlind}_T(K_{\rm seen}^{+})=1. } $$

For a finite set-valued target, equivalently require residual uncertainty:

$$ \boxed{ \mathcal U_T(T\mid K_{\rm seen}^{+})>0. } $$

If the answer or a deterministic proxy was already available during discovery:

$$ \boxed{\mathbf{DISCOVERY\mbox{-}CONTAMINATED}.} $$

That candidate may remain useful exploratorily, but not as a confirmatory SUN test for that target.

Instantiate the mask and prove noninterference. Apply the frozen mask constructor:
$$ \boxed{ \mu_T^\star = \widehat\mu_T(\Lambda_T^\star). } $$

Then:

$$ \boxed{ \mathscr D_{\rm vis} = \mu_T^\star(\mathscr D), } $$ $$ \boxed{ E_T = O(\mathscr D_{\rm vis}). } $$

The preprocessing channel must satisfy:

$$ \boxed{ d|_{\neg\Lambda_T^\star} = d'|_{\neg\Lambda_T^\star} \Longrightarrow O(\mu_T^\star(d)) = O(\mu_T^\star(d')). } $$

Require a verification certificate

$$ \boxed{ \exists\pi_{\rm NI}: \operatorname{Verify}_{\rm NI}(\pi_{\rm NI})=1. } $$

Otherwise:

$$ \boxed{\mathbf{LEAKAGE}.} $$
Build the domain without SUN. Construct every admissible native model:
$$ \boxed{ \mathfrak M_D^{(0)} = \{ M\in\mathcal L_M^{(0)}: W_D(M)=1 \}. } $$

Exhaust them:

$$ \boxed{ Q_D^M=1. } $$

Require them to induce one target baseline:

$$ \boxed{ \left| \mathfrak M_D^{(0)}/\!\equiv_T^0 \right| =1. } $$

This prevents selecting whichever native representation later makes SUN look strongest.

Measure what the native domain already determines. From only the permitted visible evidence:
$$ \boxed{ S_E^{(0)} = \{s:s\models M,\ s\models E_T\}. } $$

Project onto the target:

$$ \boxed{ \mathcal C_0 = T(S_E^{(0)}). } $$

For set-valued scoring:

$$ \boxed{ \mathcal C_0^{\rm eval} = \mathcal C_0/\!\approx_T^{\rm eval}. } $$

Now calculate headroom.

For the set case:

$$ \boxed{ H_D(T) = \mathbf1 \left[ 0< \mathcal U_T(\mathcal C_0^{\rm eval}) < \infty \right]. } $$

If the native domain already determines \(T\),

$$ \boxed{H_D(T)=0,} $$

terminate:

$$ \boxed{\mathbf{NO\mbox{-}HEADROOM}.} $$

Even a perfect SUN correspondence would then contribute zero new information.

Apply only the SUN subgrammar the native domain can legitimately instantiate. Now—and only now—select admissible subgrammars
$$ \boxed{ G\in\mathfrak G_D^{(0)}(M) \subseteq\mathcal L_G^{(0)}. } $$

The candidate does not automatically receive all of SUN.

A domain might independently support only

$$ C_n\rightarrow\{R(C_n),L(C_n)\}\rightarrow C_{n+1}, $$

while another may support the full

$$ C_0\to C_1\to C_2\to C_3 \xrightarrow{\mathcal B}C_4 $$

with

$$ \mathcal I(\mathcal Bs)=\mathcal I(s), \qquad \mathcal Bs\neq s. $$

Every SUN clause must be earned by native structure.

Enumerate every valid SUN adapter. Construct the complete realization space
$$ \boxed{ \mathfrak R_D^{(0)} = \left\{ (M,G,A): \begin{array}{l} M\in\mathfrak M_D^{(0)},\\ G\in\mathfrak G_D^{(0)}(M),\\ A\in\mathcal L_A^{(0)}(M,G),\\ V_D(A\mid M,G)=1 \end{array} \right\}. } $$

The adapter must preserve the declared operations, not merely labels or numbers.

For example:

$$ \boxed{ A\circ R=R_D\circ A, } $$ $$ \boxed{ A\circ L=L_D\circ A, } $$

and if composition is tested,

$$ \boxed{ A\circ(RL) = (R_DL_D)\circ A. } $$

Similarity such as

$$ 72=72 $$

or

$$ 3\text{ stages}=3\text{ stages} $$

does not satisfy this gate.

Prove realization exhaustion and predictive uniqueness. Require
$$ \boxed{ Q_D^R=1. } $$

Then quotient complete realizations by their target prediction:

$$ \boxed{ r_i\equiv_T r_j \iff \frac{\mathcal C_{r_i}}{\approx_T^{\rm eval}} = \frac{\mathcal C_{r_j}}{\approx_T^{\rm eval}}. } $$

A confirmatory SUN prediction exists only if

$$ \boxed{ \left| \mathfrak R_D^{(0)}/\!\equiv_T \right| =1. } $$

If exhaustive enumeration produces no realization:

$$ \boxed{\mathbf{NO\mbox{-}REALIZATION}.} $$

If several empirically different predictions survive:

$$ \boxed{\mathbf{NONUNIQUE}.} $$

You do not choose among them.

Let SUN prune possibilities. For every admissible realization \(r=(M,G,A)\),
$$ \boxed{ S_E^{(\rm SUN)}(r) = \{ s\in S_E^{(0)}: s\models A(G) \}. } $$

The defining computational requirement is

$$ \boxed{ S_E^{(\rm SUN)}(r) \subseteq S_E^{(0)}. } $$

SUN may remove possibilities.

It may not invent new native states.

If

$$ \boxed{ S_E^{(\rm SUN)}(r)=\varnothing } $$

for an otherwise required realization, terminate before reveal:

$$ \boxed{\mathbf{PREREVEAL\mbox{-}INCONSISTENT}.} $$
Extract only the prediction actually forced. Compute
$$ \boxed{ \mathcal C_{\rm SUN}(r) = T(S_E^{(\rm SUN)}(r)). } $$

All admissible realizations must yield the same evaluation consequence.

SUN may force an exact answer, but need not.

If several targets survive yet all obey property \(P\),

$$ \boxed{ \forall z\in\mathcal C_{\rm SUN}, \quad P(z), } $$

then the prediction is only

$$ \boxed{P(z_{\rm true}).} $$

Do not promote a forced property into a forced coordinate.

If claiming “unique up to gauge,” calculate separately for every realization:

$$ \boxed{ G_E(r) = \operatorname{Aut}(M,A(G),E_T). } $$

Then require cross-realization gauge coherence:

$$ \boxed{ \left| \left\{ T(S_E^{(\rm SUN)}(r))/G_E(r): r\in\mathfrak R_D^{(0)} \right\} /\!\cong_T \right| =1. } $$
Commit before reveal. Freeze the prediction object:
$$ \boxed{ \mathcal P_{\rm SUN}^{(0)} = \begin{cases} \mathcal C_{\rm SUN}^{\rm eval}, &m_T=\mathrm{SET},\\[1mm] P_{\rm SUN}, &m_T=\mathrm{PROBABILISTIC}. \end{cases} } $$

Hash/timestamp the full prereveal state if implementing this computationally.

At that instant:

$$ \boxed{\text{MODELING STOPS}.} $$

No changed adapter, tolerance, target, equivalence relation, grammar, preprocessing rule, oracle, or native representation is permitted.

Reveal exactly once. Evaluate the already-frozen truth channel:
$$ \boxed{ z_{\rm true} = \Gamma(\mathscr D). } $$

For a set prediction test:

$$ \boxed{ [z_{\rm true}]_{\rm eval} \stackrel?{\in} \mathcal C_{\rm SUN}^{\rm eval}. } $$

If not:

$$ \boxed{\mathbf{FALSIFIED}.} $$

This is the decisive SUN retention failure.

Measure incremental information. Surviving truth is not sufficient.

For a set-valued target:

$$ \boxed{ G_T = 1- \frac{ \mathcal U_T(\mathcal C_{\rm SUN}^{\rm eval}) }{ \mathcal U_T(\mathcal C_0^{\rm eval}) }. } $$

For a finite equally weighted target:

$$ \boxed{ G_T = 1- \frac{ |\mathcal C_{\rm SUN}^{\rm eval}| }{ |\mathcal C_0^{\rm eval}| }. } $$

For a probabilistic target with preregistered strictly proper loss \(\ell_T\):

$$ \boxed{ G_T = \ell_T(P_{\rm native},z_{\rm true}) - \ell_T(P_{\rm SUN},z_{\rm true}). } $$

Therefore:

$$ \boxed{ \operatorname{Retain}_T=1 \land G_T\le0 \Longrightarrow \mathbf{NON\mbox{-}INFORMATIVE}. } $$

And only:

$$ \boxed{ \operatorname{Retain}_T=1 \land G_T>0 \Longrightarrow \mathbf{SUPPORTED}. } $$

The complete candidate test therefore has the causal order

$$ \boxed{ \begin{array}{c} \text{SUSPECTED ALIGNMENT} \\ \downarrow \\ K_{\rm seen}\text{ QUARANTINED} \\ \downarrow \\ \text{NATIVE ELIGIBILITY} \\ \downarrow \\ \omega_0\text{ FROZEN} \\ \downarrow \\ \text{ORACLE EXHAUSTION} \\ \downarrow \\ \Lambda_T^\star \\ \downarrow \\ \text{DISCOVERY-BLINDNESS TEST} \\ \downarrow \\ \text{MASK + NONINTERFERENCE} \\ \downarrow \\ \text{NATIVE-MODEL EXHAUSTION} \\ \downarrow \\ \mathcal C_0 \\ \downarrow \\ \text{HEADROOM} \\ \downarrow \\ \text{SUN-REALIZATION EXHAUSTION} \\ \downarrow \\ \text{PREDICTIVE UNIQUENESS} \\ \downarrow \\ S_E^{(\rm SUN)} \\ \downarrow \\ \mathcal P_{\rm SUN}^{(0)} \text{ COMMITTED} \\ \downarrow \\ z_{\rm true}\text{ REVEALED} \\ \downarrow \\ \operatorname{Retain}_T \\ \downarrow \\ G_T. \end{array} } $$

Thus a suspected candidate becomes positive empirical evidence for SUN iff

$$ \boxed{ \mathsf L_{\rm SUN}(\omega)=1 \;\land\; \operatorname{Retain}_T(\omega)=1 \;\land\; G_T(\omega)>0. } $$

A structure that merely matches SUN after inspection has not passed the SUN test at all.