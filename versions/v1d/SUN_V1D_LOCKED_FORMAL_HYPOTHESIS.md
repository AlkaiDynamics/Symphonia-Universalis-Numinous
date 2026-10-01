# SUN V1 D — LOCKED FORMAL HYPOTHESIS AND DUAL-TOPOLOGY PREDICTIVE PROTOCOL

**Status:** LOCKED — literal final audit passed.  
**Lineage:** V1 B remains an immutable historical version. V1 C remains a transitional design record. V1 D is the canonical successor specification.  
**Normative rule:** where a V1-B clause survives unchanged, its semantics are inherited exactly; topology-specific or temporal V1-D clauses supersede only the corresponding V1-B single-topology/single-license clauses.

---

I. FIXED STRUCTURAL GRAMMAR

Define one fixed relational grammar

$$ \boxed{ \mathcal G_{\rm SUN} = (R,L,\mathcal C,\mathcal B,\mathcal I,h,g). } $$

Its ordinary transition cell is

$$ \boxed{ C_n \longrightarrow \{R(C_n),L(C_n)\} \longrightarrow C_{n+1}. } $$

The grammar contains exactly three ordinary recursive generations:

$$ \boxed{ C_0\to C_1\to C_2\to C_3 } $$

followed by a structurally distinct boundary transition

$$ \boxed{ C_3\xrightarrow{\mathcal B}C_4. } $$

The canonical harmonic realization is

$$ \boxed{ R=\frac23, \qquad L=\frac34, \qquad RL=\frac12, } $$

with inverse orientation

$$ \boxed{ R^{-1}=\frac32, \qquad L^{-1}=\frac43, \qquad R^{-1}L^{-1}=2. } $$

Hence

$$ \boxed{ \left(\frac23,\frac34\right)^{-1} = \left(\frac32,\frac43\right). } $$

The boundary preserves a specified local relational invariant,

$$ \boxed{ \mathcal I(\mathcal Bs)=\mathcal I(s), } $$

without requiring global-state identity:

$$ \boxed{ \mathcal Bs\neq s. } $$

In the canonical register realization,

$$ \boxed{ g(\mathcal Bs)=g(s)+1. } $$

Completed Harmony supplies the canonical local closure

$$ \boxed{ \frac{16}{15}\frac{15}{16}=1 } $$

while permitting

$$ \boxed{ \Delta g=+1. } $$

Therefore the primary SUN boundary invariant is

$$ \boxed{ \text{LOCAL RELATIONAL CLOSURE} \not\Rightarrow \text{GLOBAL-STATE CLOSURE}. } $$

SUN also permits observational equivalence without provenance equivalence:

$$ \Phi(s_A)=\Phi(s_B), $$

possibly with

$$ \mathcal I(s_A)=\mathcal I(s_B), $$

while

$$ \boxed{ (h_A,g_A)\neq(h_B,g_B). } $$

Thus

$$ \boxed{ \text{SAME OBSERVABLE RELATION} \neq \text{SAME HIDDEN PATH/REGISTER}. } $$

Whenever hidden provenance is causally operative,

$$ \boxed{ \operatorname{Post}^{+}(s_A) \not\sim \operatorname{Post}^{+}(s_B) } $$

may follow even when present observable states coincide.

The structural clause is therefore

$$ \boxed{ \begin{aligned} H_{\rm grammar}:\quad \exists\,\mathcal G_{\rm SUN}\ \text{such that}\quad & \mathcal G_{\rm SUN} \text{ is a fixed domain-independent relational transition grammar} \\ &\text{containing complementary generation, exactly three ordinary} \\ &\text{recursive transitions, a distinguished boundary class,} \\ &\text{local-invariant preservation with possible global displacement,} \\ &\text{and hidden provenance capable of constraining later reachability} \\ &\text{whenever that provenance is causally operative.} \end{aligned} } $$

---

# II. STATUS LAYERS AND SCOPE

V1 D preserves the V1-B core grammar and scientific severity while recognizing two noninterventional predictive topologies.

$$\boxed{\mathsf{TrialType}\in\{\mathsf{SEALED},\mathsf{DIRECTED}\}.}$$

The trial topology is orthogonal to the scoring mode:

$$\boxed{m_T\in\{\mathrm{SET},\mathrm{PROBABILISTIC}\}.}$$

Hence four topology/scoring combinations are admissible.

The preregistered uncertainty functional $\mathcal U_T$ is mode-appropriate: in SET mode it acts on evaluation-level possibility sets and is monotone under set inclusion; in PROBABILISTIC mode it acts on prediction distributions and is frozen so that zero denotes no residual target uncertainty under the registered evaluation semantics.

The hypothesis-status layers are:

$$\boxed{H_{\rm SUN}^{\rm core}=H_{\rm grammar}\land H_{\rm licensability}^{+}\land H_{\rm retention}\land H_{\rm information}.}$$

For registration-directed behavior:

$$\boxed{H_{\rm directed}=H_1\land H_2\land H_3.}$$

where the population hypotheses are defined in Section XXVIII.

The proposed class/note displacement mechanism remains separate:

$$\boxed{H_{\rm displacement}\dashrightarrow H_1/H_2,}$$

where $\dashrightarrow$ means possible explanatory mechanism, not logical necessity.

The presently recovered W72 status is frozen as:

$$\boxed{\begin{array}{rcl}
\Delta g=+1&:&\mathbf{ESTABLISHED},\\
\tau\mapsto\tau+1\pmod3&:&\mathbf{ESTABLISHED},\\
\alpha+\lambda=1&:&\mathbf{ESTABLISHED},\\
p\mapsto p+1\pmod{12}&:&\mathbf{NOT\ ESTABLISHED},\\
\chi_{\rm disp}\mapsto\chi_{\rm disp}+1&:&\mathbf{ACTIVE\ HYPOTHESIS}.
\end{array}}$$

No one-note/class displacement law enters the SUN core unless independently established.

---

# III. FROZEN EMPIRICAL PROGRAM AND TOPOLOGY CLASSIFICATION

The empirical program is selected by the V1-B mechanism

$$\boxed{u\sim\nu_0,\qquad \omega=\Sigma_0(u).}$$

with

