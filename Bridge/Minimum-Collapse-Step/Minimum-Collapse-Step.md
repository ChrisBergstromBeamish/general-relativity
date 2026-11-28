# Minimum Collapse Step in an Accessible Region
*Full proof with Planck's constant as the action anchor*

**28 November 2026 · Version 1.0**

**Result.** Planck's constant supplies the action scale. In the mode comparison defined below, a finite upper bound \(E_D^{\rm cap}\) on the positive energy governing phase changes gives the observer-scoped bound
\[
\boxed{
r+c|\Delta t|\ge
\frac{(1-\eta_{\max})\hbar c}{E_D^{\rm cap}}>0.
}
\]
Here \(r=|\Delta\mathbf x|\), and the fourth coordinate counts as distance through \(c\Delta t\). For literal nonoverlap, use \(\eta_{\max}=0\), provided that nonoverlap is defined in the same comparison pairing.

This is a complete conditional theorem. The derivation does not require a uniform squared-gradient or second frequency-moment bound. Its physical application still requires the actual old/new-wave comparison law, a spatial phase relation, a finite bound on the same positive energy, and at least one permissible successor. A causal boundary and Planck's constant alone do not establish those conditions.

## 1. Scope

The comparison is between the same particle's previous configuration and a proposed next configuration. Both are expressed in one observer's clock and rulers. The previous wave is a comparison state, not another particle or an additional energy account.

Let \(D\) denote the observer's accessible domain and \(I\) the period of preparations and comparisons included in the claim. Let \(\mathcal C(D,I)\) be the class of physical configurations and transitions admitted there. The requested universality is only over this declared class.

Write the displacement as
\[
a=(\Delta\mathbf x,c\Delta t),\qquad r=|\Delta\mathbf x|.
\tag{1}
\]
The positive comparison distances used below are
\[
d_+(a)=r+c|\Delta t|,
\qquad
d_2(a)=\sqrt{r^2+c^2\Delta t^2}.
\tag{2}
\]
These are declared positive distances in the observer's comparison geometry. They are not silently identified with an indefinite spacetime interval.

If \(r=0\), the particle has still moved along \(M^1\) when \(\Delta t\ne0\). The proof includes that case. It does not require all four components of every step to be nonzero.

There are two distinct results:

- A proved bound for a specified family of phase-related candidate configurations.
- The physical identification of that family and its energy bound with all allowable collapses in the observable domain.

The first is completed here. The second is checked against the existing construction and its remaining premises are explicit.

## 2. Method

The earlier geometric proof used the squared derivatives of a normalized spacetime profile. This proof uses a different quantity: the **mean positive mode frequency**, which the existing action-energy formula relates to energy.

The chain is
\[
\text{packet action }Q\ge\hbar
\quad+\quad
E=\sum_j\omega_j|b_j|^2
\quad+\quad
E\le E_D^{\rm cap}
\]
\[
\Longrightarrow\quad
\text{bounded average phase change over a displacement}
\]
\[
\Longrightarrow\quad
\text{a nonzero displacement before the required overlap reduction}.
\tag{3}
\]

The proof is an explicit sum over classical wave coefficients. It does not import a quantum measurement postulate, a time-energy uncertainty formula, a Hamiltonian operator, or a preassigned minimum tick.

A normalized mode vector is sufficient. We do not normalize a persistent standing wave by integrating its unchanged amplitude over an infinite timeline. This avoids that particular divergent integral, but it also makes the physical comparison pairing a named requirement.

The overlap bound is necessary for an accepted successor. It is not an occurrence law, a sufficient admission test, or a guarantee that a successor exists.

## 3. Premises and the Planck anchor

### 3.1 Numerical and physical anchor

