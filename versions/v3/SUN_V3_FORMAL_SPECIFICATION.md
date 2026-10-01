$$
\boxed{
F_{3}:\;
\mathcal M^{\star}_{\mathrm{MUSIC}}
\;\longrightarrow\;
\mathfrak S_{\mathrm{SUN}}^{(3)}
}
$$

$$
\boxed{
\mathfrak S_{\mathrm{SUN}}^{(3)}
:=
\Bigl(
\mathfrak H;\;
\mathcal Q,\;
\mathcal R_{\mathrm{int}},\;
D_{R},\;
g;\;
\mathsf{Ctor}_{3},\;
\mathsf{Act}_{7},\;
\mathsf{Rel}_{12};\;
\Pi_{231};\;
\mathsf{Addr}_{72};\;
\sigma_{3}
\Bigr)
}
$$

---

## 0. Constitutional rule

$$
\boxed{
\mathcal M^{\star}_{\mathrm{MUSIC}}
\;\neq\;
\mathfrak S_{\mathrm{SUN}}^{(3)}
}
$$

Every constitutive component of $\mathfrak S_{\mathrm{SUN}}^{(3)}$ must satisfy at least one of:

$$
\boxed{
\text{(a) be derived from a music-native relation in }
\mathcal M^{\star}_{\mathrm{MUSIC}},
}
$$

$$
\boxed{
\text{(b) be an explicitly defined formal representation whose applicability
to a declared musical subdomain is demonstrated.}
}
$$

Scope typing:

$$
\boxed{
\sigma_{3}:\;
\operatorname{Comp}\!\left(\mathfrak S_{\mathrm{SUN}}^{(3)}\right)
\;\longrightarrow\;
\operatorname{Sub}\!\left(\mathcal M^{\star}_{\mathrm{MUSIC}}\right)
}
$$

where $\operatorname{Comp}(\cdot)$ denotes the formal components, operators, and relation types of the specification, and $\operatorname{Sub}(\cdot)$ denotes structured music-native subobjects.

Examples:

$$
\sigma_{3}(\mathcal Q_{n})
=
\mathcal M^{\star}_{\mathrm{relative\;pitch}},
$$

$$
\sigma_{3}(K)
=
\mathcal M^{\star}_{\mathrm{conditional\;expectation}}.
$$

Scope law:

$$
\boxed{
c \in \operatorname{Comp}\!\left(\mathfrak S_{\mathrm{SUN}}^{(3)}\right)
\;\Longrightarrow\;
c \text{ may make claims only over } \sigma_{3}(c).
}
$$

No component of $\mathfrak S_{\mathrm{SUN}}^{(3)}$ is asserted as a universal law of all music beyond its $\sigma_{3}$-image.

---

## 1. Harmonic algebra

$$
X := \mathbb R_{>0}
$$

$$
R, L, O : X \to X
$$

$$
\boxed{\;
R(x) = \tfrac{2}{3}\,x,\qquad
L(x) = \tfrac{3}{4}\,x,\qquad
O(x) = \tfrac{1}{2}\,x
\;}
$$

$$
\kappa_{\mathrm{cl}} : X \times X \times X \to X,
\qquad
\kappa_{\mathrm{cl}}(c, r, l) := \frac{r\,l}{c}
$$

$$
\boxed{\;
\mathfrak H
=
\Bigl\langle
X;\,
R,\,L,\,O,\,\kappa_{\mathrm{cl}}
\;\Bigm|\;
R L = L R = O,\;
\kappa_{\mathrm{cl}}(x, R x, L x) = O x
\Bigr\rangle
\;}
$$

Logarithmic coordinates:

$$
\ell_{R} := \log_{2}\tfrac{2}{3},\qquad
\ell_{L} := \log_{2}\tfrac{3}{4},\qquad
\ell_{O} := \log_{2}\tfrac{1}{2} = -1
$$

$$
\boxed{\;
\ell_{R} + \ell_{L} = \ell_{O} = -1
\;}
$$

Group and forward-monoid readings:

$$
\boxed{\;
\langle R, L\rangle_{\mathrm{grp}}
\;\cong\;
\mathbb Z^{2}
\quad
\text{with basis}
\quad
(1,-1),\ (-2,1),
\;}
$$