$$\boxed{\Omega_0=\operatorname{Range}(\Sigma_0),\qquad \Pi_0=(\Sigma_0)_\#\nu_0.}$$

$\Omega_0$ governs logical universal claims and $\Pi_0$ governs probabilities and expectations. None of $\Sigma_0,\nu_0,\Omega_0,\Pi_0$ may change in response to observed outcomes.

Freeze a topology classifier

$$\boxed{\tau:(D,K_{\rm reg})\mapsto\{\mathsf{SEALED},\mathsf{DIRECTED}\}.}$$

Its certificate predicate is

$$\boxed{Q_\tau=1\iff\exists\pi_\tau:\operatorname{Verify}_\tau(\pi_\tau,\tau,\Sigma_0,\nu_0)=1.}$$

For each trial,

$$\boxed{\mathsf{TrialTypeClosed}(\omega)\iff Q_\tau=1\land \mathsf{TrialType}(\omega)=\tau(D,K_{\rm reg}),}$$

with $\tau$ committed before outcome-bearing evidence is inspected. No post-hoc topology switching is permitted.

Define the eligible-domain family

$$\boxed{\mathfrak D_{\rm SUN}^{(0)}=\{D:\mathsf{Elig}_D(D)=1\}.}$$

---

# IV. COMPLETE V1-D PREREGISTRATION OBJECT

V1 D retains every V1-B preregistration object and extends it rather than replacing it.

The V1-B base object is retained exactly as the target-specific preregistration object:

$$\boxed{\omega_{0,B}^{+}=\left(D,\mathscr D,K_{\rm seen},T,\mathcal L_\Gamma^{(0)},\mathcal L_{\rm dep}^{(0)},\mathcal L_K^{(0)},\widehat\mu_T,O,\approx_T^{\rm eval},\mathcal U_T,m_T,\mathcal L_M^{(0)},\mathcal L_G^{(0)},\mathcal L_A^{(0)},\Theta_0\right).}$$

For $\mathsf{SEALED}$ trials, the target exists before target-specific preregistration and V1 D may instantiate $\omega_{0,D}^{+}$ directly.

For $\mathsf{DIRECTED}$ trials, target-specific preregistration is preceded by a registration state in which $T$ need not yet exist:

$$\boxed{\omega_{\rm reg}=\left(D,\mathscr D_0,K_{\rm reg},\mathcal L_{\rm anchor}^{(0)},V_{\rm anchor},\sim_{\rm anchor},F_{\rm gap},\mathcal U_{\rm gap},\Theta_{\rm reg}\right).}$$

Here $\Theta_{\rm reg}$ is the pre-target restriction of the frozen V1-D semantic/verifier package to topology classification, anchor admissibility/exhaustion, gap derivation, gap uncertainty, and temporal-prefix certification; it contains no outcome-bearing evidence.

Only after the frozen registration/gap procedure yields

$$\boxed{\omega_{\rm reg}\xrightarrow{F_{\rm gap}}E_{\rm sel}\xrightarrow{}T}$$

may the directed trial instantiate its target-specific $\omega_{0,D}^{+}$. At that point set $\mathscr D:=\mathscr D_0$ for the V1-B base fields.

The V1-D target-specific object is

$$\boxed{\omega_{0,D}^{+}=\omega_{0,B}^{+}\cup\{\mathsf{TrialType},K_{\rm reg},K_{\rm pred},E_{\rm sel},\mathcal J_0,\mathcal U_{\rm gap},\text{topology-specific preregistered objects}\}.}$$

$K_{\rm seen}$ is retained as the V1-B legacy discovery-ledger field and is embedded in the corresponding V1-D preregistration history; $K_{\rm pred}$ is the operative prediction-time contamination/evidence ledger defined in Section VI.

The retained V1-B semantic package is

$$\boxed{\Theta_0=\left(Y_D,W_D,V_D,\mathsf{Elig}_D,\equiv_T^\Gamma,\equiv_T^0,\equiv_T,\cong_T,\mathcal V_0,\mathsf{RetainRule}_T,\Psi_T^{(0)},\ell_T\right).}$$

V1 D extends it as

$$\boxed{\Theta_D=\Theta_0\cup\{\operatorname{Verify}_\tau,\operatorname{Verify}_{\rm anchor},\operatorname{Verify}_{\rm gap},\operatorname{Verify}_{\rm acq},\operatorname{VerifyProv},\operatorname{Verify}_{\rm temporal},\operatorname{Verify}_{\rm eviddep},\operatorname{Verify}_{\rm stop},\operatorname{Verify}_{\rm adj},\ldots\}.}$$

The frozen verifier suite $\mathcal V_D\supseteq\mathcal V_0$ contains every verifier required by this specification. No later certificate is meaningful unless its verifier was already frozen in $\Theta_D$.

The inherited equivalence relations are interpreted mode-appropriately: $\equiv_T^0$ governs native-baseline equivalence (SET target baselines or PROBABILISTIC native prediction distributions as applicable), $\equiv_T$ governs empirical prediction equivalence across SUN realizations, $\equiv_T^\Gamma$ governs truth-channel equivalence, $\approx_T^{\rm eval}$ governs observable target evaluation, and $\cong_T$ governs the registered symmetry/gauge claim.

---

# V. CERTIFIED EXHAUSTION

For every relevant search space $X$,

$$\boxed{Q_X=1\iff\exists\pi_X:\operatorname{Verify}_X(\pi_X)=1.}$$

Define

$$\boxed{\operatorname{ClosureStatus}(X)=\begin{cases}
\mathbf{UNEXHAUSTED},&Q_X=0,\\
\mathbf{EMPTY},&Q_X=1\land|X/\!\sim|=0,\\
\mathbf{UNIQUE},&Q_X=1\land|X/\!\sim|=1,\\
\mathbf{NONUNIQUE},&Q_X=1\land|X/\!\sim|>1.
\end{cases}}$$

Thus

$$\boxed{\mathbf{UNEXHAUSTED}\neq\mathbf{EMPTY}\neq\mathbf{NONUNIQUE}\neq\mathbf{GAUGE\mbox{-}EQUIVALENT}.}$$

---

# VI. TEMPORAL KNOWLEDGE STATES AND DISCOVERY CLOSURE

V1 D distinguishes epistemic time.

At minimum,

$$\boxed{K_{\rm reg}\subseteq K_{\rm pred}.}$$

For directed trials,

$$\boxed{K_{\rm reg}\subseteq K_{\rm pred}\subseteq K_{\rm acq}(t).}$$

$K_{\rm reg}$ is information available when registration begins. $K_{\rm pred}$ is the complete **outcome-bearing evidence/contamination state available to the prediction process** immediately before commitment. It includes all seen native evidence, target-selection information, and permitted native deductions, but it excludes the SUN prediction object itself and deductions produced solely by applying the SUN constraint. Those belong to the model/prediction state, not to the contamination ledger. $K_{\rm acq}(t)$ is the evidence/knowledge state after postcommit acquisition.

Close prediction-time knowledge under the frozen discovery language:

$$\boxed{K_{\rm pred}^{+}=\operatorname{Dep}_{\mathcal L_K^{(0)}}^{*}(K_{\rm pred}).}$$

Require

$$\boxed{Q_K=1\iff\exists\pi_K:\operatorname{Verify}_K(\pi_K)=1.}$$

Define

$$\boxed{\mathsf{DiscoveryBlind}_T(K_{\rm pred}^{+})=1}$$

iff the target evaluation class is neither explicitly contained in nor deterministically recoverable from $K_{\rm pred}^{+}$ under the frozen **discovery/native inference language**. $\mathcal L_K^{(0)}$ may not smuggle the SUN prediction operator into the contamination test merely because SUN later derives a prediction from the same visible evidence.

For finite set-valued targets this requires

$$\boxed{\mathcal U_T(T\mid K_{\rm pred}^{+})>0.}$$

Postcommit knowledge growth is permitted. The invariant is

$$\boxed{K_{\rm acq}(t)\not\rightsquigarrow\Delta\{T,M,G,A,\text{optional mechanism},\approx,\mathcal P_{\rm SUN}^{(0)},\text{scoring rule}\}.}$$

New evidence may change what investigators know; it may not change what SUN predicted.

---

# VII. COMMON NATIVE-DOMAIN RULE

SUN may not construct the native possibility space.

Define

$$\boxed{\mathfrak M_D^{(0)}=\{M\in\mathcal L_M^{(0)}(D):W_D(M)=1\}.}$$

Require

$$\boxed{Q_D^M=1.}$$

Native latent state spaces need not be identical. They must, however, yield one evaluation-level target baseline under the topology-specific definition below.

For each admissible native model freeze the admissible SUN-subgrammar family

$$\boxed{\mathfrak G_D^{(0)}(M)\subseteq\mathcal L_G^{(0)}.}$$

This family is common to both trial topologies; topology-specific realization records determine how it is anchored and evaluated.

---

# VIII. TRIAL TYPE I — SEALED-STATE PREDICTION

Type I applies when the truth already exists inside a fixed truth-bearing object.

Its topology is

$$\boxed{\mathscr D\rightarrow\mu_T^\star(\mathscr D)\rightarrow\text{reason}\rightarrow\mathsf L_{\rm pre}\rightarrow\mathbf{COMMIT}\rightarrow\mathsf{Reveal}_{\rm static}.}$$

## VIII.A Truth-oracle closure

Define

$$\boxed{\mathfrak\Gamma_T^{(0)}=\{\Gamma\in\mathcal L_\Gamma^{(0)}:Y_D(\Gamma)=1\}.}$$

Require

$$\boxed{Q_T^\Gamma=1,\qquad\left|\mathfrak\Gamma_T^{(0)}/\!\equiv_T^\Gamma\right|=1.}$$

Thus

$$\boxed{\mathsf{OracleClosed}_{I}\iff Q_T^\Gamma=1\land\left|\mathfrak\Gamma_T^{(0)}/\!\equiv_T^\Gamma\right|=1.}$$

Define the complete answer-bearing dependency firewall

$$\boxed{\Lambda_T^\star=\bigcup_{\Gamma\in\mathfrak\Gamma_T^{(0)}}\operatorname{Dep}^{*}_{\mathcal L_{\rm dep}^{(0)}}(\Gamma).}$$

No preferred oracle is selected.

## VIII.B Masking and noninterference

Instantiate

$$\boxed{\mu_T^\star=\widehat\mu_T(\Lambda_T^\star),\qquad \mathscr D_{\rm vis}=\mu_T^\star(\mathscr D),\qquad E_T=O(\mathscr D_{\rm vis}).}$$

Require

$$\boxed{d|_{\neg\Lambda_T^\star}=d'|_{\neg\Lambda_T^\star}\Longrightarrow O(\mu_T^\star(d))=O(\mu_T^\star(d')).}$$

and the frozen certificate

$$\boxed{\operatorname{NONINTERFERENCE}=1\iff\exists\pi_{\rm NI}:\operatorname{Verify}_{\rm NI}(\pi_{\rm NI},\mu_T^\star,O,\Lambda_T^\star)=1.}$$

## VIII.C Native closure and headroom

For $M\in\mathfrak M_D^{(0)}$ define