Use the Planck constant
\[
h=6.62607015\times10^{-34}\ {\rm J\,s}
\tag{4}
\]
and
\[
\hbar=\frac{h}{2\pi}
\approx1.0545718176461564\times10^{-34}\ {\rm J\,s}.
\tag{5}
\]
The value of \(h\) is exact in the present SI. The displayed decimal for \(\hbar\) is rounded. We also use the same-unit conversion
\[
c=299792458\ {\rm m\,s^{-1}}.
\tag{6}
\]
Source: [NIST, SI defining constants](https://www.nist.gov/pml/special-publication-330/sp-330-section-2), checked 28 November 2026.

These numerical anchors do not by themselves impose a length, energy ceiling, or causal boundary. In the current model, identifying the packet-action scale \(s_*\) with \(\hbar\) is the retained **CAL** premise. The geometric action-admission law and that calibration are separate inputs.

Angular frequency is measured in radians per second, so the relevant energy/action relation uses \(\hbar\), not \(h\). For cyclic frequency \(\nu=\omega/(2\pi)\), the same relation reads \(E=h\nu\) for an elementary pure mode.

### 3.2 Premise register

| ID | Statement | Status |
|---|---|---|
| A1 — Packet action | \(Q=\sum_j|b_j|^2=n\hbar\), with integer \(n\ge1\). | Retains G1's C-LIFT/C-DOMAIN and CAL. It applies to a complete packet, not independently to each coherent component. |
| A2 — Positive mode energy | \(E=\sum_j\omega_j|b_j|^2\), with \(\omega_j\ge0\) and finite \(E\). | Retained for the specified positive-frequency free modes. Application to a complete interaction must use its actual phase law. |
| A3 — Same-mode comparison | The candidate is represented in the same orthonormal comparison basis by \(b_j(a)=b_j\exp[i(\mathbf k_j\cdot\Delta\mathbf x-\omega_j\Delta t)]\). | A stated translation/phase law. Its full \(M^{3,1}\) application is not derived by internal action quantization alone. |
| A4 — Admissibility separation | Every accepted candidate obeys \(|A(a)|\le\eta\), for a specified \(0\le\eta<1\). | New proposed separation condition. Literal disjoint occupied support implies \(\eta=0\) only when support and \(A\) use the same comparison pairing. |
| A5 — Spatial phase bound | \(|\mathbf k_j|\le\omega_j/c\) for the relevant modes. | Additional spatial bridge. A causal boundary alone does not derive this spectral inequality. It is not merely a statement about a signal speed. |
| A6 — Domain resource bound | \(0<E\le E_D^{\rm cap}<\infty\) for every transition in \(\mathcal C(D,I)\). | Must bound the same positive phase-governing mode sum as A2, including relevant driving resources where required. |
| A7 — Common separation strength | \(\eta\le\eta_{\max}<1\) throughout the admitted class. | Automatic for the literal orthogonality consequence \(\eta=0\); otherwise must be derived or supplied. |
| A8 — Actual successors | Some candidates satisfying all physical conditions exist. | Separate from the lower-bound theorem. |

There is no requirement that every individual mode have action \(\hbar\). The weights of coherent components may be fractional, as in the current G1 construction.

## 4. Dependencies and compatibility

The source documents are:

- [G1 granularity object](https://chrisbergstrombeamish.github.io/general-relativity/Bridge/Granularity/): *A Granularity Tensor for the Internal Spin Geometry*.
- Granularity/collapse progress and dependency record (a working file, not published).
- [C1 collapse object](https://chrisbergstrombeamish.github.io/general-relativity/Bridge/Collapse/): *Collapse as a Complete Physical Event*.
- Earlier full geometric separation proof (not published).

G1 supplies the canonical coefficients and free-mode identities
\[
b_j=\sqrt{I\omega_j}\,a_j,\qquad
Q=\sum_j|b_j|^2,\qquad
E_{\rm free}=\sum_j\omega_j|b_j|^2.
\tag{7}
\]
With C-LIFT/C-DOMAIN and CAL, a nonzero admitted complete packet has \(Q\ge\hbar\).

This provides a genuine starting point for the time-phase calculation. It does not yet establish the spatial wavevectors, the complete old/new comparison rule, or the accessible-domain energy cap.

The canonical coefficients \(b_j\) and raw field coefficients \(a_j\) differ by frequency-dependent factors. Accordingly, the canonical action pairing cannot be silently replaced by an unweighted integral of the raw field amplitude when several frequencies are present. The physical support/overlap identification must use the same pairing as the proof.

C1 permits a finite state jump. Its actual interacting evolution can also differ from free-mode phase evolution. A1–A3 therefore need to be verified for the complete transition being tested; they cannot be inferred merely because the isolated packet satisfies G1.

The current ground doublet has one common frequency. A time translation multiplies that entire doublet by a common phase. Its amplitude overlap remains one for every delay. This is an explicit case where the lower-bound theorem does not supply an accepted next collapse.

## 5. Construction and full derivation

### 5.1 Normalize using packet action

Define
\[
p_j=\frac{|b_j|^2}{Q}.
\tag{8}
\]
Then
\[
p_j\ge0,\qquad \sum_jp_j=1.
\tag{9}
\]
Using A2,
\[
\overline\omega:=\sum_jp_j\omega_j=\frac EQ.
\tag{10}
\]
The Planck action floor gives
\[
\frac EQ\le\frac E\hbar\le\frac{E_D^{\rm cap}}{\hbar}.
\tag{11}
\]
This is an upper bound on the **mean** positive frequency. It is not a maximum frequency for each component.

The derivation applies to finite or countably infinite mode families provided the positive energy sum converges. A continuous mode measure gives the same argument with sums replaced by integrals.

### 5.2 Define the old/new overlap

Let
\[
\theta_j(a)=\mathbf k_j\cdot\Delta\mathbf x-\omega_j\Delta t.
\tag{12}
\]
By A3, the normalized amplitude pairing is
\[
A(a)=\frac1Q\sum_j\overline b_j\,b_j(a)
=\sum_jp_j e^{i\theta_j(a)}.
\tag{13}
\]
Consequently,
\[
A(0)=1,\qquad |A(a)|\le1.
\tag{14}
\]

To connect with literal occupied overlap, suppose the same normalized comparison configurations can be realized as functions
\[
\psi=\sum_j\frac{b_j}{\sqrt Q}\chi_j,\qquad
\psi_a=\sum_j\frac{b_j(a)}{\sqrt Q}\chi_j
\]
in a common orthonormal basis and measure. Then
\[
A(a)=\int\overline\psi\,\psi_a\,d\mu.
\tag{15}
\]
Disjoint occupied supports imply \(A=0\). More generally,
\[
|A(a)|\le\int|\psi|\,|\psi_a|\,d\mu=:B(a).
\tag{16}
\]
Thus a physical rule \(B(a)\le\eta\) implies the premise \(|A(a)|\le\eta\). The converse need not hold: complex phases may cancel while occupied regions overlap.

The theorem can therefore give a necessary bound for literal nonoverlap. It does not replace literal nonoverlap by phase cancellation when deciding whether a successor is actually allowed.

### 5.3 Derive the elementary phase inequality

For real \(\theta\),
\[
e^{i\theta}-1=\int_0^\theta i e^{is}\,ds.
\]
Taking the magnitude,
\[
\boxed{|e^{i\theta}-1|\le|\theta|.}
\tag{17}
\]
This elementary identity is the only phase-speed estimate needed.

From (13),
\[
1-A(a)=\sum_jp_j[1-e^{i\theta_j(a)}].
\]
The triangle inequality and (17) give
\[
|1-A(a)|\le\sum_jp_j|\theta_j(a)|.
\tag{18}
\]
All sums used in this estimate converge under the finite first moments below. No second frequency moment or frequency variance is assumed.

### 5.4 Include space and \(M^1\) in the same estimate

For each mode,
\[
|\theta_j|
\le|\mathbf k_j|\,r+\omega_j|\Delta t|.
\tag{19}
\]
Without any spatial dispersion assumption, this already gives
\[
|1-A(a)|\le
\overline k\,r+\frac EQ|\Delta t|,
\qquad
\overline k=\sum_jp_j|\mathbf k_j|.
\tag{20}
\]
A time bound alone does not control \(\overline k\). A5 supplies the additional relation
\[
\overline k\le\frac{\overline\omega}{c}=\frac{E}{Qc}.
\tag{21}
\]
Combining,
\[
\boxed{
|1-A(a)|\le\frac EQ
\left(|\Delta t|+\frac rc\right).
}
\tag{22}
\]

This is the displacement-to-overlap bridge. It includes changes along \(M^1\) and changes along \(M^3\) without requiring both to be nonzero.

### 5.5 Impose the proposed admission condition

For an accepted candidate, \(|A|\le\eta\). The reverse triangle inequality gives
\[
|1-A|\ge1-|A|\ge1-\eta.
\tag{23}
\]
Combining with (22),
\[
1-\eta
\le\frac EQ\left(|\Delta t|+\frac rc\right).
\tag{24}
\]
For \(E>0\),
\[
\boxed{
r+c|\Delta t|\ge(1-\eta)\frac{Qc}{E}.
}
\tag{25}
\]
This is the bound for the particular packet and positive mode energy. If \(E=0\), all modes with nonzero weight have \(\omega_j=0\); A5 also gives \(\mathbf k_j=0\) for those modes. Then \(A=1\) for every displacement and no candidate with \(\eta<1\) is admitted by this comparison.

### 5.6 Observer-scoped uniform theorem

**Theorem.** Suppose every transition in \(\mathcal C(D,I)\) satisfies A1–A7 in the same comparison conventions. Then every accepted candidate has
\[
\boxed{
d_+(a)\ge
\frac{(1-\eta_{\max})\hbar c}{E_D^{\rm cap}}>0.
}
\tag{26}
\]

**Proof.** Equations (23), (22), and (11) give
\[
1-\eta_{\max}
\le1-\eta
\le|1-A(a)|
\le\frac{E}{Qc}d_+(a)
\le\frac{E_D^{\rm cap}}{\hbar c}d_+(a).
\tag{27}
\]
Rearrangement proves (26). \(\square\)

Also,
\[
r+c|\Delta t|
\le\sqrt2\sqrt{r^2+c^2\Delta t^2},
\tag{28}
\]
so
\[
\boxed{
d_2(a)\ge
\frac{(1-\eta_{\max})\hbar c}
{\sqrt2\,E_D^{\rm cap}}>0.
}
\tag{29}
\]
The numerical coefficients are conservative bounds, not claims of optimal sharpness.

For the literal nonoverlap consequence \(\eta_{\max}=0\),
\[
\boxed{
d_+\ge\frac{\hbar c}{E_D^{\rm cap}},
\qquad
d_2\ge\frac{\hbar c}{\sqrt2\,E_D^{\rm cap}}.
}
\tag{30}
\]
In terms of the original Planck constant,
\[
d_+\ge\frac{hc}{2\pi E_D^{\rm cap}}.
\tag{31}
\]

For the same reason as in the geometric proof, this establishes a positive lower bound. It does not establish equal steps, an integer coordinate lattice, a common cosmic clock, or an attained global minimum over all possible profiles.

### 5.7 Pure-axis consequences

For \(r=0\), equation (24) requires no spatial phase assumption:
\[
\boxed{
|\Delta t|\ge\frac{(1-\eta)Q}{E}
\ge\frac{(1-\eta_{\max})\hbar}{E_D^{\rm cap}}.
}
\tag{32}
\]
This is exactly the case where only the \(M^1\) coordinate changes.

For \(\Delta t=0\), under A5,
\[
\boxed{
r\ge\frac{(1-\eta)Qc}{E}
\ge\frac{(1-\eta_{\max})\hbar c}{E_D^{\rm cap}}.
}
\tag{33}
\]
These are pure-axis tests. They are not simultaneous lower bounds on both components of a general mixed step. The correct mixed-step statement is (26) or (29).

If one separately requires a forward causal trajectory, \(r\le c\Delta t\) with \(\Delta t\ge0\), then
\[
d_+\le2c\Delta t
\]
and every accepted such step satisfies
\[
\Delta t\ge
\frac{(1-\eta_{\max})\hbar}{2E_D^{\rm cap}}.
\tag{34}
\]
That path condition is additional to the phase-space inequality A5. The two are not the same premise.

### 5.8 What is required to make the energy cap finite?

Let \(D_s\) be an accessible spatial slice at reference time \(s\in I\). A sufficient resource construction is:

1. A nonnegative density \(\epsilon_+(x,s)\) accounts for the same positive energy that governs the comparison phases.
2. Every tested packet/process satisfies
   \[
   E\le E_+(s):=\int_{D_s}\epsilon_+(x,s)\,dV_s.
   \]
3. The quantity
   \[
   E_D^{\rm cap}:=\sup_{s\in I}E_+(s)
   \]
   is finite.

A more restrictive but explicit sufficient condition is
\[
0\le\epsilon_+(x,s)\le\epsilon_{\max}<\infty,
\qquad
{\rm Vol}(D_s)\le V_{\max}<\infty
\]
uniformly over \(I\). Then
\[
E_D^{\rm cap}\le\epsilon_{\max}V_{\max}<\infty.
\tag{35}
\]
Together with the other theorem premises, this gives
\[
d_+\ge
\frac{(1-\eta_{\max})\hbar c}{\epsilon_{\max}V_{\max}}.
\tag{36}
\]

Equation (35) proves finiteness from those explicit bounded-density and volume assumptions. It does not derive those assumptions merely from the word “observable.”

A finite volume does not prevent arbitrarily large amplitudes or energy density. A spatial horizon does not automatically bound an unlimited time history. Fluxes, changing accessible volume, and external driving must remain inside the resource account when claiming a common cap across \(I\).

The relevant bound is on the **positive phase-governing energy**. A finite net energy after cancellation against negative binding contributions does not by itself bound that positive sum.

### 5.9 Why a boundary and \(h\) alone do not close the proof

Even a fixed bounded wave domain can have unbounded mode numbers. Consider, solely as a mathematical example, an interval of fixed length \(L\) with standing modes
\[
\chi_n(x)=\sqrt{2/L}\sin(n\pi x/L),
\qquad
\omega_n=cn\pi/L.
\tag{37}
\]
Take two modes \(n\) and \(3n\) with equal action weights and total packet action \(Q=\hbar\). Their positive energy is
\[
E_n=\frac{\hbar}{2}(\omega_n+\omega_{3n})
=\frac{2n\pi\hbar c}{L}.
\tag{38}
\]
Their time-overlap amplitude is
\[
A_n(t)=\tfrac12(e^{-i\omega_n t}+e^{-i\omega_{3n}t})
=e^{-2i\omega_n t}\cos(\omega_n t).
\tag{39}
\]
It first reaches zero at
\[
t_n=\frac{\pi}{2\omega_n}=\frac{L}{2nc}\longrightarrow0.
\tag{40}
\]
The domain and Planck anchor remain fixed. The positive energy grows without bound.

This is a counterexample to deriving a uniform phase-separation time from bounded domain size and \(Q=\hbar\) alone. It does not assert that orthogonal modes have disjoint occupied supports, or that these modes are the actual collapse configurations of the project. For literal support exclusion, the earlier compact-packet shrinking example separately shows that a finite domain without an energy/scale restriction can contain arbitrarily small excluded-support steps.

The finite boundary is therefore a scope and possible resource constraint. The missing content is the rule excluding unbounded energy or otherwise constraining the actual allowed profiles.

### 5.10 A finite-energy example of actual phase separation

Choose two equally weighted modes with
\[
Q=\hbar,\qquad \omega_1=\Omega,\quad\omega_2=3\Omega,\quad\Omega>0.
\]
Then
\[
E=2\hbar\Omega,\qquad
A(t)=e^{-2i\Omega t}\cos(\Omega t).
\tag{41}
\]
The first zero is
\[
t_*=\frac{\pi}{2\Omega}.
\tag{42}
\]
The theorem gives the valid lower bound
\[
t_*\ge\frac{\hbar}{E}=\frac1{2\Omega}.
\tag{43}
\]
The exact time is larger by a factor of \(\pi\), consistent with a conservative inequality.

For a spatial example, take two modes with wavevectors \(\pm k\,\hat x\), equal weights, and the same frequency \(\Omega\ge ck\). Then
\[
A(x,t)=e^{-i\Omega t}\cos(kx).
\tag{44}
\]
The first pure-spatial zero is \(x_*=\pi/(2k)\), while the bound is \(x_*\ge c/\Omega\). Pure time translation leaves \(|A|=1\) in this particular example, demonstrating that a bound does not guarantee a successor in every direction.

These examples demonstrate finite phase-orthogonal successors. They do not prove literal occupied nonoverlap of complete past/future histories. That stronger admission and existence question must use the actual wave geometry.

### 5.11 Boundary normalization without a false translation identity

Restricting an integral to a fixed accessible domain generally gives
\[
\int_D|\psi(X-a)|^2\,dX
\ne
\int_D|\psi(X)|^2\,dX.
\tag{45}
\]
Consequently, one cannot simply restrict the earlier all-space overlap formula to \(D\) while retaining its equal-normalization identity.

The present mode-vector proof avoids that substitution: A3 changes phases in a declared orthonormal comparison basis and therefore preserves \(Q\) exactly. Whether an actual translated wave in the observer's domain is represented by A3 must still be established.

A separate fully normalized finite-domain formulation is also available. Let \(F_q\in L^2(D)\) be nonnegative profiles with \(\|F_q\|_2=1\), where \(q\) is a physical placement parameter in a convex set. Suppose
\[
\|D F_q[v]\|_2^2\le\Lambda_D^2\,v^Thv
\]
uniformly. Integrating along the straight parameter segment yields
\[
\|F_q-F_p\|_2\le\Lambda_Dd_h(p,q).
\]
Then an overlap threshold \(\langle F_p,F_q\rangle\le\eta\) implies
\[
d_h(p,q)\ge\frac{\sqrt{2(1-\eta)}}{\Lambda_D}.
\tag{46}
\]
This version respects the finite domain, but the derivative bound and the meaning of placement are still model inputs. It is a separate route, not an assumed consequence of A1–A7.

An observational boundary is not automatically a physical wall that forces the wave to vanish there. Imposing a sharp cutoff or a vanishing boundary condition changes the comparison problem. Smoothing a cutoff introduces a scale that must be accounted for.

## 6. Results and interpretation

### 6.1 What Planck's constant adds

The anchor produces the nonzero numerator \(Q\ge\hbar\). The positive energy formula produces the denominator \(E/Q\), the average angular-frequency rate. Their ratio has the required units:
\[
\frac{\hbar}{E}\ \text{is time},\qquad
\frac{\hbar c}{E}\ \text{is length}.
\]

No numerical observable-universe energy budget has been supplied or inferred here. Therefore no numerical cosmological minimum step is claimed.

For convenient substitution once a valid cap is known,
\[
\hbar c\approx3.16152677350\times10^{-26}\ {\rm J\,m},
\]
\[
\frac{\hbar c}{\sqrt2}
\approx2.23553702044\times10^{-26}\ {\rm J\,m}.
\tag{47}
\]
For \(\eta_{\max}=0\), divide these coefficients by the justified positive cap in joules to obtain the corresponding guaranteed distances in metres.

### 6.2 Finite mean energy without a second-moment bound

The proof only needs a finite first moment \(\sum p_j\omega_j\). It does not assume finite \(\sum p_j\omega_j^2\).

For example, take weights \(p_1=1-1/N\), \(p_2=1/N\) at frequencies \(\omega_*\) and \(N\omega_*\). The mean frequency stays below \(2\omega_*\), while the second moment grows without bound as \(N\to\infty\).

Thus a properly identified finite positive energy cap can establish the new theorem even when a uniform derivative-tensor cap has not been shown. This provides an alternative conditional route; neither theorem's full physical premises are inferred from the other. The energy cap and actual collapse comparison still require their own identification.

### 6.3 What the causal boundary does and does not establish

| Claim | Result |
|---|---|
| The theorem can be scoped to one observer's accessible class of processes. | Yes; the quantifiers are restricted to \(\mathcal C(D,I)\). |
| A causal boundary may help identify a finite available resource account. | Yes, if the energy and flux account supplies A6. |
| Finite region size alone guarantees a finite common phase-energy cap. | No; equations (37)–(40) exhibit the missing restriction. |
| A causal/access boundary forces the physical wave to vanish there. | Not established. |
| The mathematical proof requires a causal boundary in every possible realization. | No; an independently specified finite energy cap would also suffice without one. |
| Failure of an infinite-time normalization proves a physical causal boundary must exist. | No; that is a limitation of that normalization. The normalized mode-vector proof does not require the integral. |
| The same positive minimum applies to every observer and every epoch. | Not derived. The cap and admissible class may depend on observer and comparison interval. |

### 6.4 Exact physical interfaces still requiring derivation

1. **Comparison pairing:** identify the old/new complete wave pairing to which the nonoverlap rule applies. Retain the distinction between canonical action coefficients and raw field amplitudes.
2. **Admitted displacement law:** show that the candidate's complete pattern obeys A3, or derive a replacement bound for its actual changes. An arbitrary instantaneous C1 jump is not automatically a free-phase displacement.
3. **Spatial bridge:** derive the relevant spatial phase relation or a bound on \(\overline k\). Internal action quantization alone supplies neither.
4. **Positive energy cap:** bound the same phase-governing energy for every transition in the declared accessible class, including necessary apparatus and interaction contributions.
5. **Existence:** exhibit a candidate that passes the actual standing-wave/nonoverlap condition and all conservation requirements.

If these interfaces are proved, equations (26) and (29) are the resulting observer-scoped minimum-step theorem. Assuming an interface without deriving it keeps the result conditional.

## 7. Checks

### 7.1 Analytic verification

- \(Q\ge\hbar\) is used for the whole packet. No extra action quantum is assigned to each coherent component.
- Positive frequencies make \(E/Q\) the mean absolute frequency needed for the estimate. Signed frequency cancellation cannot be used as an energy bound.
- The inequality \(|1-e^{i\theta}|\le|\theta|\) is proved directly.
- The chain from admission to step uses the correct inequality direction.
- A finite mean energy is enough; no hidden second-moment assumption is used.
- \(M^1\) contributes \(c|\Delta t|\), including the pure-time case.
- The spatial phase condition is stated separately from causal trajectory speed.
- The energy cap bounds the same positive modal quantity as the phase estimate.
- Phase orthogonality, occupied nonoverlap, and actual collapse occurrence remain distinct.
- A fixed finite domain does not silently preserve translated normalization.
- The numerical constants have units of action, action times speed, time, or length as required.
- The claimed constant is a lower bound, not an exact universal tick or a proven attained infimum across all physical states.

### 7.2 Executed numerical checks

A deterministic Python/NumPy script tested 10,000 mode-sum examples in dimensionless units \(\hbar=c=1\), with positive frequencies, arbitrary normalized weights, wavevectors satisfying A5, several packet-action sectors, and domain caps no smaller than each tested energy.

| Check | Result |
|---|---:|
| Mode-sum samples | 10,000 |
| Maximum positive violation of the inequality chain | 0 |
| Maximum positive violation of the full-step bound | 0 |
| Two-mode time-overlap residual at the exact zero | \(6.123233995736765\times10^{-17}\) |
| Two-mode space-overlap residual at the exact zero | \(6.123233995736766\times10^{-17}\) |
| Overall numerical check | PASS |

These checks support the calculations. The analytic inequalities establish the theorem; finite sampling does not establish physical universality.

### 7.3 Reproducible verification code

```python
import json, math
import numpy as np

rng=np.random.default_rng(20261128)
max_chain_violation=0.0
max_final_violation=0.0
samples=10000
for _ in range(samples):
    n=int(rng.integers(2,35))
    omega=np.exp(rng.normal(0,1.7,size=n))
    p=rng.dirichlet(np.ones(n))
    directions=rng.normal(size=(n,3))
    directions/=np.linalg.norm(directions,axis=1)[:,None]
    k=directions*(omega*rng.uniform(0,1,size=n))[:,None]
    Q=float(rng.integers(1,7))
    E=Q*float(p@omega)
    Ecap=E*(1+rng.uniform(0,3))
    scale=10**rng.uniform(-6,1)
    dx=rng.normal(size=3)*scale
    dt=float(rng.normal()*scale)
    theta=k@dx-omega*dt
    A=complex(p@np.exp(1j*theta))
    gap=max(0.0,1-abs(A))
    radius=float(np.linalg.norm(dx))
    phase_bound=float(p@np.abs(theta))
    path_bound=(E/Q)*(radius+abs(dt))
    max_chain_violation=max(max_chain_violation,
        gap-abs(1-A),abs(1-A)-phase_bound,
        phase_bound-path_bound)
    d2=math.sqrt(radius**2+dt**2)
    floor=gap/(math.sqrt(2)*Ecap)
    max_final_violation=max(max_final_violation,floor-d2)
assert max_chain_violation<1e-10
assert max_final_violation<1e-10
Omega=1.7
tau=math.pi/(2*Omega)
At=0.5*(np.exp(-1j*Omega*tau)+np.exp(-3j*Omega*tau))
kval=2.3
x=math.pi/(2*kval)
Ax=0.5*(np.exp(-1j*kval*x)+np.exp(1j*kval*x))
assert abs(At)<1e-12 and abs(Ax)<1e-12
h=6.62607015e-34
hbar=h/(2*math.pi)
c=299792458.0
result={
"mode_sum_samples":samples,
"maximum_positive_chain_violation":max(0.0,max_chain_violation),
"maximum_positive_full_step_violation":max(0.0,max_final_violation),
"two_mode_temporal_overlap_residual":abs(At),
"two_mode_spatial_overlap_residual":abs(Ax),
"h_SI":h,"hbar_SI":hbar,
"hbar_c_SI":hbar*c,
"hbar_c_over_sqrt2_SI":hbar*c/math.sqrt(2),
"status":"PASS"}
print(json.dumps(result,indent=2))
```

## 8. Completion test

| Required outcome | Status |
|---|---|
| Use Planck's constant as an explicit action anchor. | Complete; numerical anchor and CAL identification are stated separately. |
| Derive a minimum full-geometric displacement using the anchor. | Complete under A1–A7. |
| Include pure displacement along \(M^1\). | Complete; equation (32). |
| Restrict universality to the accessible region. | Complete; the class and cap are observer-scoped. |
| Avoid an unnecessary derivative-variance cap. | Complete; the proof uses finite mean positive energy. |
| Show what a causal boundary contributes. | Complete; domain/resource role and sufficient bounded-energy conditions are explicit. |
| Prove a causal boundary is necessary. | Not established; the mathematics does not imply this from the stated inputs. |
| Prove boundary plus \(h\) alone forces a minimum step. | Not valid in the stated mathematical class; the additional energy/phase restrictions are necessary to this route. |
| Identify the remaining links to the actual G1/C1 collapse construction. | Complete; listed in Section 6.4. |
| Establish an unconditional numerical minimum for our observable universe. | Open; no validated domain energy cap or complete physical comparison law has been supplied. |

**Final proved theorem.** For every accepted transition in a specified accessible class satisfying A1–A7,
\[
\boxed{
r+c|\Delta t|\ge
\frac{(1-\eta_{\max})\hbar c}{E_D^{\rm cap}},
\qquad
\sqrt{r^2+c^2\Delta t^2}\ge
\frac{(1-\eta_{\max})\hbar c}{\sqrt2\,E_D^{\rm cap}}.
}
\]
The numerator is anchored by Planck's constant. The accessible-region energy cap supplies the physical scale. Establishing that cap and its coupling to the actual admissibility law remains the physical completion.