$$
\boxed{\;
\langle R, L\rangle_{+}
\;\cong\;
\mathbb N_{0}^{2}.
\;}
$$

---

## 2. Relational pitch structure

For pitches $f_{i} \in X$:

$$
\boxed{\;
r_{ij} = \frac{f_{j}}{f_{i}},
\qquad
d_{ij} = \log_{2} r_{ij}.
\;}
$$

Path-compatible composition:

$$
\boxed{\;
r_{ij} \circ r_{jk} := r_{ik},
\qquad
d_{ij} \oplus d_{jk} := d_{ik}.
\;}
$$

Equivalently:

$$
\boxed{\;
r_{ik} = r_{ij}\,r_{jk},
\qquad
d_{ik} = d_{ij} + d_{jk}.
\;}
$$

Relational pitch quotient:

$$
\boxed{\;
\mathcal Q_{n}
=
\mathbb R^{n} \;/\; \operatorname{span}(\mathbf 1),
\;}
$$

$$
\boxed{\;
D_{R} = n - 1
\quad
\text{for an unconstrained } n\text{-pitch configuration modulo global transposition.}
\;}
$$

Interval/composition structure:

$$
\boxed{\;
\mathcal R_{\mathrm{int}}
:=
\left(
\mathcal I_{\times},\;
\mathcal I_{+},\;
\log_{2}
\right)
\;}
$$

with:

$$
\mathcal I_{\times}
:=
\bigl(\,\{r_{ij}\},\ \circ\,\bigr),
\qquad
\mathcal I_{+}
:=
\bigl(\,\{d_{ij}\},\ \oplus\,\bigr),
$$

and:

$$
\boxed{\;
\log_{2}:\;
\mathcal I_{\times}
\;\longrightarrow\;
\mathcal I_{+}
\;}
$$

satisfying:

$$
\boxed{\;
\log_{2}\!\bigl(r_{ij} \circ r_{jk}\bigr)
=
\log_{2} r_{ij} \;\oplus\; \log_{2} r_{jk}.
\;}
$$

Equivalently, on the ambient algebras:

$$
\boxed{\;
(\mathbb R_{>0}, \cdot)
\;\xrightarrow[\cong]{\ \log_{2}\ }\;
(\mathbb R, +).
\;}
$$

Dimensional types are pairwise distinct:

$$
\boxed{\;
D_{R} \not\equiv D_{P},
\qquad
D_{R} \not\equiv D_{O},
\qquad
D_{P} \not\equiv D_{O}.
\;}
$$

$\not\equiv$ denotes type non-identity; numerical coincidences are not presumed.

---

## 3. Generation

$$
\boxed{\;
C_{0} = F \in X,
\qquad
C_{g+1} = O(C_{g}) = \tfrac{1}{2} C_{g},
\qquad
C_{g} = 2^{-g} F.
\;}
$$

Generation index as descent from $F$:

$$
\boxed{\;
g \in \mathbb N_{0},
\qquad
g : \{C_{g}\}_{g \in \mathbb N_{0}} \to \mathbb N_{0},
\qquad
g(C_{g}) := g.
\;}
$$

---

## 4. Typed musical vocabulary

$$
\boxed{\;
\mathcal A_{22}
=
\mathsf{Ctor}_{3}
\;\sqcup\;
\mathsf{Act}_{7}
\;\sqcup\;
\mathsf{Rel}_{12}.
\;}
$$

$$
|\mathsf{Ctor}_{3}| = 3,
\qquad
|\mathsf{Act}_{7}| = 7,
\qquad
|\mathsf{Rel}_{12}| = 12,
\qquad
22 = 3 + 7 + 12.
$$

### 4.1 Constructors

$$
\mathsf{Ctor}_{3}
:=
\{\, E,\ \mathsf{Sieve},\ \mathsf{Joint} \,\}.
$$

$$
E(k, n)
\;\longmapsto\;
\text{cyclic } n\text{-slot pattern with } k \text{ evenly distributed onsets}.
$$

$$
\mathsf{Sieve}
=
\bigl\langle\,
M_{r}
\;\bigm|\;
\cup,\ \cap,\ \complement
\,\bigr\rangle,
\qquad
M_{r} := \{\, x \in \mathbb Z : x \equiv r \pmod M \,\}.
$$