$$\boxed{S_{E,M,I}^{(0)}=\{s:s\models M,\ s\models E_T\},\qquad \mathcal C_{0,I}(M)=T(S_{E,M,I}^{(0)}).}$$

For PROBABILISTIC mode also construct, before SUN realization,

$$\boxed{P_{{\rm native},I}(M)=\Psi_T^{(0)}(M,E_T,S_{E,M,I}^{(0)}).}$$

Native closure is mode-specific:

$$\boxed{\mathsf{NativeClosed}_{I}\iff Q_D^M=1\land\begin{cases}
\forall M_i,M_j,\ \dfrac{\mathcal C_{0,I}(M_i)}{\approx_T^{\rm eval}}=\dfrac{\mathcal C_{0,I}(M_j)}{\approx_T^{\rm eval}},&m_T=\mathrm{SET},\\[2mm]
\forall M_i,M_j,\ P_{{\rm native},I}(M_i)\equiv_T^0P_{{\rm native},I}(M_j),&m_T=\mathrm{PROBABILISTIC}.
\end{cases}}$$

For SET mode define

$$\boxed{\mathcal C_{0,I}^{\rm eval}:=\mathcal C_{0,I}(M)/\!\approx_T^{\rm eval}}$$

and

$$\boxed{H_{D,I}(T)=\mathbf1[0<\mathcal U_T(\mathcal C_{0,I}^{\rm eval})<\infty].}$$

For PROBABILISTIC mode, once native closure holds let $P_{{\rm native},I}$ denote the unique native prediction-equivalence class and define

$$\boxed{H_{D,I}(T)=\mathbf1[0<\mathcal U_T(P_{{\rm native},I})<\infty].}$$

A trial with no native predictive uncertainty terminates as $\mathbf{NO\mbox{-}HEADROOM}$.

## VIII.D Complete SUN realization space

For each native model define admissible SUN subgrammars $\mathfrak G_D^{(0)}(M)\subseteq\mathcal L_G^{(0)}$ and

$$\boxed{\mathfrak R_{D,I}^{(0)}=\left\{r=(M,G,A):M\in\mathfrak M_D^{(0)},\ G\in\mathfrak G_D^{(0)}(M),\ A\in\mathcal L_A^{(0)}(M,G),\ V_D(A\mid M,G)=1\right\}.}$$

Adapters must preserve frozen types, operations, composition laws, distinctions, and invariants. Where applicable,

$$\boxed{A\circ R=R_D\circ A,\qquad A\circ L=L_D\circ A,\qquad A\circ(RL)=(R_DL_D)\circ A.}$$

Numerical resemblance or cardinality coincidence is insufficient.

Require

$$\boxed{Q_{D,I}^{R}=1.}$$

## VIII.E SUN-constrained states and prediction

For every realization,

$$\boxed{S_{E,I}^{(\rm SUN)}(r)=\{s\in S_{E,M,I}^{(0)}:s\models A(G)\}\subseteq S_{E,M,I}^{(0)}.}$$

Require $S_{E,I}^{(\rm SUN)}(r)\neq\varnothing$ for every admissible realization.

For SET mode,

$$\boxed{\mathcal C_{{\rm SUN},I}(r)=T(S_{E,I}^{(\rm SUN)}(r)),\qquad \mathcal C_{{\rm SUN},I}^{\rm eval}(r)=\mathcal C_{{\rm SUN},I}(r)/\!\approx_T^{\rm eval}.}$$

For PROBABILISTIC mode,

$$\boxed{P_{{\rm SUN},I}(r)=\Psi_T^{(0)}(r,E_T,S_{E,I}^{(\rm SUN)}(r)).}$$

Define topology/mode-dispatched predictive equivalence:

$$\boxed{r_i\equiv_{T,I}r_j\iff\begin{cases}
\mathcal C_{{\rm SUN},I}^{\rm eval}(r_i)=\mathcal C_{{\rm SUN},I}^{\rm eval}(r_j),&m_T=\mathrm{SET},\\
P_{{\rm SUN},I}(r_i)\equiv_T P_{{\rm SUN},I}(r_j),&m_T=\mathrm{PROBABILISTIC}.
\end{cases}}$$

Then

$$\boxed{\mathsf{RealizationClosed}_{I}\iff Q_{D,I}^{R}=1\land|\mathfrak R_{D,I}^{(0)}/\!\equiv_{T,I}|=1.}$$

When $\mathsf{RealizationClosed}_{I}=1$, define the common prediction object represented by that unique equivalence class as $\mathcal C_{{\rm SUN},I}^{\rm eval}$ in SET mode or $P_{{\rm SUN},I}$ in PROBABILISTIC mode; likewise define the model-independent native probabilistic baseline $P_{{\rm native},I}$ under the frozen native-model equivalence.

A property forced across every surviving target may be predicted, but it may not be promoted into an exact coordinate unless that exact coordinate is forced.

For realization-specific gauge define

$$\boxed{G_{E,I}(r)=\operatorname{Aut}(M,A(G),E_T).}$$

Gauge controls hidden-coordinate identifiability; $\approx_T^{\rm eval}$ controls empirical scoring.

## VIII.F Nonvacuity

For SET mode,

$$\boxed{\mathsf{ConstraintActive}_{I}=\mathbf1[\mathcal C_{{\rm SUN},I}^{\rm eval}\subsetneq\mathcal C_{0,I}^{\rm eval}].}$$

For PROBABILISTIC mode,

$$\boxed{\mathsf{ConstraintActive}_{I}=\mathbf1[P_{{\rm SUN},I}\not\equiv_T P_{{\rm native},I}].}$$

---

# IX. TRIAL TYPE II — REGISTRATION-DIRECTED ACQUISITION

Type II applies when known partial structure can potentially identify which unresolved region should be tested, and decisive evidence is acquired only after prediction commitment.

Its topology is

$$\boxed{\mathscr D_0\rightarrow\text{partial registration}\rightarrow\text{gap derivation}\rightarrow E_{\rm sel}\rightarrow\mathsf L_{\rm pre}\rightarrow\mathbf{COMMIT}\rightarrow\Gamma_{\rm search}\rightarrow\Delta\mathscr D_{\rm acq}\rightarrow\mathsf{Reveal}_{\rm acquisition}.}$$

## IX.A Partial-registration closure

Freeze $\mathcal L_{\rm anchor}^{(0)}$ and define

$$\boxed{\mathfrak A_D^{(0)}=\{A_{\rm anchor}\in\mathcal L_{\rm anchor}^{(0)}:V_{\rm anchor}(A_{\rm anchor})=1\}.}$$

Require

$$\boxed{Q_D^{\rm anchor}=1,\qquad\mathsf{AnchorClosed}\iff Q_D^{\rm anchor}=1\land|\mathfrak A_D^{(0)}|>0.}$$

Gauge-equivalent partial registrations may be quotiented only under a frozen $\sim_{\rm anchor}$.

No preferred registration may be selected because it later predicts the observed answer.

## IX.B Anchor constraint rank and registration reduction

Let $\mathfrak R_0^{\rm reg}$ be the admissible registration/orientation space before qualifying anchor constraints. For an ordering $a_{i_1},\ldots,a_{i_r}$ let $\mathfrak R_j^{\rm reg}$ be the space after the first $j$ constraints. Define

$$\boxed{\mathfrak R_D^{\rm prior}:=\mathfrak R_0^{\rm reg},\qquad \mathfrak R_D^{\rm anchor}:=\mathfrak R_{\rho_{\rm anchor}}^{\rm reg}.}$$

Define $\rho_{\rm anchor}$ as the largest $r$ for which

$$\boxed{\mathfrak R_0^{\rm reg}\supsetneq\mathfrak R_1^{\rm reg}\supsetneq\cdots\supsetneq\mathfrak R_r^{\rm reg}}$$

modulo frozen gauge.

Thus three observed correspondences do not imply $\rho_{\rm anchor}=3$.

Define

$$\boxed{R_1(\omega)=\mathsf{RegistrationReduced}(\omega)=\mathbf1[\mathfrak R_D^{\rm anchor}/\!\sim_{\rm anchor}\subsetneq\mathfrak R_D^{\rm prior}/\!\sim_{\rm anchor}].}$$

## IX.C Gap derivation and target-selection event

Freeze a gap-selection rule $F_{\rm gap}$. It may consume $D$, $\mathscr D_0$, known anchors, the complete admissible registration space, frozen SUN structure, and separately registered optional mechanisms. It may not consume the target truth.

It returns

$$\boxed{E_{\rm sel}=(D,\text{gap identity},\text{target variable},\text{selection rule},\text{evidence used}).}$$

Require a frozen gap-derivation certificate

