# **A Pre-Geometric Substrate Model for the Emergence of Finite-Density Spacetime**

> This work proposes a rupture-based geometrogenesis model in which finite-density spacetime emerges from a non-geometric substrate. It belongs to the broader family of emergent spacetime theories but differs from causal set, loop, and holographic approaches by assuming no initial topology, metric, or adjacency. Geometry, time, Lorentzian signature, and finite densities arise through a monotonic separability transition rather than a bounce or quantum foam.

##### **Concept by Jérémie Fréreault.**
##### **Structured and rendered with AI assistance.**
##### **Shared publicly for discussion, critique, and exploration.**
##### **Visual Studio Code is recommended for proper reading.**

---

## **Glossary**

**Pre-Geometric Substrate**
A state with no manifold, metric, separability, causality, or time. Contains mass-energy content but no geometrical or temporal descriptors.

**Unbounded Internal Reducibility**
The property that substrate degrees of freedom can be subdivided endlessly in principle, even though no subdivision is meaningful until geometry exists. Reducibility refers to an abstract subdivision of degrees of freedom and carries no spatial meaning in the 0D phase. It only becomes operational once geometry emerges.

**Collapsed Configuration**
A maximal-symmetry state in which all substrate degrees of freedom coincide because separability is undefined.

**Rupture**
A spontaneous symmetry-breaking transition that introduces geometric degrees of freedom (space, volume, direction, time) and maps the substrate into a manifold.

**Rupture Map** $(\Phi : S \to M)$
A mapping that assigns each pre-geometric degree of freedom a location in an emergent spacetime.

**Separability Layer / Rupture Layer**
One realization of $(\Phi_t)$, representing the state of the universe at emergent time $t$.

**Finite Density Condition**
The requirement that for any bounded region $(R \subset M)$, the mapped mass satisfies $(M(R) < \infty)$. Prevents the Big Bang singularity.

**Momentum Stretching**
A redshift-like effect in which momenta scale as $(p \propto \frac{1}{a(t)})$ as separability increases.

**0D Phase**
The pre-rupture regime with no dimensions, no temporal progression, and no definable density. Unstable when mass content is nonzero.

**Monotonic Separability**
The principle that the rupture layers become increasingly separable over time and cannot revert to the pre-geometric collapsed state.

**Structural Irreversibility**
The fact that geometric structure, once introduced, cannot be removed without collapsing the manifold, providing an intrinsic arrow of time.

# **Mathematical Summary**

This section collects the minimal mathematical structures used throughout the model.

---

## **Substrate**

**Primitive set:**

$$
S \quad\text{(countable set of substrate degrees of freedom)}
$$

**Mass function:**

$$
m : S \to \mathbb{R}_{+}
$$

**Measure:**

$$
\mu(A)=\#\{s\in A\}, \qquad \text{(counting measure)}
$$

**Total mass:**

$$
M_{\text{total}}=\sum_{s\in S} m(s)
$$

No topology, metric, or geometric relations are defined on $S$.

---

## **Internal Phase Structure**

**Internal parameter space:**

$$
\Theta = S^{1}
$$

**Phase field:**

$$
\psi : \Theta \to \mathbb{R}
$$

with properties:

$$
\psi(\theta+2\pi)=\psi(\theta)\qquad
\int_0^{2\pi}\psi(\theta)d\theta=0,\qquad
\psi\not\equiv\text{const}.
$$

**Phase trajectory (monotonic):**

$$
\theta(t)=\theta_0+\int_0^{t}\omega(\tau)\, d\tau, \qquad \omega(t)>0.
$$

**Phase gradient (separability magnitude):**

$$
D(t)=\psi'\bigl(\theta(t)\bigr).
$$

---

## **Rupture Layers**

**Participation operator:**

At rupture layer (t), the participation of (s) is determined by the phase–coupling functional:

$$
\Pi_t(s)=
\begin{cases}
1, & C\bigl(s,\theta(t)\bigr)\, D(t) > \lambda_t, \\[6pt]
0, & \text{otherwise}.
\end{cases}
$$

where
$$
\lambda_t \in \mathbb{R}
$$
is a layer-dependent threshold chosen so that $(S_t=\{\,s\in S \mid \Pi_t(s)=1\,\})$ is finite.
This thresholding rule is the only degree of freedom required to ensure:

* a finite number of elements join each layer,
* participation depends explicitly on the internal phase,
* the layer sequence is fully determined by $(\theta(t))$,
* the coupling is non-geometric and valid in the 0D phase.

---

## **Separability**

Per-element separability:

$$
\sigma_t(s)=D(t)\,\Pi_t(s).
$$

Total separability:

$$
\Sigma(t)=\sum_{s\in S_t}\sigma_t(s).
$$

Layer-dependent smoothing scale:

$$
\epsilon(t)=\frac{1}{\Sigma(t)}.
$$

Monotonicity:

$$
\dot{\Sigma}(t)>0.
$$

General growth law:

$$
\dot{\Sigma}(t)=\alpha\,\Sigma(t)^{\beta},\qquad \alpha>0,\; 0\le\beta\le1.
$$

Emergent scale factor:

$$
a(t)\propto\left(\frac{\Sigma(t)}{M_{\text{total}}}\right)^{1/3}.
$$

---

## **Embedding and Emergent Spacetime**

Emergent manifold:

$$
(M,g) \quad\text{(Lorentzian spacetime)}
$$

**Rupture embedding:**

$$
\Phi_t : S_t \to M.
$$

Worldline of $s$:

$$
\gamma_s(t)=\Phi_t(s).
$$

**Embedding functional:**

$$
\Phi_t(s)
=
\exp_{X_t}\!\bigl(A_t(s)\, D(t)\, v_t(s)\bigr).
$$

where
- $(X_t\in M)$ is a reference point,
- v_t(s)\in T_{X_t}M \text{ is a unit tangent direction assigned to } s,
- $(A_t(s)>0)$ for $(s\in S_t)$.
- \|v_t(s)\|_g = 1.

---

## **Finite Density Condition**

For any bounded region $(R\subset M)$:
$$
M(R)=\sum_{\substack{s\in S_t \\ \Phi_t(s)\in R}} m(s)<\infty.
$$

This eliminates the Big Bang singularity.

---

## **Stress–Energy Tensor**

Four-velocity:
$$
u^\mu(s,t)=\frac{d\gamma_s^\mu(t)}{dt}.
$$

Stress–energy tensor:
$$
T_{\mu\nu}(x,t)
=
\sum_{s\in S_t}
m(s)\,
u_\mu(s,t)\,
u_\nu(s,t)\,
\eta_{\epsilon(t)}\!\bigl(x - \Phi_t(s)\bigr).
$$


Conservation:

$$
\nabla_\mu T^{\mu\nu}(x,t)=0
\quad\text{in the sense of distributions},
$$

Einstein equation (emergent):

$$
G_{\mu\nu}=8\pi G\, T_{\mu\nu}.
$$

---

## **Coarse-Phase Cosmological Quantities**

Effective phase field from coarse sampling:

$$
\psi_{\text{eff}}(\theta)=
\sum_{n=1}^{N_{\text{eff}}}
\bigl(A_n\sin n\theta + B_n\cos n\theta\bigr).
$$

Effective gradient:

$$
D_{\text{eff}}(t)=\psi'_{\text{eff}}(\theta(t)).
$$