$$
\mathsf{Joint}(x_{1}, \dots, x_{k})
\;\Rightarrow\;
M.
$$

### 4.2 Actions

$$
\mathsf{Act}_{7}
:=
\{\, S_{c},\; D_{12},\; \mathsf{Rev}_{n},\; m,\; \operatorname{Rot}_{k},\; A_{\delta},\; K \,\}.
$$

$$
S_{c}(x) = c\,x,
\qquad
c > 0.
$$

$$
D_{12}
=
\bigl\langle\, s, t
\;\bigm|\;
s^{12} = e,\;
t^{2} = e,\;
t s t = s^{-1}
\,\bigr\rangle.
$$

$$
\mathsf{Rev}_{n}(x)_{j} = x_{n-1-j},
\qquad
\mathsf{Rev}_{n}^{2} = \operatorname{id}.
$$

$$
m : (\text{object}, a) \;\rightharpoonup\; (\text{same object}, b).
$$

$$
\operatorname{Rot}_{k}(x_{0}, \dots, x_{n-1})
=
(x_{k}, \dots, x_{k-1}).
$$

$$
A_{\delta} :
\text{source-qualified local duration operation,}
$$
$$
\boxed{\;
d_{i} \mapsto d_{i} + \delta
\quad\text{or insertion / rest / dot-derived duration, per native context.}
\;}
$$

$$
K(\text{context}, y)
=
P\bigl(\text{next} = y \mid \text{context}\bigr).
$$

### 4.3 Structural relations

$$
\mathsf{Rel}_{12}
:=
\bigl\{
\text{path},\
\text{cycle},\
\text{boundary},\
\text{reduction},
$$
$$
\qquad\;\;
\text{mapping},\
\text{invariant},\
\text{measure},\
\text{realization},
$$
$$
\qquad\;\;
\text{residual},\
\text{orbit},\
\text{address/history},\
\text{topology}
\bigr\}.
$$

Each is a typed relation on the state space; none is asserted as a generator.

---

## 5. Configuration space

$$
\boxed{\;
\Pi_{231}
:=
\bigl\{\, \{\alpha_{i}, \alpha_{j}\} : i < j,\ \alpha_{i}, \alpha_{j} \in \mathcal A_{22} \,\bigr\}.
\;}
$$

$$
\boxed{\;
|\Pi_{231}|
=
\binom{22}{2}
=
231.
\;}
$$

$\Pi_{231}$ is the complete unordered pair-space of the vocabulary. Membership is combinatorial; it is not asserted as an active musical relation.

---

## 6. Address layer

$$
\boxed{\;
\mathsf{Addr}_{72}
=
\mathbb Z_{12} \times \mathbb Z_{6}.
\;}
$$

$$
\boxed{\;
|\mathsf{Addr}_{72}|
=
72
=
3 \times 4 \times 6
=
3 \times 24.
\;}
$$

Three-coset partition of $\mathbb Z_{12}$:

$$
\{0,3,6,9\},\quad
\{1,4,7,10\},\quad
\{2,5,8,11\}.
$$

$\mathsf{Addr}_{72}$ is a representation layer; it is removable without altering $\mathfrak H$, $\mathcal Q_{n}$, $\mathcal A_{22}$, or $\Pi_{231}$.

---

## 7. Governing equations

$$
\boxed{
\begin{aligned}
\text{(i)}\quad & R \circ L = L \circ R = O \\[1mm]
\text{(ii)}\quad & \ell_{R} + \ell_{L} = -1 \\[1mm]
\text{(iii)}\quad & \kappa_{\mathrm{cl}}(x, R x, L x) = O x \\[1mm]
\text{(iv)}\quad & C_{g+1} = \tfrac{1}{2} C_{g},
\qquad
g \in \mathbb N_{0} \\[1mm]
\text{(v)}\quad & D_{R} \not\equiv D_{P},\;
D_{R} \not\equiv D_{O},\;
D_{P} \not\equiv D_{O} \\[1mm]
\text{(vi)}\quad & r_{ij} \circ r_{jk} = r_{ik},
\qquad
d_{ij} \oplus d_{jk} = d_{ik} \\[1mm]
\text{(vii)}\quad & |\mathcal A_{22}| = 3 + 7 + 12 = 22 \\[1mm]
\text{(viii)}\quad & |\Pi_{231}| = \binom{22}{2} = 231 \\[1mm]
\text{(ix)}\quad & |\mathsf{Addr}_{72}| = 3 \times 4 \times 6 = 3 \times 24 \\[1mm]
\text{(x)}\quad & c \in \operatorname{Comp}(\mathfrak S^{(3)})
\;\Rightarrow\;
c \text{ claims only over } \sigma_{3}(c)
\end{aligned}
}
$$