$$\boxed{Q_{\rm gap}=1\iff\exists\pi_{\rm gap}:\operatorname{Verify}_{\rm gap}(\pi_{\rm gap},F_{\rm gap},\omega_{\rm reg},E_{\rm sel})=1.}$$

Define

$$\boxed{\mathsf{GapDerived}=1\iff Q_{\rm gap}=1}$$

iff $E_{\rm sel}$ was generated solely by the frozen prereveal procedure without access to target truth.

SUN may help determine which question to ask. The answer must remain unknown.

## IX.D Selection-conditioned native baseline

Target selection itself contains information and may not be credited twice.

For each native model define

$$\boxed{S_{E,M,II}^{(0)}\mid E_{\rm sel}}$$

as the native state space after the public fact of target selection is supplied, without supplying SUN's reason for selecting it.

Define

$$\boxed{\mathcal C_{0,II}(M\mid E_{\rm sel})=T(S_{E,M,II}^{(0)}\mid E_{\rm sel}).}$$

For PROBABILISTIC mode also construct, before SUN realization,

$$\boxed{P_{{\rm native},II}(M)=\Psi_T^{(0)}(M,E_{\rm sel},S_{E,M,II}^{(0)}).}$$

Require mode-specific native closure:

$$\boxed{\mathsf{NativeClosed}_{II}\iff Q_D^M=1\land\begin{cases}
\forall M_i,M_j,\ \dfrac{\mathcal C_{0,II}(M_i\mid E_{\rm sel})}{\approx_T^{\rm eval}}=\dfrac{\mathcal C_{0,II}(M_j\mid E_{\rm sel})}{\approx_T^{\rm eval}},&m_T=\mathrm{SET},\\[2mm]
\forall M_i,M_j,\ P_{{\rm native},II}(M_i)\equiv_T^0P_{{\rm native},II}(M_j),&m_T=\mathrm{PROBABILISTIC}.
\end{cases}}$$

For SET mode define

$$\boxed{\mathcal C_{0,II}^{\rm eval}(E_{\rm sel})=\mathcal C_{0,II}(M\mid E_{\rm sel})/\!\approx_T^{\rm eval}}$$

and

$$\boxed{H_{D,II}(T)=\mathbf1[0<\mathcal U_T(\mathcal C_{0,II}^{\rm eval}\mid E_{\rm sel})<\infty].}$$

For PROBABILISTIC mode, once native closure holds let $P_{{\rm native},II}$ denote the unique conditional native prediction-equivalence class and define

$$\boxed{H_{D,II}(T)=\mathbf1[0<\mathcal U_T(P_{{\rm native},II})<\infty].}$$

## IX.E Gap illumination

Let $\mathcal X_{\rm gap}^{0}$ be the unresolved native location/class/property possibilities before SUN registration is propagated. For each complete realization $r$, let $\mathcal X_{\rm gap}(r)$ denote the unresolved native location/class/property possibilities compatible with that realization. Across all admissible SUN realizations define

$$\boxed{\mathcal X_{\rm gap}^{\rm SUN}=\bigcap_{r\in\mathfrak R_{D,II}^{(0)}}\mathcal X_{\rm gap}(r).}$$

Then

$$\boxed{R_2(\omega)=\mathsf{GapIlluminated}(\omega)=\mathbf1[\mathcal X_{\rm gap}^{\rm SUN}\subsetneq\mathcal X_{\rm gap}^{0}].}$$

Freeze a monotone gap-uncertainty functional $\mathcal U_{\rm gap}$ before the gap result is known. Define $\mathcal X_{\rm loc}^{0},\mathcal X_{\rm loc}^{\rm SUN}$ and $\mathcal X_{\rm class}^{0},\mathcal X_{\rm class}^{\rm SUN}$ as the corresponding location and class projections of the gap possibility sets. Then

$$\boxed{\mathsf{LocationGain}=\mathbf1[\mathcal X_{\rm loc}^{\rm SUN}\subsetneq\mathcal X_{\rm loc}^{0}],\qquad\mathsf{ClassGain}=\mathbf1[\mathcal X_{\rm class}^{\rm SUN}\subsetneq\mathcal X_{\rm class}^{0}].}$$

## IX.F Complete Type-II realization closure

Define

$$\boxed{\mathfrak R_{D,II}^{(0)}=\left\{r=(M,G,A_{\rm anchor},A,\eta):\begin{array}{l}
M\in\mathfrak M_D^{(0)},\\
A_{\rm anchor}\in\mathfrak A_D^{(0)},\\
G\in\mathfrak G_D^{(0)}(M),\\
A\text{ extends }A_{\rm anchor},\\
V_D(A\mid M,G)=1,\\
\eta\text{ is any separately preregistered optional mechanism}
\end{array}\right\}.}$$

Every admissible partial registration must be extended or formally rejected by frozen criteria. No orientation disappears silently.

Require

$$\boxed{Q_{D,II}^{R}=1.}$$

For every realization define

$$\boxed{S_{E,II}^{(\rm SUN)}(r)\subseteq S_{E,M,II}^{(0)}\mid E_{\rm sel},\qquad S_{E,II}^{(\rm SUN)}(r)\neq\varnothing.}$$

For SET mode,

$$\boxed{\mathcal C_{{\rm SUN},II}(r\mid E_{\rm sel})=T(S_{E,II}^{(\rm SUN)}(r)),\quad \mathcal C_{{\rm SUN},II}^{\rm eval}(r\mid E_{\rm sel})=\mathcal C_{{\rm SUN},II}(r\mid E_{\rm sel})/\!\approx_T^{\rm eval}.}$$

For PROBABILISTIC mode,

$$\boxed{P_{{\rm SUN},II}(r)=\Psi_T^{(0)}(r,E_{\rm sel},S_{E,II}^{(\rm SUN)}(r)).}$$

Define

$$\boxed{r_i\equiv_{T,II}r_j\iff\begin{cases}
\mathcal C_{{\rm SUN},II}^{\rm eval}(r_i\mid E_{\rm sel})=\mathcal C_{{\rm SUN},II}^{\rm eval}(r_j\mid E_{\rm sel}),&m_T=\mathrm{SET},\\
P_{{\rm SUN},II}(r_i)\equiv_T P_{{\rm SUN},II}(r_j),&m_T=\mathrm{PROBABILISTIC}.
\end{cases}}$$

Then

$$\boxed{\mathsf{RealizationClosed}_{II}\iff Q_{D,II}^{R}=1\land|\mathfrak R_{D,II}^{(0)}/\!\equiv_{T,II}|=1.}$$

When $\mathsf{RealizationClosed}_{II}=1$, define the common prediction object represented by that unique equivalence class as $\mathcal C_{{\rm SUN},II}^{\rm eval}$ in SET mode or $P_{{\rm SUN},II}$ in PROBABILISTIC mode; likewise define the model-independent conditional native probabilistic baseline $P_{{\rm native},II}$.

A common forced property may be predicted without claiming a unique coordinate.

## IX.G Conditional target nonvacuity

For SET mode,

$$\boxed{\mathsf{ConstraintActive}_{II}=\mathbf1[\mathcal C_{{\rm SUN},II}^{\rm eval}\subsetneq\mathcal C_{0,II}^{\rm eval}(E_{\rm sel})].}$$

For PROBABILISTIC mode,

$$\boxed{\mathsf{ConstraintActive}_{II}=\mathbf1[P_{{\rm SUN},II}\not\equiv_T P_{{\rm native},II}].}$$

$\mathsf{ConstraintActive}_{II}$ and $\mathsf{GapIlluminated}$ are independent questions: did SUN narrow the answer once the target was specified, and did SUN narrow which unresolved target/location/class to investigate?

## IX.H Directed acquisition channel

Freeze

$$\boxed{\Gamma_{\rm search}=(\mathscr S,P_{\rm acq},\tau_{\rm stop},V_{\rm evidence},E_{\rm adjudicate}).}$$

Here $\mathscr S$ is the admissible evidence/search universe, $P_{\rm acq}$ the acquisition procedure, $\tau_{\rm stop}$ the stopping rule, $V_{\rm evidence}$ the evidence-admissibility predicate, and $E_{\rm adjudicate}$ the frozen map from admissible acquired evidence to the target evaluation class.

Each acquisition component is a registered object governed by the Section-V certificate rule $Q_X=1\iff\exists\pi_X:\operatorname{Verify}_X(\pi_X)=1$. Require certified closure of every component:

$$\boxed{\mathsf{AcquisitionClosed}_{II}\iff Q_{\mathscr S}=1\land Q_{P_{\rm acq}}=1\land Q_{\tau_{\rm stop}}=1\land Q_{V_{\rm evidence}}=1\land Q_{E_{\rm adjudicate}}=1.}$$