Effective expansion:

$$
\frac{\dot{a}}{a}\propto
\langle |D_{\text{eff}}(t)|\rangle.
$$

Effective geometric energy density:

$$
\rho_{\text{sep}}(t)=\frac{3}{8\pi G}H^2(t).
$$

---

## **Observability Threshold**

Define the threshold for gauge-field resolvability:

$$
\epsilon_{\text{obs}}(t).
$$

Dark subset:

$$
S_{\mathrm{DM}}(t)
= \{ s\in S_t \mid \sigma_t(s) < \epsilon_{\mathrm{obs}}(t) \}.
$$

These elements gravitate normally but are non-luminous.

## **1. Introduction**

The classical Big Bang model begins with a manifold already in place and assigns a formally infinite density to an initial pointlike configuration. This divergence is widely understood not as a physical blow-up but as an indication that the geometric description is being applied outside its domain of validity.

This work proposes a more fundamental starting point: a pre-geometric substrate with unbounded internal reducibility. This substrate contains mass-energy but lacks a manifold, a metric, separability, causality, and time. As such, density is undefined because volume is undefined.

The transition from this collapsed, maximally symmetric phase into a geometric phase is called a rupture. The rupture introduces spatial directions, finite volume elements, and an emergent time coordinate through a mapping $(\Phi : S \to M)$. The apparent infinite density of the Big Bang becomes an interpretational category error: density only becomes meaningful after geometry exists.

A key feature of this model is that the rupture necessarily breaks the perfect symmetry of the pre-geometric phase. This symmetry breaking produces a monotonic increase of separability, which yields a natural arrow of time, eliminates the need for low-entropy initial conditions, and connects cosmic expansion directly to geometric emergence.

The goal of this work is to present a clean formal scaffold demonstrating how finite densities, emergent time, irreversible evolution, and standard cosmological behavior arise naturally from this transition.

## **2. The Pre-Geometric Substrate**

## **2.1 Structure**

Let $S$ denote the pre geometric substrate.
We model $S$ as a **countable set of primitive degrees of freedom**. No topology, metric, or spatial relation is defined on it.

To make expressions like $\int_S f(s)\, ds$ mathematically meaningful
, we explicitly equip $S$ with the **counting measure** $\mu$:

$$
\mu(A) = \#\{\, s \in A \,\}.
$$

Thus,

$$
\int_S f(s)\, d\mu = \sum_{s\in S} f(s).
$$

This keeps every integral finite whenever $f(s)$ has finite support on a rupture layer.

Each element carries a mass label:

$$
m: S \to \mathbb{R}_+.
$$

Total substrate mass is the counting measure sum:

$$
M_{\mathrm{total}} = \sum_{s\in S} m(s),
$$

which exists by construction.
Because no geometric or volume structure exists, this is *mass*, not density.

The substrate has:

* no neighborhoods
* no metric
* no ordering
* no time
* no separability

All permutations of $S$ represent the same physical configuration, expressing the maximal symmetry of the 0D phase.

### **2.2 Collapsed Configuration**

In the absence of separability, the substrate is in a collapsed phase: there is no meaningful partition

$$
S = \bigsqcup_i S_i.
$$

Any geometric interpretation of this state yields a formal infinite density, which is an interpretational mistake, not a physical divergence.


## **3. Emergent Spacetime and the Rupture Map**

### **3.1 Spacetime Manifold**

Let $M$ be a differentiable manifold equipped with a Lorentzian metric $g$. For cosmology, $M$ may be an FRW spacetime, though this is not required. The dimensionality of $M$ is treated as an input rather than a derived property. Determining whether dimensionality can emerge from properties of $S$ is a possible extension of the model.

### **3.2 Rupture as a Phase Transition**

The rupture is a transition from the collapsed pre-geometric phase to a geometric phase where:

* separability exists
* volume exists
* density becomes definable
* time emerges as an ordering parameter

We model the transition via a mapping:

$$
\Phi : S \to M.
$$

### **3.3 Finite Local Densities**

For any bounded region $(R)$:

$$
M(R) = \sum_{s : \Phi(s) \in R} m(s).
$$

**Finite density condition**

$$
M(R) < \infty \quad \forall \text{ bounded } R \subset M.
$$

This guarantees:

* no divergences
* no singular initial density
* finite mass-energy by distribution across emergent volume

The Big Bang singularity becomes a mapping constraint, not a physical blow-up.

# **3.4 Internal Phase Field and Angle-Sliced Rupture Geometry**

The internal phase field does **not** assign a phase value to each substrate element.
It is defined on a compact internal parameter space:

$$
\Theta = S^1,
$$

which represents an abstract reducibility coordinate, independent of $S$.

The phase field is:

$$
\psi : \Theta \to \mathbb{R},
$$

with $\theta(t) \in \Theta$ giving the slice sampled by rupture layer $t$.
This avoids confusing $\psi$ with a spatial field or with a label attached to each substrate degree of freedom.

Only the **value** $\psi(\theta(t))$ and the **gradient** $\psi'(\theta(t))$ become operative during rupture.

The rupture process requires a mechanism by which distinct geometric degrees of freedom can emerge from a pre-geometric substrate that possesses no spatial structure. The substrate elements never carry phase labels. The phase is a global slicing parameter only. This section introduces such a mechanism by defining an **internal cyclic phase field** intrinsic to the substrate. This phase is not geometric, spatial, or temporal; it is an abstract reducibility parameter that becomes operational only when a rupture layer forms.

## **Phase–Coupling Functional**

To make rupture-layer selection and participation well defined, introduce a coupling
$$
C : S \times \Theta \to \mathbb{R}
$$
that assigns each substrate element a phase–response value.
The minimal structure needed is:

1. **Dependence on the internal phase:**
   $$
   C(s,\theta_1)\neq C(s,\theta_2)\quad\text{for generic } \theta_1\neq\theta_2.
   $$

2. **No spatial meaning before rupture.**

3. **Statistical neutrality:**
   $$
   \sum_{s\in S} C(s,\theta)=0 \quad\forall\theta.
   $$

A minimal choice that adds no geometry is:
$$
C(s,\theta)=m(s)\,\chi(s)\,\psi(\theta),
$$
where
$$
\chi : S \to \{-1,+1\}.
$$
is any fixed, arbitrary, non-geometric label (permitted by unbounded internal reducibility).

This gives a mass-weighted, sign-symmetric internal response.

## **Internal Phase Space**

Let
$$
\Theta = S^{1}
$$
be a compact cyclic parameter space (a circle) representing an internal ordering variable of the substrate. This is **not** a spatial dimension and has no geometric interpretation; it is a purely pre-geometric internal label permitted by unbounded internal reducibility.

Define an internal phase field
$$
\psi : \Theta \to \mathbb{R},
$$
satisfying:

1. **continuity**
2. **periodicity**
3. **zero mean**
   $$
   \int_{0}^{2\pi} \psi(\theta)\, d\theta = 0,
   $$
4. **non-constancy** (to provide structure)

The specific waveform of $\psi$ is irrelevant; only its oscillatory nature matters. Any member of this functional class suffices.

The only operational quantities at a rupture layer are:

* the **phase value** $(\theta(t))$, and
* the **local gradient** $(\psi'(\theta(t)))$.

These were dormant in the 0D substrate and become meaningful only when geometry emerges.

---

## **Rupture Layers as Phase Slices**

Each rupture layer $(\Phi_t : S \to M)$ corresponds to sampling the substrate at a particular internal phase angle
$$
\theta(t) \in \Theta,
$$
with the sampling operator
$$
\mathcal{L}(t) = \psi\bigl(\theta(t)\bigr).
$$

The function $(t \mapsto \theta(t))$ is required to be **monotonic**:
$$
\frac{d\theta}{dt} > 0,
$$
ensuring that rupture layers cannot repeat or reverse, capturing structural irreversibility.

Although the internal phase drives the layering, observers experience it as the **flow of time**.

---

## **Emergent Degrees of Freedom from Phase Gradient**

The local directionality and magnitude of geometric separability introduced at layer $t$ are determined by the gradient of the phase field at the slicing angle:
$$
D(t) = \psi'(\theta(t)).
$$

Interpretation:

* large $(D(t))$: strong separability growth
* small $(D(t))$: weak separability growth
* sign of $(D(t))$: orientation in the abstract separability direction (not spatial direction)

Because only the oscillatory structure of $\psi$ matters, the model does **not** depend on any particular functional form such as a sine wave.

---

## **Substrate Instability as Phase Progression**

The substrate is assumed unstable in its collapsed configuration. This instability manifests as a continuous drift through internal phase:
$$
\theta(t) = \theta_0 + \int_{0}^{t} \omega(\tau)\, d\tau,
$$
where $(\omega(t) > 0)$ encodes instability strength.
This is not a frequency in any geometric sense but a structural instability parameter.

A rupture layer forms whenever this drift intersects the next symmetry-breaking phase slice. The sequence of slices generates the emergent temporal ordering.

---

## **Projection of Mass into Geometry**

At layer $t$ \, a projection operator
$$
\Pi_t(s) =
\begin{cases}
1, & s \text{ participates in rupture at phase } \theta(t) \\[6pt]
0, & \text{otherwise}
\end{cases}
$$
selects elements from the substrate to be embedded via:
$$
\Phi_t(s) = F_t\bigl(s, \psi(\theta(t)) \, \psi'(\theta(t))\bigr).
$$

Substrate elements not selected remain unresolved and participate in later layers.

This formalizes:

* the infinite substrate,
* the extraction of finite geometric content layer by layer,
* the increasing resolution with time.

---

## **Angle-Sliced Rupture as Generator of Geometric Structure**

The emergent manifold structure is governed by:

* **orientation** from $(\psi'(\theta(t)))$,
* **separability gain** from $(\psi'(\theta(t)) \,)$,
* **layer ordering** from monotonic $(\theta(t))$,
* **non-reversibility** from non-invertible slicing,
* **anisotropies** from variations in $(\psi'(\theta))$.

Because the rupture mechanism depends only on the **coarse-increment sampling** of the internal phase, no observer in the emergent manifold can reconstruct:

* the true waveform of $\psi$,
* its intrinsic periodic structure,
* or any “wavelength” in a geometric sense.

Thus:

> **The periodicity of $\psi$ is a structural property of the substrate, not an observable geometric quantity.**

# **3.5 Phase-Driven Separability Operator and Emergent Dimensionality**

The internal phase field introduces a structured but non-geometric source of differentiability during rupture. Since the only meaningful features of the phase field are its **periodicity** and **oscillatory behavior**, the separability introduced at each rupture layer depends solely on the value of the phase slice $(\theta(t))$ and the **local gradient** of the phase field:

$$
D(t) = \psi'(\theta(t)).
$$

Here, $(D(t))$ determines both the *orientation* and *magnitude* of the separability that emerges at layer $t$. Because the underlying function $\psi$ is merely required to be continuous, periodic, and zero-mean, the specific waveform is irrelevant. Only the alternating structure of ($\psi$') matters; this guarantees that separability grows monotonically in magnitude while its orientation alternates, producing geometric richness without violating the monotonicity of total separability:

$$
\Sigma(t + \delta t) > \Sigma(t).
$$

We now define the **separability operator** at layer $t$:

$$
\mathcal{S}_{t} = D(t) \, \mathcal{R}_{t}.
$$

where $(\mathcal{R}_{t})$ is the rupture-resolution operator selecting the subset of substrate elements that become geometrically distinguishable at layer $t$. The contribution of substrate element $s$ to separability at that layer is:

$$
\sigma_{t}(s) = D(t) \, \Pi_{t}(s).
$$

Integrating over all participating elements yields the global separability:

$$
\Sigma(t) = \int_{S} D(t) \, \Pi_{t}(s)\, ds.
$$

This formalism connects the structure of the internal phase directly to the expansion and geometric differentiation of the emergent manifold.

## **3.5.1 Phase-Induced Separability Direction**

At rupture layer $(t)$, the separability introduced into the manifold comes from the internal gradient of the phase field:

$$
D(t) = \psi'(\theta(t)).
$$

The magnitude of separability gain at layer $(t)$ is:

$$
\Delta \Sigma(t) \propto |D(t)|.
$$

The sign of $(D(t))$ encodes **orientation** (not spatial direction) of the emergent degree of freedom. Since any zero-mean periodic $\psi$ has an oscillatory derivative, $(D(t)$ alternates in sign but grows in magnitude, producing directional richness while preserving monotonic separability.


$$
\Sigma(t + \delta t) > \Sigma(t).
$$

Only the *direction* oscillates; the *amount* always increases.

## **3.5.2 The Fundamental Separability Differential Equation**

The change in total separability between two rupture layers is:

$$
\Delta \Sigma
= \Sigma(t + \delta t) - \Sigma(t)
= \int_{S} \psi'(\theta(t + \delta t)) \, \Pi_{t+\delta t}(s) \, d\mu(s).
$$

This forms the core dynamical law governing expansion:

* if $\psi$ is small, separability expands slowly,
* if $\psi$ is large, separability expands rapidly.

Because the internal phase field is **not reconstructible** from within spacetime (Section 3.4) \, this differential equation contains the only accessible information about the substrate’s internal oscillation.

This structure is sufficient to define the emergent cosmological dynamics.

### **3.5.3 Dimensionality from Coarse-Phase Resonant Modes**

Any continuous zero-mean periodic phase field admits a Fourier expansion:

$$
\psi(\theta) =
\sum_{n=1}^{\infty}
\bigl(
A_n \sin(n\theta) + B_n \cos(n\theta)
\bigr).
$$

Rupture layers sample the phase only through the **coarse** sequence $\theta(t)$, and never resolve rapid oscillations of $\psi$.
Thus, only Fourier modes with frequencies below a coarse-graining threshold survive:

$$
\psi_{\mathrm{eff}}(\theta)
=
\sum_{n=1}^{N_{\mathrm{eff}}}
\bigl(
A_n \sin(n\theta) + B_n \cos(n\theta)
\bigr).
$$


The effective gradient is:

$$
D_{\mathrm{eff}}(t) = \psi'_{\mathrm{eff}}\bigl(\theta(t)\bigr).
$$

The key observation:

*The number of **linearly independent directions** that survive coarse sampling equals the number of **independent phase-gradient modes** with coherent sign structure after coarse graining.*

For a generic smooth function on $S^1$:

* the $n=1$ mode produces one monotonic component → **time-like direction**
* the next three lowest-frequency linearly independent oscillatory components produce three mutually independent, sign-alternating directions → **three spatial axes**

Higher modes average out under coarse sampling because their contribution changes sign within a single rupture increment.

Thus:

$$
\dim(\text{spatial}) = 3,
\qquad
\dim(\text{time}) = 1.
$$

This dimensionality emerges from the **stability of low-frequency phase-gradient resonances**, not from geometric assumptions.

## **3.5.4 Time as the Resonant Zero Mode**

In this context, the time dimension arises from the monotonic sampling of the internal phase:

$$
\theta(t) = \theta_0 + \int_0^t \omega(\tau) d\tau.
$$

The monotonic evolution of $(\theta(t))$ produces a stable mode that:

* increases separability
* has no oscillatory sign variation
* produces no geometric direction
* but orders all rupture slices

This is exactly the property required for a “time-like” dimension.

Therefore:

### **Time emerges as the non oscillatory component of phase progression.**

---

## **3.6 The Rupture Embedding Functional**

Each rupture layer defines a map:

$$
\Phi_t : S \to M.
$$

To produce a well-typed embedding into the manifold $M$, we introduce:

* a reference point $X_t \in M$ for layer $t$
* a unit tangent vector $v_t \in T_{X_t}M$ encoding phase-gradient orientation
* a mass-weighted embedding amplitude $A_t(s)$

The separability direction arises from the internal phase gradient:

$$
D(t) = \psi'(\theta(t)).
$$

### **3.6.1 Embedding Definition**

The embedding is defined using the exponential map on $M$:

$$
\Phi_t(s)
=
\exp_{X_t}
\Bigl(
A_t(s)\, D(t)\, v_t(s)
\Bigr),
$$

where:

* $A_t(s)$ is defined only when $\Pi_t(s) = 1$
* a direction assignment
  \[
    v_t : S_t \to T_{X_t}M,
  \]
  such that
  \[
    \|v_t(s)\|_g = 1 \quad \text{for all } s\in S_t,
  \]
* a mass-weighted embedding amplitude $A_t(s)$
* $v_t$ determines orientation within the tangent space

This ensures that $\Phi_t(s)$ lies in $M$ and the construction is coordinate independent.

### **3.6.2 Required Properties**

1. **Local Participation**
   $A_t(s)$ is defined iff $\Pi_t(s)=1$.

2. **Mass Coupling**
   $$\frac{\partial A_t(s)}{\partial m(s)} > 0.$$

3. **Phase Coupling**
   $$\frac{\partial \Phi_t}{\partial \theta(t)} \propto D(t).$$

4. **Separability Consistency**
   The separability scale is:
   $$\sigma_t(s) = \bigl\lVert A_t(s)\, D(t)\, v_t(s) \bigr\rVert_g.$$

For generic rupture layers we require that the set
$$
\bigl\{\, v_t(s) \mid s\in S_t \,\bigr\}
$$
spans a multi-dimensional subspace of $T_{X_t}M$, so that the image $\Phi_t(S_t)$ is not confined to a single geodesic.


This representation is the minimal structure that makes the embedding fully well-defined.

# **3.7 Resulting Spacetime Structure**

The full picture now becomes:

1. **A timeless, dimensionless, collapsed substrate**
   holds mass and an internal phase field.

2. **Instability drives phase progression**
   through $(\theta(t))$.

3. **Rupture layers form when phase slices intersect mass structure.**

4. **Each layer introduces a degree of separability**
   with orientation determined by $(\psi'(\theta(t)))$.

5. **Three independent resonance modes stabilize**
   producing the three macroscopic spatial dimensions. Because rupture increments act as a natural low-pass filter, only the first three oscillatory gradient components maintain a coherent orientation between layers; higher modes oscillate away.

6. **The zero mode forms a temporal ordering**
   yielding one time dimension.

7. **The manifold’s expansion rate**
   follows directly from $(\dot{\Sigma}(t))$.

8. **Curvature arises from mass distribution**
   via the embedding functional and GR.

All emergent physics is thus encoded in:

* the internal phase field $$\psi$$
* the instability-driven phase drift $θ(t)$
* the selection operator $Π_t$
* the embedding functional $F_t$
* the separability functional $Σ(t)$

Nothing else is required.

## **4. Time as a Sequence of Rupture Realizations**

Time emerges from an ordered family of maps:

$$
\Phi_t : S \to M,\qquad t\in \mathbb{R}.
$$

Here:

* $S$ persists
* mass is conserved
* geometric relationships change over $(t)$

Worldline of a substrate element $(s)$:

$$
\gamma_s(t) = \Phi_t(s).
$$

This yields:

* well-defined worldlines
* dynamical evolution
* emergent causal structure
* standard Lorentzian geometry

### **4.1 Mass Conservation**

$$
M_{\mathrm{total}}(t)
= \sum_{s\in S} m(s)
= M_{\mathrm{total}}.
$$

### **4.2 Momentum Stretching and Expansion**

With scale factor $a(t)$:

$$
p_s(t) \propto \frac{1}{a(t)}.
$$

As separability increases, the effective geometric distances between mapped elements grow, which enforces the usual $(p \propto \frac{1}{a(t)})$ scaling when momenta are re-expressed in the emergent metric.

Increasing separability encoded in $(\Phi_t)$ produces:

* redshift
* radiation cooling
* momentum stretching

This reproduces standard cosmological effects from first principles.

## **5.1 The 0D Phase as an Instability**

A central principle:

> A nonzero mass content cannot remain in a state with no separability, no volume, and no time once a geometric phase becomes possible.

Mathematically, if $(M_{\mathrm{total}} > 0)$, the collapsed, permutation-symmetric configuration is unstable. The rupture map $(\Phi)$ is the only resolution that yields finite density.

Any nonzero mass content introduces internal distinctions that cannot remain compatible with perfect permutation symmetry once geometric degrees of freedom become dynamically available.

This suggests a cosmological law:

**Mass content forces the emergence of geometry.**

## **5.2 Emergence of the Stress–Energy Tensor**

$$
\textbf{Regularization Kernel.}\quad
\eta_\epsilon : M \to \mathbb{R}_+, \qquad \epsilon>0,
$$

with properties

$$
\eta_\epsilon(x) \ge 0,
\qquad
\int_M \eta_\epsilon(x)\, dV_g = 1,
\qquad
\lim_{\epsilon\to 0} \eta_\epsilon(x) = \delta^{(4)}(x).
$$

Interpretation: a covariant mollifier with characteristic width $\epsilon$ depending on the rupture layer.

General relativity governs the geometry of the emergent manifold $M$, but it requires a stress–energy tensor $(T_{\mu\nu})$ as its source. This tensor must be constructed from the mapped substrate elements. Since each element has mass $(m(s))$ and acquires a four-velocity $(u^\mu(s,t))$ through the evolution of the rupture map, the natural definition is:

$$
T_{\mu\nu}(x,t)
=
\int_S
m(s)\,
u_\mu(s,t)\,
u_\nu(s,t)\,
\eta_{\epsilon(t)}\!\bigl(x - \Phi_t(s)\bigr)
\, d\mu(s).
$$

This expression satisfies the following:

1. **Locality**
   Energy and momentum exist only at geometric points where substrate elements are mapped.

2. **Conservation**
   Since $m(s)$ is constant and worldlines are generated by a smooth one-parameter family of maps, the continuity equation follows:

$$
\nabla_\mu T^{\mu\nu} = 0.
$$

3. **Compatibility with GR**
   Einstein’s equations,

$$
G_{\mu\nu} = 8\pi G\, T_{\mu\nu}.
$$

hold on the emergent manifold, with curvature determined by the distribution of mapped substrate elements. No additional fields or potentials are required, and dark matter contributions follow automatically from low-separability degrees of freedom.

This construction closes the dynamical loop between the rupture process and the geometric evolution of spacetime.

## **5.3 Rupture Dynamics**

Let $S_t = \{\, s\in S \mid \Pi_t(s)=1 \,\}$ be the finite subset participating in layer $t$.

Define the total separability:

$$
\Sigma(t) = \sum_{s\in S_t} \sigma_t(s).
$$

Because $S_t$ is finite for every $t$, $\Sigma(t)$ is always finite.

### **5.3.1 Monotonicity**

$$
\dot{\Sigma}(t) > 0,
$$

expressing that separability cannot decrease once the manifold exists.

### **5.3.2 Finite Rate**

$$
0 < \dot{\Sigma}(t) < \infty.
$$

### **5.3.3 Scale Factor Relation**

The emergent scale factor is defined by:

$$
a(t) \propto
\left(
\frac{\Sigma(t)}{M_{\mathrm{total}}}
\right)^{1/3}.
$$

This matches the intuition that tripling separability increases accessible volume.

### **5.3.4 Minimal Evolution Law**

A general separability growth law is:

$$
\dot{\Sigma}(t) = \alpha\, \Sigma(t)^\beta,
\qquad
\alpha>0, \quad 0\le \beta\le 1.
$$

This provides:

* $\beta=1$: exponential inflation-like growth
* $\beta=0$: linear growth
* intermediate $\beta$: power-law FRW-like behavior

# **5.4 Coarse-Phase Sampling and Observable Cosmological Dynamics**

Although the internal phase field $(\psi : S^{1} \to \mathbb{R})$ has unbounded internal reducibility and may contain arbitrarily fine oscillatory structure, only its **coarse-grained gradient**

$$
D(t) = \psi'\bigl(\theta(t)\bigr)
$$

is accessible to the emergent universe. The mapping $\Phi_t$ samples the substrate at discrete rupture layers, each corresponding to a monotonic phase slice $(\theta(t))$. Because these slices are separated by finite increments of separability, the emergent universe can detect only **low-frequency components** of the internal phase field.

Let the Fourier decomposition of $\psi$ be:

$$
\psi(\theta) = \sum_{n=1}^\infty \left(A_n \sin(n\theta) + B_n \cos(n\theta) \right).
$$

While the full series may contain infinitely many nonzero coefficients, rupture layers detect only the subset of modes that survive coarse sampling:

* high-frequency modes oscillate too rapidly in $\theta$ to influence consecutive rupture layers,
* low-frequency modes contribute coherently to separability increments,
* mid-frequency modes create small-scale variations that average out.

Thus observable cosmological quantities depend only on:

$$
D_{\text{eff}}(t)
= \psi'_{\text{eff}}\bigl(\theta(t)\bigr)
$$

where $(\psi_{\text{eff}})$ is the effective phase field formed from the lowest surviving harmonics after coarse sampling.

This yields a coarse-grained expansion rate:

$$
\Delta \Sigma(t)
= \int_{S} \bigl|D_{\text{eff}}(t)\bigr| \, \Pi_t(s) \, d\mu(s).
$$

The emergent universe therefore evolves according to a **filtered** version of the phase field, not the underlying high-resolution structure of $\psi$. The true harmonic content of the substrate remains inaccessible.

---

# **Physical Interpretation**

* The internal oscillation is **not** a field in spacetime.
* It does not correspond to any physical wavelength.
* Cosmological expansion reflects only the **coarse trend** of $(|D(t)|)$.
* Observers see a smoothed evolution of geometry, not the fine oscillations of $\psi$ itself.

This resolves potential conflicts between the enormous structural complexity of the substrate and the smooth large-scale behavior of spacetime.

# **5.5 Effective Friedmann-Like Behavior from Phase-Gradient Dynamics**

Because the emergent manifold cannot resolve the full structure of the internal phase field, cosmological evolution must be expressed in terms of **effective quantities** constructed from the coarse-sampled gradient (D_{\text{eff}}(t)). This leads naturally to Friedmann-like equations without assuming metric compatibility with any specific harmonic function.

Define an effective expansion factor $(a(t))$ through the relation:

$$
\frac{\dot{a}(t)}{a(t)}
\propto
\left\langle\,\bigl|D_{\text{eff}}(t)\bigr|\,\right\rangle
$$
where the angled brackets denote coarse temporal averaging across many rupture layers.

This equation links:

* the **expansion rate** to
* the **phase-gradient amplitude of the effective phase field**.

No assumption about sinusoidal behavior is required; only oscillatory structure is needed.

## **5.5.1 Energy Density as a Measure of Unresolved Substrate Content**

The canonical cosmological energy density $(\rho(t))$ arises from the proportion of substrate mass not yet surfaced by rupture layers. Let $(M_{\text{surf}}(t))$ be the total mass surfaced by time $t$. Then:

$$
\rho(t) \propto M - M_{\text{surf}}(t)
$$
where $M$ is the (possibly infinite but irreducibly structured) total mass of the substrate.

Since:

$$
\frac{dM_{\text{surf}}}{dt}
\propto
\left| D_{\text{eff}}(t) \right|,
$$
we obtain:

$$
\dot{\rho}(t) \propto -\,\bigl|D_{\text{eff}}(t)\bigr|.
$$

Thus regions with larger effective phase-gradient magnitude generate more geometry per rupture layer, reduce unresolved mass more quickly, and accelerate local expansion.

## **5.5.2 Effective Friedmann Relation**

Combining the effective expansion rate and mass-resolution dynamics yields:

$$
\left(\frac{\dot{a}}{a}\right)^{2}
\propto
\left\langle\,\bigl|D_{\text{eff}}(t)\bigr|\,\right\rangle^{2}
+ \rho(t).
  $$

This is structurally analogous to the Friedmann equation:

$$
\left(\frac{\dot{a}}{a} \right)^2
\sim \rho_{\text{eff}} + \text{(curvature-like terms)},
$$

but arises **without** curvature, fields, or metric assumptions. Instead, it emerges from the phase-driven differential unfolding of the substrate.

# **5.5.3 Key Consequences**

* Cosmic expansion is the macroscopic manifestation of surfacing pre-geometric content.
* Accelerated expansion corresponds to intervals where
  $$
  \bigl|\psi'(\theta(t))\bigr|
  \text{ is large on average.}
  $$
* The universe’s large-scale smoothness comes from the suppression of high-frequency phase harmonics.
* Dark-energy-like behavior emerges from diminishing unresolved mass at late rupture layers.
* No explicit choice of ψ is ever observable or required.


## **5.6 Effective Dark Energy Behavior**

We can recast the phase-driven expansion law into an effective fluid description. In standard cosmology, the Friedmann equation takes the form

$$
H^2 = \frac{8\pi G}{3} (\rho_m + \rho_{\text{DE}})\, 
$$

where $(\rho_m)$ is matter (and radiation) density and $(\rho_{\text{DE}})$ is an effective dark energy density.

From the phase-sliced dynamics we have

$$
H(t) = \frac{1}{3} \alpha\, \Sigma^{\beta-1} f\bigl(\theta(t)\bigr)
$$

so

$$
H^2 = \frac{1}{9} \alpha^2\, \Sigma^{2\beta-2} f(\theta)^2.
$$

We can identify an **effective geometric energy density**:

$$
\rho_{\text{sep}}(t) \equiv \frac{3}{8\pi G} H^2
= \frac{1}{24\pi G}\, \alpha^2\, \Sigma^{2\beta-2}(t)\, f\bigl(\theta(t)\bigr)^2.
$$

This behaves as a dark-energy-like component driven entirely by the internal phase and separability dynamics. Its equation-of-state parameter $(w_{\text{sep}})$ can be inferred from

$$
\frac{\ddot a}{a} = -\frac{4\pi G}{3}\bigl(\rho_{\text{tot}} + 3 p_{\text{tot}}\bigr) \, 
$$

with $(\rho_{\text{tot}} = \rho_m + \rho_{\text{sep}}) \, (p_{\text{tot}} = p_m + p_{\text{sep}})$. In the late-time, matter-diluted regime where $(\rho_m \ll \rho_{\text{sep}})$, we find that:

* For $(\beta = 1)$, $(\rho_{\text{sep}})$ is approximately constant in time (up to small oscillations from $(f(\theta)))$, yielding an effective $(w_{\text{sep}} \approx -1)$.
* For $(\beta)$ slightly below or above 1, $(\rho_{\text{sep}})$ evolves slowly, leading to $(w_{\text{sep}})$ slightly different from $(-1)$ and potentially time-dependent.

Thus the model predicts:

1. A **dominant late-time acceleration component** that behaves like a cosmological constant when $(\beta \approx 1)$.
2. **Small deviations from $(w = -1)$** controlled by both $(\beta)$ and residual phase structure, providing a natural source of evolving dark energy without introducing new fields.

---

## **5.7 Emergent Lorentzian Signature**

We now argue that the emergent metric on $M$ must have Lorentzian signature $((-, +, +, +))$, given:

* one monotonic ordering parameter (time) \, 
* and a finite number of oscillatory separability directions (space).

From the phase-driven picture:

1. The internal phase trajectory $(\theta(t))$ is **monotonic** and never reverses.

   * This defines a unique direction in the space of rupture layers.
   * Distinct layers cannot be mapped back onto each other without violating monotonic separability.
   * This direction is intrinsically asymmetric and cannot be treated like a spatial coordinate.

2. The separability directions derived from $(D(t) = \psi'(\theta(t)))$ are **oscillatory** and symmetric.

   * They appear as reversible degrees of freedom.
   * At fixed layer $t$, small displacements along these directions carry no preferred orientation.

To encode these features in a metric, we require:

* exactly **one** direction where intervals distinguish causal order and are intrinsically oriented,
* and **three** directions where intervals are symmetric and purely geometric.

This is precisely what a Lorentzian metric provides. Denote local coordinates by $((x^0,x^1,x^2,x^3))$, with $(x^0)$ aligned with the rupture-ordering direction and (x^i) aligned with spatial separability modes. The metric signature

$$
\mathrm{sig}(g) = (-,+,+,+)
$$

captures:

* the non-reversibility and ordering of $(x^0)$
* the reversibility and isotropy (after coarse graining) in $((x^1,x^2,x^3))$

If all four directions had the same sign (Euclidean signature) \, no intrinsic causal asymmetry could be represented. Time and space would be interchangeable in a way incompatible with monotonic separability and structural irreversibility.

Conversely, more than one negative direction would create multiple inequivalent “time-like” directions, contradicting the single-parameter ordering imposed by the rupture sequence $({\Phi_t})$.

Therefore:

> The combination of a single monotonic rupture-ordering parameter and a finite set of oscillatory separability modes uniquely selects a metric of Lorentzian signature with one time-like and three space-like dimensions.

# **6. Emergent Arrow of Time**

A central feature of this framework is that **time does not preexist the rupture**. Instead, time arises as an ordering of rupture layers that progressively increase geometric separability. The arrow of time is not imposed as an axiom but emerges naturally from the structure of the transition from pre-geometry to geometry.

## **6.1 Symmetry in the Pre-Geometric Phase**

In the substrate $(S)$, all degrees of freedom are indistinguishable. There are no spatial directions, no metric, no notion of volume, and no temporal ordering. This state possesses **maximal symmetry**, formally represented by invariance under all permutations of $S$. A system in such a state has no parameters by which evolution could be defined.

## **6.2 Symmetry Breaking Through the Rupture**

The rupture that introduces the map $(\Phi : S \to M)$ necessarily breaks this perfect symmetry. The moment geometry appears, the manifold $M$ acquires:

* distinct directions,
* finite volumes,
* local neighborhoods,
* and metric structure.

The introduction of geometric structure is incompatible with maximal symmetry. The rupture therefore induces **spontaneous symmetry breaking**. Any nonzero mass content in $S$ forces this break; a perfectly symmetric rupture is dynamically unstable and immediately amplifies any perturbation.

## **6.3 Monotonic Increase of Separability**

Monotonicity can be expressed by requiring a strictly non-decreasing separability functional

$$
S_{\text{sep}}[\Phi_t]
$$

such that

$$
S_{\text{sep}}[\Phi_{t+1}] > S_{\text{sep}}[\Phi_t]
$$

with equality possible only in the asymptotic limit where separability saturates.

Each rupture layer $(\Phi_t)$ increases separability in the emergent manifold:

$$
\Phi_{t+1}(S) \quad \text{is strictly more separable than} \quad \Phi_t(S).
$$

Once degrees of freedom become geometrically distinguished, re-collapsing them into a pre-geometric configuration would require destroying the manifold structure itself. For any two layers $t_1 < t_2$, there exists no permutation $\pi$ of $S$ for which $(\Phi_{t_1} = \Phi_{t_2} \circ \pi)$. This states that no later layer can be collapsed back into an earlier one without destroying geometric structure. This provides a **structural irreversibility** more fundamental than ordinary thermodynamic irreversibility.

In this sense:

> **Time flows forward because separability only increases; the rupture map is injective but not invertible.**

## **6.4 Entropy as a Consequence, Not a Cause**

In standard cosmology, the arrow of time is attributed to entropy increase, yet the low-entropy boundary condition at the Big Bang remains unexplained. In this model:

* the arrow of time is primary,
* entropy growth is secondary,
* and both arise from the same geometric principle:
  **the monotonic increase of separability after symmetry breaking.**

Entropy production is simply the statistical reflection of the structural fact that the rupture cannot reverse.

## **6.5 Perception of Temporal Flow**

From the perspective of embedded observers, the monotonic sequence of rupture layers

$$
\Phi_0, \Phi_1, \Phi_2, \ldots
$$

produces:

* a well-defined ordering,
* a causal structure inherited from the geometry of $M$,
* momentum redshift due to increasing separability,
* and a psychological perception of forward flow.

Only forward-propagating layers are physically realizable; reverse layers would require geometric collapse, violating the finite-density and monotonic-separability conditions.

## **6.6 Summary**

In this framework, the arrow of time emerges from a single principle:

> **Time is directional because geometric separability increases monotonically after the rupture, and this increase is structurally irreversible. The mapping family $(\Phi_t)$ is injective in $(t)$: distinct layers cannot map substrate elements to identical geometric configurations.**

This resolves the classical problems of:

* the origin of time,
* the low-entropy initial state,
* the irreversibility of macroscopic phenomena,
* and the unidirectional flow of temporal experience,

without introducing new forces, exotic matter, or ad hoc initial conditions.

## **7. Consequences for Thermodynamics**

The rupture model has direct implications for the origin and behavior of thermodynamic phenomena.

### **7.1 Entropy Is Not Fundamental**

In this framework:

* entropy is not the cause of temporal asymmetry
* entropy increase follows from the geometric structure of rupture layers
* time’s arrow exists even in the absence of statistical ensembles

This reverses the usual interpretation in cosmology, where entropy is treated as the source of irreversibility.

### **7.2 Low-Entropy Initial State Becomes Natural**

The Big Bang’s low-entropy starting point, which is unexplained in standard cosmology, is reframed. The pre-rupture configuration is maximally symmetric — *not low entropy, but entropy-undefined*. Once geometry emerges, separability increases monotonically and entropy becomes definable only *after* symmetry breaking.

The universe appears low-entropy at early times because:

* entropy did not exist before the rupture
* the first rupture layers contain minimal separability
* entropy grows as separability grows

Once geometry appears, entropy becomes definable only to the extent that separability exists. Early layers appear low-entropy because the phase space available to distinguish microstates is initially extremely small.

### **7.3 Irreversibility Is Structural, Not Statistical**

Traditional thermodynamics attributes irreversibility to coarse-graining. Here, irreversibility arises from:

* injectivity of $(\Phi_t)$
* non-invertibility of geometric emergence
* impossibility of collapsing a manifold back into a 0D substrate

This makes the arrow of time **structurally guaranteed**, not probabilistic.

### **7.4 Expansion and Cooling as Separability Effects**

Cosmic expansion and cooling of radiation follow automatically:

* increased separability → increased scale factor
* increased scale factor → momentum stretching
* momentum stretching → reduced temperature

Thus thermodynamic cooling becomes a geometric effect rather than a requirement for explaining structure formation.

### **7.5 Entropy Production Tracks Separability**

Let $(S_{\text{entropy}})$ denote thermodynamic entropy.

One may define a monotonic functional:

$$
\mathcal{S}(t) \propto \text{Separability}(\Phi_t)
$$

This links entropy production to the underlying geometric order, suggesting:

> The second law of thermodynamics is a corollary of the monotonic growth of separability.

This perspective has potential implications for black hole thermodynamics, inflation theory, and quantum gravity formulations based on information-theoretic principles.

# **8. Dark Matter as Low-Separability Substrate Elements**

Let $\sigma_t(s)$ be the separability scale of substrate element $s$ at rupture layer $t$, and let

$$
\epsilon_{\mathrm{obs}}(t)
$$

be the minimum separability needed to support observable gauge-field excitations.

Elements with:

$$
\sigma_t(s) < \epsilon_{\mathrm{obs}}(t)
$$

are present geometrically but **cannot couple to gauge fields**, and therefore cannot be detected electromagnetically. Gauge interactions require $(\theta(t)=\theta_0+\int_0^{t}\omega(\tau)\, d\tau)$ so that the mapped support overlaps with gauge field excitation zones.

Define the dark subset:

$$
S_{\mathrm{DM}}(t)
=
\bigl\{\, s\in S \mid \sigma_t(s) < \epsilon_{\mathrm{obs}}(t) \,\bigr\}.
$$


### **8.1 Gravitational Contribution**

Because curvature depends only on mass, not resolvability:

$$
T_{\mu\nu}^{\mathrm{DM}}(x,t)
=
\sum_{s\in S_{\mathrm{DM}}(t)}
m(s)\,
u_\mu(s,t)\,
u_\nu(s,t)\,
\delta^{(4)}\!\bigl(x-\Phi_t(s)\bigr).
$$

Low-separability elements gravitate normally.

### **8.2 Collisionless and Pressureless Behavior**

Interaction strength requires overlapping geometric support.
If $\sigma_t(s_1)$ and $\sigma_t(s_2)$ are both below $\epsilon_{\mathrm{obs}}$, field-mediated interactions are exponentially suppressed.

Thus dark elements behave as:

* collisionless
* pressureless
* cold

matching CDM phenomenology.

# **9. Quantum Phenomena as Partial Geometric Separability**

Quantum behavior arises when the rupture mapping does **not fully resolve** a substrate element’s geometric identity.

Let:

$$
\sigma_t(s)
$$

measure local separability.

### **9.1 Superposition**

If the embedding $\Phi_t(s)$ cannot pick a single geometric support, the element spans several candidate supports ${x_i}$:

$$
\Phi_t(s) = \sum_i w_i(t)\, x_i,
$$

where $w_i(t)$ encode unresolved geometric identity.

This *is* quantum superposition.

### **9.2 Entanglement**

Two elements $s_1$ and $s_2$ share a cross-nonseparability:

$$
\chi_t(s_1,s_2)>0
$$

whenever their embeddings partially overlap.

This inherited overlap from the pre geometric substrate becomes entanglement.

### **9.3 Measurement**

Measurement is the **forced growth of separability** through coupling to a highly separable system:

$$
\sigma_{t+\Delta t}(s)
\approx
\sigma_t(\text{detector}).
$$

This yields apparent wavefunction collapse.

### **9.4 Uncertainty**

Precise position requires large spatial separability.
Precise momentum requires stable separability across layers.

The two cannot be maximized simultaneously because:

* position needs sharp $\Phi_t(s)$
* momentum needs smooth $\Phi_{t+\Delta t}(s)$

Thus:

$$
\Delta x\, \Delta p
\gtrsim \frac{1}{2\sigma_t(s)}.
$$

### **9.5 Wavefunction as Separability Profile**

Define the wavefunction:

$$
\psi_s(x,t)
$$

as the separability-weighted distribution of unresolved support:

$$
|\psi_s(x,t)|^2 =
\text{fraction of geometric identity unresolved near } x.
$$

### **9.6 Emergence of Classicality**

Classical behavior arises when:

$$
\sigma_t(s) \gg \epsilon_{\mathrm{obs}}(t).
$$

### **9.7 Substrate-Level Determinism**

Before rupture the substrate is deterministic.
Quantum randomness arises from geometric incompleteness, not fundamental indeterminism.

## **10. Implications and Next Steps**

This framework:

* removes the Big Bang singularity through the finite-density mapping condition
* derives the arrow of time from symmetry breaking in the rupture
* explains entropy increase as a geometric rather than statistical phenomenon
* interprets redshift as momentum stretching driven by rising separability
* reproduces standard cosmological features (expansion, cooling, structure formation) without new particle physics
* aligns naturally with general relativity, which governs the emergent manifold $M$
* provides a minimal cosmogenesis model requiring only mass, symmetry, and instability

Promising directions for future work include:

* specifying a dynamical law for the rupture sequence $(\Phi_t)$
* exploring whether the Friedmann equations arise from substrate evolution
* modeling entropy production from geometric separability
* determining whether cosmic acceleration can be derived from rupture dynamics
* extending the rupture formalism to quantum fields defined on $M$
* examining consequences for black hole thermodynamics and informational bounds

## **10.1 Potential Observational Signatures**

Although the rupture framework is conceptual, it yields several qualitative predictions that distinguish it from standard cosmology.

### 1. **Dark matter correlates with early low-separability regions**

Substrate elements with $(\sigma_t(s) < \epsilon_{\text{obs}}(t))$ behave as cold, collisionless matter.
Prediction: early spatial variations in separability should map to **non-Gaussian structure** in the dark matter distribution, especially on galactic scales.

### 2. **Cosmic acceleration may reflect late-time separability dynamics**

If the exponent $(\beta)$ in the rupture law $(\dot{\Sigma} = \alpha\, \Sigma^\beta)$ changes over time, this introduces an effective acceleration even without dark energy.
Prediction: small deviations from a constant dark-energy equation-of-state.

### 3. **Primordial power spectrum modification**

If microscopic degrees of freedom in the substrate have correlations, the rupture mapping should imprint them on the earliest separability layers.
Prediction: slight, scale-dependent departures from exact power-law primordial fluctuations.

### 4. **High-curvature deviations from GR**

If separability growth saturates at extremely late times, the mapping between matter and curvature should become mildly nonlinear.
Prediction: small corrections to GR in strong-field environments, potentially visible in black hole shadow structure or gravitational wave ringdown.

### 5. **Low-separability relics**

A small population of elements that never reach the observational threshold could form an **extra-dark** component, contributing mass but not clustering normally.
Prediction: mild discrepancies between gravitational lensing mass and cold dark matter simulations.

These signatures provide possible pathways toward empirical relevance without committing to rigid numerical predictions.

## **10.2 Additional Observational Signature: Phase-Imprinted Acceleration**

The phase-sliced dynamics suggests an additional, more specific observational signature, complementary to those listed in Section 9.1.

### **6. Phase-imprinted features in the expansion history**

Because the instantaneous expansion rate is modulated by the phase factor $f(\theta(t)) = D_{\text{eff}}(t)$, while observations sample a coarse-grained history, the model predicts:

* A **dominant smooth acceleration** driven by the effective separability component $(\rho_{\text{sep}})$, which behaves approximately like a cosmological constant when $(\beta \approx 1)$.
* On top of this, **small, correlated deviations** in the Hubble rate $(H(z))$ and the effective dark energy equation-of-state $(w(z))$, reflecting residual phase structure that does not entirely average out.

**Prediction:** future high-precision measurements of

* $(H(z))$ from standard sirens and standard candles, and
* $(w(z))$ from combined CMB, BAO, and large-scale structure data,

should reveal:

1. A baseline consistent with $(w \approx -1)$,
2. plus **small, smooth, non-random deviations** from a perfectly constant $(w)$, with a characteristic scale and pattern that trace back to the internal phase dynamics.

Such deviations would not follow the generic forms expected from simple scalar-field dark energy models, but instead exhibit a structure tied to the underlying phase-sliced separability law.

## **11. Conclusion**

This work proposes a cosmogenesis model in which finite-density spacetime emerges from a pre-geometric substrate through a structurally irreversible rupture. The Big Bang singularity is replaced by a well-defined mapping constraint, and the origin of time is attributed to increasing separability following spontaneous symmetry breaking.

The model explains finite density, cosmic expansion, redshift, entropy growth, and the arrow of time without invoking new fundamental particles, hidden dimensions, inflationary fields, or ad hoc initial conditions. Instead, these features arise naturally from the transition between pre-geometry and geometry.

The rupture framework provides a minimal, coherent, and mathematically grounded foundation for understanding the emergence of spacetime and may offer new pathways toward unifying gravitational and thermodynamic phenomena.

---

## **Appendix: A Mechanical Analogy for Emergent Time**

Imagine a tower of trampolines stacked so densely they form a continuous column. Now drop a tungsten sphere—massive, rigid, carrying enormous momentum—into the top.

As it tears through the first trampoline, three things happen at once:

1. **A rupture occurs.**
   The membrane rips as the sphere passes, leaving behind a local disturbance that continues to vibrate even after the sphere has moved on.

2. **The sphere loses a tiny fragment.**
   A single atom of tungsten is left behind between the first and second membrane. The ball keeps falling, but now it is microscopically lighter.

3. **The fall slows.**
   Having lost a bit of energy in the rupture, it takes slightly longer for the sphere to reach and tear through the next trampoline.

Now rotate the entire tower sideways.
Zoom in.
Scroll along the structure at a speed just slower than the sphere’s motion.

What you see no longer resembles a falling object.
It resembles **frames of a film**, each trampoline capturing a slightly different configuration of the system. The same sphere, the same substrate, but in different states.

Each membrane becomes a **slice**, a **layer**, a **realization of the system**, differentiated only by the cumulative effects of past ruptures.

This mechanical analogy captures the central intuition of the model:

* A substrate with no geometry can still have internal structure.
* A rupture that introduces separability can create successive “layers” that resemble snapshots of time.
* Each layer differs because each rupture transfers a tiny amount of information and energy forward into the next one.
* What we call *time* may be the ordering of these layers produced by the dynamics of the rupture.

In other words, the ball is not *moving through* time.
The layers created by each rupture **are** time.

---

## **How to Cite This Work**

**APA-style**

Fréreault, J. (2025). *A Pre-Geometric Substrate Model for the Emergence of Finite-Density Spacetime*.
https://github.com/jeremie5/pregeometric-cosmogenesis

**BibTeX**

```bibtex
@misc{frereault2025substrate,
  author       = {Jérémie Fréreault},
  title        = {A Pre-Geometric Substrate Model for the Emergence of Finite-Density Spacetime},
  year         = {2025},
  howpublished = {\url{https://github.com/jeremie5/pregeometric-cosmogenesis}},
  note         = {Conceptual cosmology paper hosted as a public repository}
}
```

---

## **License**

This work is licensed under **CC BY 4.0**.

You may:

* **Share** — copy and redistribute
* **Adapt** — remix, transform, and build upon it

As long as you provide proper **attribution**.
Full terms: [https://creativecommons.org/licenses/by/4.0/](https://creativecommons.org/licenses/by/4.0/)

---

## **Frequently Misunderstood Aspects**

**Does the model claim the universe came from nothing?**
No. It begins with a non-geometric substrate that already contains content.

**Is this a multiverse theory?**
No. Rupture layers form a temporal sequence, not multiple universes.

**Does the rupture create matter?**
No. It redistributes existing mass-energy.

**Does this require new physics?**
No. The mechanism is purely structural.

**Is density infinite before the rupture?**
Density is undefined before geometry. Infinity appears only if one misinterprets the pre-geometric phase.

**Is this just inflation?**
No. Inflation, if present, becomes a consequence of increasing separability.

**Does time exist in the 0D phase?**
No. Time appears only through the ordering of rupture layers.

**Does this contradict GR?**
No. GR governs the emergent manifold $M$. This explains why $M$ exists.

**Is it metaphysics?**
It becomes physics once the dynamics of $(\Phi_t)$ generate testable predictions.

---

## **Footer Note**

> This repository outlines a conceptual cosmogenesis framework in which finite-density spacetime emerges from a pre-geometric substrate through a rupture-driven transition. No cosmological constant, multiverse, or exotic quantum gravity machinery is assumed. Only mass content, symmetry, instability, and mapping structure.

If you made it this far: welcome to the substrate.