---

## 8. Compact form

$$
\boxed{
\begin{aligned}
F_{3} &:\ \mathcal M^{\star}_{\mathrm{MUSIC}}
\;\longrightarrow\;
\mathfrak S_{\mathrm{SUN}}^{(3)} \\[1.5mm]
\mathfrak S_{\mathrm{SUN}}^{(3)}
&=
\Bigl(
\mathfrak H;\;
\mathcal Q,\; \mathcal R_{\mathrm{int}},\; D_{R},\; g;\;
\mathsf{Ctor}_{3},\; \mathsf{Act}_{7},\; \mathsf{Rel}_{12};\;
\Pi_{231};\;
\mathsf{Addr}_{72};\;
\sigma_{3}
\Bigr) \\[1.5mm]
\mathfrak H
&=
\Bigl\langle
\mathbb R_{>0};\,
R, L, O, \kappa_{\mathrm{cl}}
\;\Bigm|\;
R L = L R = O,\;
\kappa_{\mathrm{cl}}(x, R x, L x) = O x
\Bigr\rangle \\[1mm]
R(x) &= \tfrac{2}{3} x,
\qquad
L(x) = \tfrac{3}{4} x,
\qquad
O(x) = \tfrac{1}{2} x \\[1mm]
\mathcal Q_{n} &= \mathbb R^{n} / \operatorname{span}(\mathbf 1),
\qquad
D_{R} = n - 1 \\[1mm]
\mathcal R_{\mathrm{int}} &= \bigl(\mathcal I_{\times},\ \mathcal I_{+},\ \log_{2}\bigr) \\[1mm]
\mathcal A_{22} &= \mathsf{Ctor}_{3} \sqcup \mathsf{Act}_{7} \sqcup \mathsf{Rel}_{12},
\qquad
22 = 3 + 7 + 12 \\[1mm]
|\Pi_{231}| &= \binom{22}{2} = 231 \\[1mm]
\mathsf{Addr}_{72} &= \mathbb Z_{12} \times \mathbb Z_{6},
\qquad
72 = 3 \times 4 \times 6 \\[1mm]
\sigma_{3} &:\ \operatorname{Comp}\!\left(\mathfrak S_{\mathrm{SUN}}^{(3)}\right)
\;\longrightarrow\;
\operatorname{Sub}\!\left(\mathcal M^{\star}_{\mathrm{MUSIC}}\right)
\end{aligned}
}
$$

---

## 9. Deferred semantics interface

Not part of the defining tuple; reserved for future specification:

$$
\boxed{\;
\models_{3}
\;\subseteq\;
\mathcal M^{\star}_{\mathrm{MUSIC}}
\times
\operatorname{Comp}\!\left(\mathfrak S_{\mathrm{SUN}}^{(3)}\right)
\;}
$$

with the consistency law:

$$
\boxed{\;
m \models_{3} c
\;\Longrightarrow\;
m \in \sigma_{3}(c).
\;}
$$

---

## 10. Sibling-branch architecture

$$
\boxed{
\begin{array}{ccc}
& \mathcal M^{\star}_{\mathrm{MUSIC}} & \\[1mm]
\swarrow F_{2} & & F_{3} \searrow \\[1mm]
\mathfrak S^{(2)} & & \mathfrak S^{(3)}
\end{array}
}
$$

$$
\boxed{\;
F_{4}:\;
\mathcal M^{\star}_{\mathrm{MUSIC}}
\;\longrightarrow\;
\mathfrak S_{\mathrm{SUN}}^{(4)}.
\;}
$$

$$
\boxed{
\text{Each } F_{k} \text{ starts from the same immutable music, not from any part of } \mathfrak S^{(j)},\ j < k.
}
$$

---

$$
\boxed{
\textbf{SUN V3 — standalone formal account of }
\mathcal M^{\star}_{\mathrm{MUSIC}}.
}
$$