Before commitment freeze the allowed evidence universe, allowed queries/measurements, ordering where relevant, hit criterion, miss criterion, contradiction handling, ambiguity handling, stopping rule, and adjudication rule.

If the stopping rule is reached without sufficient evidence, record

$$\boxed{\mathbf{SEARCH\mbox{-}EXHAUSTED\mbox{-}UNRESOLVED}.}$$

It is not converted into confirmation.

Type II is observational/acquisitional, not interventional:

$$\boxed{\mathsf{DIRECTED}\neq\mathsf{INTERVENTIONAL}.}$$

If the postcommit procedure causally changes the target system, the trial is outside V1 D.

## IX.I Temporal dataset transition

Before commitment the evidential dataset is $\mathscr D_0$. After commitment,

$$\boxed{\mathscr D_0\xrightarrow[\Gamma_{\rm search}]{\rm acquisition}\mathscr D_1=\mathscr D_0\cup\Delta\mathscr D_{\rm acq}.}$$

The scientific separation is

$$\boxed{\text{PREDICTION FROM }\mathscr D_0\qquad\text{TEST FROM }\Delta\mathscr D_{\rm acq}.}$$

Ordinarily,

$$\boxed{z_{\rm true}=E_{\rm adjudicate}(\Delta\mathscr D_{\rm acq}).}$$

If adjudication legitimately requires context from $\mathscr D_0$, that dependence must be frozen explicitly.

---

# X. COMMON TRUTH-CHANNEL READINESS

Define

$$\boxed{\mathsf{TruthChannelReady}=\begin{cases}
\mathsf{OracleClosed}_{I},&\mathsf{TrialType}=\mathsf{SEALED},\\
\mathsf{AcquisitionClosed}_{II},&\mathsf{TrialType}=\mathsf{DIRECTED}.
\end{cases}}$$

The term “Ready” is deliberate: in Type II the truth has not yet entered the adjudicated trial state.

Define topology dispatchers

$$\boxed{\mathsf{NativeClosed}_{\tau}=\begin{cases}\mathsf{NativeClosed}_{I},&\mathsf{SEALED},\\\mathsf{NativeClosed}_{II},&\mathsf{DIRECTED},\end{cases}}$$

$$\boxed{H_{D,\tau}(T)=\begin{cases}H_{D,I}(T),&\mathsf{SEALED},\\H_{D,II}(T),&\mathsf{DIRECTED},\end{cases}}$$

$$\boxed{\mathsf{RealizationClosed}_{\tau}=\begin{cases}\mathsf{RealizationClosed}_{I},&\mathsf{SEALED},\\\mathsf{RealizationClosed}_{II},&\mathsf{DIRECTED},\end{cases}}$$

$$\boxed{\mathsf{ConstraintActive}_{\tau}=\begin{cases}\mathsf{ConstraintActive}_{I},&\mathsf{SEALED},\\\mathsf{ConstraintActive}_{II},&\mathsf{DIRECTED}.\end{cases}}$$

Also define

$$\boxed{Q_{D,\tau}^{R}=\begin{cases}Q_{D,I}^{R},&\mathsf{SEALED},\\Q_{D,II}^{R},&\mathsf{DIRECTED},\end{cases}}$$

$$\boxed{\mathfrak R_{D,\tau}^{(0)}=\begin{cases}\mathfrak R_{D,I}^{(0)},&\mathsf{SEALED},\\\mathfrak R_{D,II}^{(0)},&\mathsf{DIRECTED},\end{cases}}$$

and dispatch $S_{E,\tau}^{(\rm SUN)}$ analogously.

For SET mode define

$$\boxed{\mathcal C_{{\rm SUN},\tau}^{\rm eval}=\begin{cases}\mathcal C_{{\rm SUN},I}^{\rm eval},&\mathsf{SEALED},\\\mathcal C_{{\rm SUN},II}^{\rm eval},&\mathsf{DIRECTED},\end{cases}}$$

and for PROBABILISTIC mode

$$\boxed{P_{{\rm SUN},\tau}=\begin{cases}P_{{\rm SUN},I},&\mathsf{SEALED},\\P_{{\rm SUN},II},&\mathsf{DIRECTED}.\end{cases}}$$

Define $P_{{\rm native},\tau}$ analogously. $\mathcal P_{\rm SUN}^{(0)}$ is assigned from the appropriate common prediction object at commitment.

---

# XI. PRECOMMIT LICENSE

Define the issuance time $t_{\rm pre}$ immediately before commitment.

Define a frozen prefix verifier $\operatorname{Verify}_{\rm temporal}^{\rm pre}$. Then

$$\boxed{\mathsf{TemporalPreValid}=1\iff\exists\pi_{\rm pre}:\operatorname{Verify}_{\rm temporal}^{\rm pre}(\pi_{\rm pre})=1}$$

iff the topology classification, target-selection event where applicable, preregistered models, verifiers, equivalences, and prediction objects are all fixed before $t_{\rm pre}$ and no outcome-bearing reveal/acquisition event has occurred by $t_{\rm pre}$.

The precommit predictive license is

$$\boxed{\begin{aligned}
\mathsf L_{\rm pre}(\omega)=1\iff\;&D\in\mathfrak D_{\rm SUN}^{(0)}\\
&\land\mathsf{TrialTypeClosed}\\
&\land\mathsf{TruthChannelReady}\\
&\land Q_K=1\\
&\land\mathsf{DiscoveryBlind}_T(K_{\rm pred}^{+})=1\\
&\land\mathsf{NativeClosed}_{\tau}\\
&\land H_{D,\tau}(T)=1\\
&\land Q_{D,\tau}^{R}=1\\
&\land\mathsf{RealizationClosed}_{\tau}\\
&\land\mathsf{ConstraintActive}_{\tau}=1\\
&\land\forall r\in\mathfrak R_{D,\tau}^{(0)},\ S_{E,\tau}^{(\rm SUN)}(r)\neq\varnothing\\
&\land\mathsf{TemporalPreValid}\\
&\land\begin{cases}
\operatorname{NONINTERFERENCE}=1,&\mathsf{SEALED},\\
\mathsf{AnchorClosed}=1\land\mathsf{GapDerived}=1\land\mathsf{AcquisitionClosed}_{II}=1,&\mathsf{DIRECTED}.
\end{cases}
\end{aligned}}$$

For an explicit triangulation/gap-illumination claim additionally require

$$\boxed{R_1(\omega)=1\land R_2(\omega)=1.}$$

Only if $\mathsf L_{\rm pre}=1$ may the trial commit $\mathcal P_{\rm SUN}^{(0)}$.

For SET mode,

$$\boxed{\mathcal P_{\rm SUN}^{(0)}=\mathcal C_{{\rm SUN},\tau}^{\rm eval}.}$$

For PROBABILISTIC mode,

$$\boxed{\mathcal P_{\rm SUN}^{(0)}=P_{{\rm SUN},\tau}.}$$

At commitment:

$$\boxed{\mathbf{MODELING\ STOPS}.}$$

No target, registration, model, adapter, optional mechanism, tolerance, equivalence relation, truth/acquisition protocol, stopping rule, probability constructor, loss, or scoring rule may change afterward.

---

# XII. REVEAL / ACQUISITION AND PROVENANCE CLOSURE

The common abstract reveal is

$$\boxed{\mathsf{Reveal}=\begin{cases}
\mathsf{Reveal}_{\rm static},&\mathsf{SEALED},\\
\mathsf{Reveal}_{\rm acquisition},&\mathsf{DIRECTED}.
\end{cases}}$$

Type I opens truth already present in the sealed truth object. Type II adjudicates evidence legitimately acquired after commitment. Both are one-way transitions and neither permits remapping.

## XII.A Acquisition evidence dependencies

For directed trials freeze $\mathcal L_{\rm eviddep}^{(0)}$ and $\operatorname{Verify}_{\rm eviddep}$.

For every acquired evidence object $e$, record

$$\boxed{\operatorname{prov}(e)=(\text{source},t_{\rm acq}(e),\text{acquisition operation},\text{protocol run},\text{integrity digest}).}$$

Define the answer-bearing dependency set through the frozen extractor:

$$\boxed{\Lambda_{\rm evid}^{\star}=\operatorname{Dep}^{*}_{\mathcal L_{\rm eviddep}^{(0)}}(E_{\rm adjudicate},z_{\rm true}).}$$

Define

$$\boxed{\operatorname{VerifyProv}(e)=1}$$

iff the source identity, acquisition time, acquisition operation, protocol-run identity, and integrity digest in $\operatorname{prov}(e)$ verify under the frozen provenance verifier.

Define $\Delta\mathscr D_{\rm acq}$ as those admissible evidence objects that entered through the committed $\Gamma_{\rm search}$ after commitment with $\operatorname{VerifyProv}(e)=1$.

Then

$$\boxed{\mathsf{AcquisitionNovel}=1}$$

iff every $e\in\Lambda_{\rm evid}^{\star}$ has $\operatorname{VerifyProv}(e)=1$, entered through the committed acquisition protocol after $t_{\rm commit}$, and was unavailable to the prediction process under $K_{\rm pred}^{+}$. Novelty refers to the trial's epistemic access, not the age of the fact.

## XII.B Post-outcome integrity predicates

Let $\mathcal T_{\rm acq}$ denote the immutable acquisition trace.

$$\boxed{\mathsf{ProtocolCompliant}=1\iff\exists\pi_{\rm acq}:\operatorname{Verify}_{\rm acq}(\pi_{\rm acq},\Gamma_{\rm search},\mathcal T_{\rm acq})=1.}$$

$$\boxed{\mathsf{StopRuleCompliant}=1\iff\operatorname{Verify}_{\rm stop}(\mathcal T_{\rm acq},\tau_{\rm stop})=1.}$$

Let $E_{\rm adjudicate}$ either return one registered target evaluation class $z_{\rm true}$ or the explicit sentinel $\mathbf{SEARCH\mbox{-}EXHAUSTED\mbox{-}UNRESOLVED}$. Define

$$\boxed{\mathsf{AdjudicationValid}=1\iff z_{\rm true}\text{ is a registered target evaluation class}\land\operatorname{Verify}_{\rm adj}(E_{\rm adjudicate},\Delta\mathscr D_{\rm acq},z_{\rm true})=1.}$$

A protocol-compliant unresolved sentinel is recorded in $\mathcal J_0$ but does not satisfy $\mathsf{AdjudicationValid}$ and therefore cannot produce $\mathsf L_{\rm eval}=1$.

For Type I the static truth is

$$\boxed{z_{\rm true}=\Gamma(\mathscr D),\qquad\Gamma\in\mathfrak\Gamma_T^{(0)},}$$

with every admissible $\Gamma$ required to yield the same $\approx_T^{\rm eval}$ class. Define

$$\boxed{\mathsf{RevealIntegrity}=1}$$

iff the committed dataset/oracle identities match the revealed objects, exactly one frozen oracle execution is used, and it produces the recorded $z_{\rm true}$.

---

# XIII. TEMPORAL CERTIFICATE

Freeze event identities and timestamps

$$\boxed{t_{\rm type},t_{\rm sel},t_{\rm pre},t_{\rm commit},t_{\rm reveal},t_{\rm acq}(e),t_{\rm stop},t_{\rm eval}.}$$

For Type I the completed trace must satisfy

$$\boxed{t_{\rm type}<t_{\rm pre}<t_{\rm commit}<t_{\rm reveal}\le t_{\rm eval}.}$$

For Type II the completed trace must satisfy

$$\boxed{t_{\rm type}\le t_{\rm sel}<t_{\rm pre}<t_{\rm commit}<t_{\rm acq}(e)\le t_{\rm stop}\le t_{\rm eval}}$$

for every answer-bearing $e$.

Define

$$\boxed{\mathsf{TemporalOrderValid}\iff\exists\pi_{\rm time}:\operatorname{Verify}_{\rm temporal}(\pi_{\rm time})=1.}$$

$\mathsf{TemporalPreValid}$ is the prereveal prefix certificate available at $t_{\rm pre}$. Define

$$\boxed{\mathsf{TemporalPostValid}=\mathsf{TemporalOrderValid}}$$

for the completed trace establishing the applicable full ordering above.

---

# XIV. EVALUATION VALIDITY AND POST-OUTCOME LICENSE

For Type I,

$$\boxed{\mathsf{EvaluationValid}_{I}=\mathsf{RevealIntegrity}\land\mathsf{TemporalPostValid}.}$$

For Type II,

$$\boxed{\mathsf{EvaluationValid}_{II}=\mathsf{AcquisitionNovel}\land\mathsf{ProtocolCompliant}\land\mathsf{StopRuleCompliant}\land\mathsf{AdjudicationValid}\land\mathsf{TemporalPostValid}.}$$

Dispatch

$$\boxed{\mathsf{EvaluationValid}_{\tau}=\begin{cases}\mathsf{EvaluationValid}_{I},&\mathsf{SEALED},\\\mathsf{EvaluationValid}_{II},&\mathsf{DIRECTED}.\end{cases}}$$

The post-outcome evaluation license is

$$\boxed{\mathsf L_{\rm eval}(\omega)=\mathsf L_{\rm pre}(\omega)\land\mathsf{EvaluationValid}_{\tau}(\omega).}$$

Thus

$$\boxed{\text{PRECOMMIT CLOSURE}\rightarrow\mathsf L_{\rm pre}\rightarrow\mathbf{COMMIT}\rightarrow\mathbf{MODELING\ STOPS}\rightarrow\text{REVEAL/ACQUIRE}\rightarrow\mathsf{EvaluationValid}\rightarrow\mathsf L_{\rm eval}\rightarrow\text{SCORE}.}$$

---

# XV. RETENTION AND INFORMATION

For SET mode,

$$\boxed{\operatorname{Retain}_T(\omega)=\mathbf1[[z_{\rm true}]_{\rm eval}\in\mathcal C_{{\rm SUN},\tau}^{\rm eval}].}$$

For PROBABILISTIC mode,

$$\boxed{\operatorname{Retain}_T(\omega)=\mathsf{RetainRule}_T(P_{{\rm SUN},\tau},z_{\rm true}).}$$

No remapping is permitted.

## XV.A Core answer information

For Type I SET mode,

$$\boxed{G_T=1-\frac{\mathcal U_T(\mathcal C_{{\rm SUN},I}^{\rm eval})}{\mathcal U_T(\mathcal C_{0,I}^{\rm eval})}.}$$

For Type II SET mode,

$$\boxed{G_T\mid E_{\rm sel}=1-\frac{\mathcal U_T(\mathcal C_{{\rm SUN},II}^{\rm eval}\mid E_{\rm sel})}{\mathcal U_T(\mathcal C_{0,II}^{\rm eval}\mid E_{\rm sel})}.}$$

For finite equally weighted sets, the corresponding cardinality ratio may be used.

For PROBABILISTIC mode use the preregistered strictly proper loss:

$$\boxed{G_{T,I}=\ell_T(P_{{\rm native},I},z_{\rm true})-\ell_T(P_{{\rm SUN},I},z_{\rm true}),}$$

$$\boxed{G_{T,II}=\ell_T(P_{{\rm native},II},z_{\rm true})-\ell_T(P_{{\rm SUN},II},z_{\rm true}).}$$

Define the common answer-information score

$$\boxed{G_{\rm core}(\omega)=\begin{cases}
G_T,&\mathsf{SEALED}\land m_T=\mathrm{SET},\\
G_T\mid E_{\rm sel},&\mathsf{DIRECTED}\land m_T=\mathrm{SET},\\
G_{T,I},&\mathsf{SEALED}\land m_T=\mathrm{PROBABILISTIC},\\
G_{T,II},&\mathsf{DIRECTED}\land m_T=\mathrm{PROBABILISTIC}.
\end{cases}}$$

## XV.B Directed gap information

For directed trials define

$$\boxed{G_{\rm gap}=1-\frac{\mathcal U_{\rm gap}(\mathcal X_{\rm gap}^{\rm SUN})}{\mathcal U_{\rm gap}(\mathcal X_{\rm gap}^{0})}.}$$

For finite equally weighted gap sets,

$$\boxed{G_{\rm gap}=1-\frac{|\mathcal X_{\rm gap}^{\rm SUN}|}{|\mathcal X_{\rm gap}^{0}|}.}$$

$G_{\rm gap}$ and $G_{\rm core}$ are distinct quantities and may not be summed without a separately preregistered information measure.

---

# XVI. INDIVIDUAL OUTCOME TAXONOMY

A trial is eligible for empirical scoring only when $\mathsf L_{\rm eval}=1$.

A licensed retained informative result satisfies

$$\boxed{\mathsf L_{\rm eval}=1\land\operatorname{Retain}_T=1\land G_{\rm core}>0.}$$

A licensed reality-retaining but answer-noninformative result satisfies

$$\boxed{\mathsf L_{\rm eval}=1\land\operatorname{Retain}_T=1\land G_{\rm core}\le0.}$$

A licensed miss satisfies

$$\boxed{\mathsf L_{\rm eval}=1\land\operatorname{Retain}_T=0.}$$

For directed trials report separately

$$\boxed{R_1(\omega)=\mathsf{RegistrationReduced}(\omega),\quad R_2(\omega)=\mathsf{GapIlluminated}(\omega),\quad R_3(\omega)=\operatorname{Retain}_T(\omega).}$$

Thus registration failure is $R_1=0$; gap failure is $R_1=1,R_2=0$; a genuine directed predictive miss is $R_1=R_2=1,R_3=0$; and directed success is $R_1=R_2=R_3=1$, with answer-level information still reported separately through $G_{\rm core}$.

$\mathbf{SEARCH\mbox{-}EXHAUSTED\mbox{-}UNRESOLVED}$ is neither silently discarded nor promoted to confirmation.

---

# XVII. CANDIDATE-SEARCH LEDGER

The frozen empirical program maintains an immutable ledger

$$\boxed{\mathcal J_0.}$$

It records

$$\boxed{\text{ALL SCREENED CANDIDATES}\rightarrow\text{ALL DETECTED ALIGNMENTS}\rightarrow\text{ALL ADMISSIBLE REGISTRATIONS}\rightarrow\text{ALL TARGET-SELECTION EVENTS}\rightarrow\text{ALL LICENSE DECISIONS}\rightarrow\text{ALL ACQUISITION ATTEMPTS}\rightarrow\text{ALL OUTCOMES}.}$$

Failed alignments, nonqualifying candidates, unresolved acquisition attempts, and licensed misses do not disappear.

Define

$$\boxed{\mathsf{DirectedQualified}(\omega)=1}$$

iff the frozen candidate-search rules classify the candidate as $\mathsf{DIRECTED}$ and all preregistered eligibility/anchor-admissibility requirements are satisfied without conditioning on $R_1$.

---

# XVIII. FROZEN CROSS-DOMAIN TEST PROGRAM

Freeze a domain-class map

$$\boxed{\kappa:D\rightarrow\mathcal K_0}$$

before outcomes are observed. Classes in $\mathcal K_0$ must be defined in native disciplinary terms rather than constructed from SUN similarities.

Using the precommit license, require genuine positive-probability licensed coverage in at least two independently defined domain classes:

$$\boxed{\left|\left\{k\in\mathcal K_0:\Pr_{\Pi_0}[\mathsf L_{\rm pre}=1\land\kappa(D)=k]>0\right\}\right|\ge2.}$$

Define

$$\boxed{\mathsf{CrossDomainCoverage}_{\rm pre}=1}$$

iff the above condition holds.

---

# XIX. FROZEN CORE-GRAMMAR COVERAGE

Retain the V1-B core clause set exactly:

$$\boxed{\mathcal Q_{\rm core}=\{R,L,RL,3G,\mathcal B,\mathcal I{\rm -closure},\Delta g,{\rm provenance\mbox{-}reachability}\}.}$$

To avoid collision with the optional displacement coordinate $\chi_{\rm disp}$, denote V1-B's clause-coverage map by $\chi_{\rm core}$:

$$\boxed{\chi_{\rm core}(r)\subseteq\mathcal Q_{\rm core}.}$$

Define trial-level coverage by intersection:

$$\boxed{\chi_{\rm core}(\omega)=\bigcap_{r\in\mathfrak R_{D,\tau}^{(0)}}\chi_{\rm core}(r).}$$

Require

$$\boxed{\forall q\in\mathcal Q_{\rm core},\quad\Pr_{\Pi_0}[\mathsf L_{\rm pre}=1\land q\in\chi_{\rm core}(\omega)]>0.}$$

Define $\mathsf{CoreGrammarCoverage}_{\rm pre}=1$ iff the above condition holds.

---

# XX. POPULATION HYPOTHESES

Licensability is independent of information gain:

$$\boxed{\begin{aligned}H_{\rm licensability}^{+}:\quad&\Pr_{\Pi_0}[\mathsf L_{\rm pre}=1]>0\\
&\land\mathsf{CrossDomainCoverage}_{\rm pre}=1\\
&\land\mathsf{CoreGrammarCoverage}_{\rm pre}=1.
\end{aligned}}$$
Universal retention is evaluated only on post-outcome-valid trials:

$$\boxed{H_{\rm retention}:\forall\omega\in\Omega_0,\quad\mathsf L_{\rm eval}(\omega)=1\Longrightarrow\operatorname{Retain}_T(\omega)=1.}$$

Thus any actual trial with $\mathsf L_{\rm eval}=1\land\operatorname{Retain}_T=0$ implies $\neg H_{\rm retention}$.

The information hypothesis includes an explicit denominator guard:

$$\boxed{H_{\rm information}:\Pr_{\Pi_0}[\mathsf L_{\rm eval}=1]>0\land\mathbb E_{\omega\sim\Pi_0}[G_{\rm core}(\omega)\mid\mathsf L_{\rm eval}(\omega)=1]>0.}$$

For directed behavior define population hypotheses

$$\boxed{H_1:\Pr[\mathsf{DirectedQualified}=1]>0\land\Pr[R_1=1\mid\mathsf{DirectedQualified}=1]>0,}$$

$$\boxed{H_2:\Pr[R_1=1]>0\land\Pr[R_2=1\mid R_1=1]>0,}$$

$$\boxed{H_3:\forall\omega,\quad(\mathsf{TrialType}(\omega)=\mathsf{DIRECTED}\land\mathsf L_{\rm eval}(\omega)=1)\Longrightarrow R_3(\omega)=1.}$$

and

$$\boxed{H_{\rm directed}=H_1\land H_2\land H_3.}$$

Define $H_{\rm triangulation}$ as the registered family hypothesis that there exists a preregistered anchor-rank threshold $\rho_\star$ with positive-probability eligible coverage for which sufficiently independent partial registrations produce nonzero rates of $R_1$ and, conditional on $R_1$, $R_2$. The value of $\rho_\star$ is not fixed to three by definition and remains empirical.

$H_{\rm displacement}$ remains a candidate mechanism, outside $H_{\rm SUN}^{\rm core}$, outside generic Type-II licensure, and outside $H_{\rm directed}$ unless explicitly preregistered in a particular mechanism test.

---

# XXI. FULL FORMALIZED SUN V1-D HYPOTHESIS

The core scientific hypothesis remains

$$\boxed{H_{\rm SUN}^{\rm core}=H_{\rm grammar}\land H_{\rm licensability}^{+}\land H_{\rm retention}\land H_{\rm information}.}$$

V1 D adds the separately testable directed-discovery hypothesis $H_{\rm directed}$ without making it a prerequisite for valid Type-I trials.

The compact V1-D claim is:

$$\boxed{\begin{gathered}
\textbf{A FIXED DOMAIN-INDEPENDENT RELATIONAL TRANSITION GRAMMAR EXISTS.}\\[1mm]
\textbf{IT MAY BE TESTED THROUGH TWO DISTINCT NONINTERVENTIONAL PREDICTIVE TOPOLOGIES.}\\[1mm]
\textbf{IN SEALED-STATE TRIALS, SUN MUST CONSTRAIN AN ANSWER THAT ALREADY EXISTS}\\
\textbf{INSIDE A FIREWALLED TRUTH-BEARING OBJECT.}\\[1mm]
\textbf{IN REGISTRATION-DIRECTED TRIALS, KNOWN PARTIAL STRUCTURE MAY FIRST}\\
\textbf{CONSTRAIN WHICH UNRESOLVED GAP SHOULD BE TESTED, AFTER WHICH SUN MUST}\\
\textbf{COMMIT WHAT IT EXPECTS BEFORE NEW EVIDENCE IS ACQUIRED.}\\[1mm]
\textbf{ALL ADMISSIBLE NATIVE MODELS, REGISTRATIONS, AND SUN REALIZATIONS}\\
\textbf{MUST BE EXHAUSTED UNDER FROZEN VERIFIERS BEFORE COMMITMENT.}\\[1mm]
\textbf{TARGET SELECTION AND TARGET-ANSWER INFORMATION ARE SCORED SEPARATELY.}\\[1mm]
\textbf{AFTER COMMITMENT, KNOWLEDGE MAY INCREASE, BUT THE PREDICTION MAY NOT CHANGE.}\\[1mm]
\textbf{EVERY EVALUATION-LICENSED PREDICTION MUST RETAIN THE SUBSEQUENTLY}\\
\textbf{REVEALED OR ACQUIRED REALITY WITHOUT REMAPPING.}
\end{gathered}}$$

Most compactly:

$$\boxed{\textbf{SUN MAY CONSTRAIN AN UNKNOWN ANSWER}}$$

or, in its stronger directed form,

$$\boxed{\textbf{SUN MAY CONSTRAIN WHICH UNKNOWN TO INVESTIGATE, THEN CONSTRAIN WHAT SHOULD BE FOUND THERE.}}$$

---

# XXII. OPERATIONAL PROTOCOLS

## XXII.A SEALED

$$\boxed{\begin{array}{c}
\textbf{SELECT SEALED CANDIDATE}\\
\downarrow\\
\textbf{FREEZE TARGET + ORACLE LANGUAGE}\\
\downarrow\\
\textbf{CLOSE ORACLES + DISCOVERY LEDGER}\\
\downarrow\\
\textbf{BUILD DEPENDENCY FIREWALL + MASK}\\
\downarrow\\
\textbf{CLOSE NATIVE MODELS + VERIFY HEADROOM}\\
\downarrow\\
\textbf{EXHAUST SUN REALIZATIONS + VERIFY NONVACUITY}\\
\downarrow\\
\mathsf L_{\rm pre}\\
\downarrow\\
\textbf{COMMIT}\\
\downarrow\\
\boxed{\mathbf{MODELING\ STOPS}}\\
\downarrow\\
\textbf{STATIC REVEAL}\\
\downarrow\\
\mathsf{EvaluationValid}_{I}\\
\downarrow\\
\mathsf L_{\rm eval}\\
\downarrow\\
\textbf{RETENTION + INFORMATION SCORE}.
\end{array}}$$

## XXII.B DIRECTED

$$\boxed{\begin{array}{c}
\textbf{SCREEN UNDER FROZEN CANDIDATE RULE + RECORD IN }\mathcal J_0\\
\downarrow\\
\textbf{CLOSE ALL PARTIAL REGISTRATIONS + MEASURE CONSTRAINT RANK}\\
\downarrow\\
\textbf{DERIVE GAP UNDER }F_{\rm gap}\\
\downarrow\\
\textbf{FREEZE }E_{\rm sel}\textbf{ + GIVE SAME TARGET IDENTITY TO NATIVE BASELINE}\\
\downarrow\\
\textbf{VERIFY TARGET TRUTH STILL UNKNOWN}\\
\downarrow\\
\textbf{CLOSE NATIVE MODELS + EXHAUST ALL SUN REALIZATIONS}\\
\downarrow\\
\textbf{FREEZE }\Gamma_{\rm search}\textbf{ + STOPPING/ADJUDICATION RULES}\\
\downarrow\\
\mathsf L_{\rm pre}\\
\downarrow\\
\textbf{COMMIT}\\
\downarrow\\
\boxed{\mathbf{MODELING\ STOPS}}\\
\downarrow\\
\textbf{ACQUIRE ONLY UNDER FROZEN PROTOCOL}\\
\downarrow\\
\textbf{STOP BY RULE + ADJUDICATE}\\
\downarrow\\
\mathsf{EvaluationValid}_{II}\\
\downarrow\\
\mathsf L_{\rm eval}\\
\downarrow\\
\textbf{SCORE }R_1,R_2,R_3,G_{\rm gap},G_{\rm core}.
\end{array}}$$

---

# XXIII. NORMATIVE SYMBOL REGISTRY

The following registry is normative for lock auditing.

| Symbol / predicate | Definition locus |
|---|---|
| $\mathcal G_{\rm SUN},R,L,\mathcal C,\mathcal B,\mathcal I,h,g,H_{\rm grammar}$ | I |
| $\Sigma_0,\nu_0,\Omega_0,\Pi_0,\tau,Q_\tau,\mathsf{TrialTypeClosed},\mathfrak D_{\rm SUN}^{(0)}$ | III |
| $\omega_{\rm reg},\Theta_{\rm reg},\omega_{0,B}^{+},\omega_{0,D}^{+},\Theta_0,\Theta_D,\mathcal V_0,\mathcal V_D,m_T,\Psi_T^{(0)},\ell_T,\mathcal U_{\rm gap}$ | IV |
| $Q_X,\operatorname{ClosureStatus}$ | V |
| $K_{\rm reg},K_{\rm pred},K_{\rm acq},K_{\rm pred}^{+},Q_K,\mathsf{DiscoveryBlind}_T$ | VI |
| $\mathfrak M_D^{(0)},Q_D^M,\mathfrak G_D^{(0)}(M)$ | VII |
| $\mathfrak\Gamma_T^{(0)},Q_T^\Gamma,\Lambda_T^\star,\mu_T^\star,E_T,\operatorname{NONINTERFERENCE}$ | VIII |
| $\mathsf{NativeClosed}_I,H_{D,I},\mathfrak R_{D,I}^{(0)},Q_{D,I}^{R},\equiv_{T,I},\mathsf{RealizationClosed}_I,\mathsf{ConstraintActive}_I$ | VIII |
| $\mathfrak A_D^{(0)},Q_D^{\rm anchor},\mathsf{AnchorClosed},\rho_{\rm anchor},\mathfrak R_D^{\rm prior},\mathfrak R_D^{\rm anchor},R_1,F_{\rm gap},E_{\rm sel},Q_{\rm gap},\mathsf{GapDerived}$ | IX |
| $\mathsf{NativeClosed}_{II},H_{D,II},\mathcal X_{\rm gap}^{0},\mathcal X_{\rm gap}^{\rm SUN},\mathsf{LocationGain},\mathsf{ClassGain},R_2$ | IX |
| $\mathfrak R_{D,II}^{(0)},Q_{D,II}^{R},\equiv_{T,II},\mathsf{RealizationClosed}_{II},\mathsf{ConstraintActive}_{II}$ | IX |
| $\Gamma_{\rm search},\mathscr S,P_{\rm acq},\tau_{\rm stop},V_{\rm evidence},E_{\rm adjudicate},\mathsf{AcquisitionClosed}_{II}$ | IX |
| $\mathsf{TruthChannelReady},\mathsf{NativeClosed}_\tau,H_{D,\tau},Q_{D,\tau}^{R},\mathsf{RealizationClosed}_\tau,\mathsf{ConstraintActive}_\tau,\mathcal C_{{\rm SUN},\tau}^{\rm eval},P_{{\rm SUN},\tau},P_{{\rm native},\tau}$ | X |
| $t_{\rm pre},\mathsf{TemporalPreValid},\mathsf L_{\rm pre},\mathcal P_{\rm SUN}^{(0)}$ | XI |
| $\mathcal L_{\rm eviddep}^{(0)},\operatorname{Verify}_{\rm eviddep},\Lambda_{\rm evid}^{\star},\operatorname{prov},\operatorname{VerifyProv},\Delta\mathscr D_{\rm acq},\mathsf{AcquisitionNovel}$ | XII |
| $\mathcal T_{\rm acq},\mathsf{ProtocolCompliant},\mathsf{StopRuleCompliant},\mathsf{AdjudicationValid},\mathsf{RevealIntegrity}$ | XII |
| $t_{\rm type},t_{\rm sel},t_{\rm commit},t_{\rm reveal},t_{\rm acq},t_{\rm stop},t_{\rm eval},\mathsf{TemporalOrderValid},\mathsf{TemporalPostValid}$ | XIII |
| $\mathsf{EvaluationValid}_I,\mathsf{EvaluationValid}_{II},\mathsf{EvaluationValid}_\tau,\mathsf L_{\rm eval}$ | XIV |
| $\operatorname{Retain}_T,G_{\rm core},G_{\rm gap}$ | XV |
| $R_3$ | XVI |
| $\mathcal J_0,\mathsf{DirectedQualified}$ | XVII |
| $\kappa,\mathcal K_0,\mathsf{CrossDomainCoverage}_{\rm pre}$ | XVIII |
| $\mathcal Q_{\rm core},\chi_{\rm core},\mathsf{CoreGrammarCoverage}_{\rm pre}$ | XIX |
| $H_{\rm licensability}^{+},H_{\rm retention},H_{\rm information},H_1,H_2,H_3,H_{\rm directed},H_{\rm triangulation},\rho_\star,H_{\rm displacement}$ | XX |

Local bound variables such as $s,z,M,G,A,r,e,d,d'$ are scoped by their defining expressions and are not global symbols.

---

# XXIV. LOCK STATEMENT

SUN V1 D is a formal hypothesis and dual-topology test harness. It does not by itself constitute an empirical prediction.

No empirical prediction exists for a concrete trial until $\mathsf L_{\rm pre}=1$ and $\mathcal P_{\rm SUN}^{(0)}$ is immutably committed. No empirical support or falsification is scored unless $\mathsf L_{\rm eval}=1$.

The architecture is frozen as:

$$\boxed{\text{V1-B exact grammar and scientific severity}+\text{V1-D dual topology}+\text{temporal }(\mathsf L_{\rm pre},\mathsf L_{\rm eval})\text{ licensing}.}$$