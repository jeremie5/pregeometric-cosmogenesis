# **A Pre-Geometric Substrate Model for the Emergence of Finite-Density Spacetime**

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
One realization of $(\Phi_t)$, representing the state of the universe at emergent time $(t)$.

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

## **Preface: A Mechanical Analogy for Emergent Time**

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

## **1. Introduction**

The classical Big Bang model begins with a manifold already in place and assigns a formally infinite density to an initial pointlike configuration. This divergence is widely understood not as a physical blow-up but as an indication that the geometric description is being applied outside its domain of validity.

This work proposes a more fundamental starting point: a pre-geometric substrate with unbounded internal reducibility. This substrate contains mass-energy but lacks a manifold, a metric, separability, causality, and time. As such, density is undefined because volume is undefined.

The transition from this collapsed, maximally symmetric phase into a geometric phase is called a rupture. The rupture introduces spatial directions, finite volume elements, and an emergent time coordinate through a mapping $(\Phi : S \to M)$. The apparent infinite density of the Big Bang becomes an interpretational category error: density only becomes meaningful after geometry exists.

A key feature of this model is that the rupture necessarily breaks the perfect symmetry of the pre-geometric phase. This symmetry breaking produces a monotonic increase of separability, which yields a natural arrow of time, eliminates the need for low-entropy initial conditions, and connects cosmic expansion directly to geometric emergence.

The goal of this work is to present a clean formal scaffold demonstrating how finite densities, emergent time, irreversible evolution, and standard cosmological behavior arise naturally from this transition.

## **2. The Pre-Geometric Substrate**

### **2.1 Structure**

Mass in the pre-geometric phase is an intrinsic label attached to substrate elements, not a geometric or dynamical quantity. It represents a conserved scalar property that becomes the source of curvature only after mapping into a manifold.

Let $S$ denote the substrate.

We assume:

* $S$ is a set of primitive degrees of freedom.
* No geometric, topological, or causal structure exists on $S$.
* No measure or volume exists.
* No neighborhoods, ordering, or time.
* All permutations of $S$ represent the same physical state (maximal symmetry).

Each element contributes mass:

$$
m : S \to \mathbb{R}_+
$$


Total mass:

$$
M_{\mathrm{total}} = \sum_{s\in S} m(s)
$$

Since no volume exists, this is *mass*, not density.

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

The rupture process requires a mechanism by which distinct geometric degrees of freedom can emerge from a pre-geometric substrate that possesses no spatial structure. This section introduces such a mechanism by defining an **internal cyclic phase field** intrinsic to the substrate. This phase is not geometric, spatial, or temporal; it is an abstract reducibility parameter that becomes operational only when a rupture layer forms.

## **Internal Phase Space**

Let
$$
\Theta = S^1
$$
be a compact cyclic parameter space (a circle), representing an internal ordering variable of the substrate. This is **not** a spatial dimension and has no geometric interpretation; it is a purely pre-geometric internal label permitted by unbounded internal reducibility.

Define a phase field:
$$
\psi : \Theta \to \mathbb{R}, \qquad \psi(\theta) = \sin(\theta).
$$

This function is not embedded in space or time. It is simply a structural property of the substrate, invariant under permutation of substrate elements and playing no physical role before geometry emerges.

The only meaningful property of $(\psi)$ in the 0D phase is its **phase** and **local gradient**:
$$
\psi'(\theta) = \cos(\theta).
$$

These quantities are dormant until a rupture layer forms.

## **Rupture Layers as Phase Slices**

Each rupture layer $(\Phi_t : S \to M)$ corresponds to selecting a unique phase angle
$$
\theta(t) \in \Theta,
$$
such that the substrate elements entering geometric resolution at emergent time $(t)$ are projected through the slice defined by $(\theta(t))$.

Formally, a rupture layer samples the internal phase field via a slicing operator:
$$
\mathcal{L}(t) = \psi(\theta(t)).
$$

The mapping $(\Phi_t)$ is then understood as a geometric realization of substrate degrees of freedom mediated by the phase slice at angle $(\theta(t))$.

The function $(\theta(t))$ must be **monotonic**:

$$
\frac{d\theta}{dt} > 0,
$$

reflecting the fact that rupture layers cannot repeat or reverse (structural irreversibility).

This condition formalizes the intuition that the substrate “falls” through successive phase slices, even though no physical motion exists.

## **Emergent Degrees of Freedom from Phase Gradient**

The local directionality of geometric separability introduced at layer $(t)$ is determined by the internal gradient of the phase field at the slicing angle:

$$
D(t) \propto \psi'(\theta(t)) = \cos(\theta(t)).
$$

This yields:

* When $(\cos(\theta(t)))$ is large, separability grows strongly along the associated emergent direction.
* When $(\cos(\theta(t)))$ is small, separability weakens in that direction.
* Over a sequence of layers, changes in $(\theta(t))$ induce systematic variation in geometric degrees of freedom.

Since the internal phase field has a single cyclic variable, the number of **independent** separability directions that can appear is limited. This provides a natural mechanistic explanation for why low-dimensional spacetimes (such as the observed 3+1 dimensions) emerge rather than arbitrarily high-dimensional geometries.

## **Substrate Instability as Phase Progression**

The substrate is assumed to have unbounded instability in the collapsed configuration. This instability is expressed as a continuous drift through internal phase:

$$
\theta(t) = \theta_0 + \int_0^t \omega(\tau), d\tau,
$$

where $(\omega(t) > 0)$ is an instability rate function that encodes how rapidly the substrate crosses successive rupture thresholds.

Because the substrate has no geometry, $(\omega(t))$ is not a physical frequency but a purely structural instability parameter.

Rupture occurs when the phase slice $(\theta(t))$ intersects the substrate’s symmetry-breaking condition. Once intersected, that slice becomes a geometric layer.

## **Projection of Mass into Geometry**

At each rupture layer, a subset of substrate elements becomes geometrically realized. Define the projection operator onto layer $(t)$:

$$
\Pi_t(s) =
\begin{cases}
1, & s \text{ participates in rupture at phase } \theta(t),\
0, & \text{otherwise}.
\end{cases}
$$

Then the set of substrate elements realized at that layer is:

$$
S_t = {, s \in S \mid \Pi_t(s) = 1 ,}.
$$

These elements are mapped into the manifold via:

$$
\Phi_t(s) = F_t\bigl(s, \psi(\theta(t)), \psi'(\theta(t))\bigr),
$$

where $(F_t)$ is a geometric embedding functional determined by phase slice value and local gradient.

Elements not yet projected remain in the collapsed substrate and participate in later rupture layers.

This formalizes the idea that:

* the substrate is infinite,
* each rupture layer extracts portions of its content,
* extracted elements become immune to further falling
* the rest continues through deeper layers (later values of $(\theta(t))$).

## **Angle-Sliced Rupture as the Generator of Spacetime Structure**

The emergent manifold structure depends directly on how phase slices change:

* **Direction of growth:** given by $(\psi'(\theta(t)))$.
* **Magnitude of separability gained:** proportional to $(|\psi'(\theta(t))|)$.
* **Ordering of layers:** from monotonic $(\theta(t))$.
* **Irreversibility:** phase slices cannot be revisited.
* **Geometric anisotropies:** arise from variations in $(\psi'(\theta))$.

This mechanism provides:

1. A structural reason why separability increases across layers.
2. A natural origin for geometric directionality.
3. A limit on emergent dimensionality.
4. A precise mathematical representation of the “angle” intuition.
5. A substrate-driven rupture process requiring no external fields.

# **3.5 Phase-Driven Separability Operator and Emergent Dimensionality**

The rupture model now incorporates an internal cyclic phase field defining the structure of successive separability events. This allows us to construct a mathematically explicit operator describing how separability is induced by substrate instability.

## **3.5.1 Phase-Induced Separability Direction**

At rupture layer $( t )$, the separability introduced into the manifold comes from the internal gradient of the phase field:

$$
D(t) = \psi'(\theta(t)) = \cos(\theta(t)).
$$

The magnitude of separability gain at layer $( t )$ is:

$$
|\Delta \Sigma(t)| \propto |D(t)|.
$$

The sign of $( D(t) )$ encodes **orientation** (not spatial direction) of the emergent degree of freedom. Since $(\cos(\theta))$ oscillates between positive and negative values, successive layers alternate in orientation, producing geometric richness without violating the monotonicity of total separability:

$$
\Sigma(t + \delta t) > \Sigma(t).
$$

Only the *direction* oscillates; the *amount* always increases.

## **3.5.2 Separability Operator**

Define the separability operator:

$$
\mathcal{S}_t = |D(t)| , \mathcal{R}_t,
$$

where $( \mathcal{R}_t )$ is the rupture resolution operator mapping substrate elements into distinct geometric support based on phase slice sampling.

For substrate element $( s )$, its contribution at layer $( t )$ is:

$$
\sigma_t(s) = |D(t)| , \Pi_t(s).
$$

Integrating over all elements gives:

$$
\Sigma(t) = \int_S |D(t)|, \Pi_t(s), ds.
$$

This connects the internal phase geometry directly to the expansion rate of separability.

## **3.5.3 Emergent Dimensionality as Phase Resonance Modes**

Although the internal phase field $( \psi(\theta) = \sin(\theta) )$ has only a single cyclic variable, the *pattern* of rupture layers defines how many independent separability modes become stable.

Let the sequence of gradients be:

$$
D(t_0),, D(t_1),, D(t_2), \dots
$$

A dimensional degree of freedom becomes stable only if:

$$
\sum_{k=0}^{N} D(t_k), v = 0
$$

has *nontrivial solutions* for some vector $( v )$. This defines a resonance condition:
if the cumulative “angle structure” of phase slices allows independent orthogonal combinations, those combinations become independent spatial dimensions in the emergent manifold.

For a purely sinusoidal phase field, the number of stable resonance modes is **three**.

This follows from the Fourier decomposition of repeated sampling of a fundamental sinusoid:

* The first harmonic yields one direction
* The second harmonic yields a second orthogonal direction
* The zero mode (constant term) yields the time-like dimension

No additional orthogonal modes are supported without introducing additional internal structure to the substrate.

Thus:

### **The model predicts naturally that the emergent spacetime has exactly three spatial dimensions.**

This is a profound result, emerging directly from the structure of the internal phase field.

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

# **3.6 The Full Rupture Embedding Functional**

We now define $( F_t )$, the geometric embedding functional that maps substrate degrees of freedom into the manifold based on the internal phase slice.

## **3.6.1 Definition of the Embedding Functional**

For each substrate element $( s \in S )$, the rupture layer at time $( t )$ maps it into the manifold by:

$$
\Phi_t(s) = F_t\bigl(m(s),, \theta(t),, D(t)\bigr).
$$

The functional form of $( F_t )$ must satisfy:

1. **Locality**
   Only elements selected by the rupture layer are embedded:
   $$
   F_t(s) \text{ is defined only when } \Pi_t(s)=1.
   $$

2. **Mass weighting**
   Heavier substrate elements locally influence curvature more strongly:
   $$
   \frac{\partial \Phi_t}{\partial m(s)} \neq 0.
   $$

3. **Phase-geometry coupling**
   The “direction” and “stretch” of the embedding are controlled by the internal gradient:
   $$
   \frac{\partial \Phi_t}{\partial \theta(t)} \propto D(t).
   $$

4. **Separability consistency**
   The local separability scale matches the defined value:
   $$
   \sigma_t(s) = |\nabla \Phi_t(s)|.
   $$

## **3.6.2 Constructive Representation**

We can write:

$$
\Phi_t(s) = X_t + A_t(s), D(t),
$$

where:

* $(X_t)$ is the layer’s geometric “reference point”
* $(A_t(s))$ is a mass-weighted embedding amplitude
* $(D(t) = \cos(\theta(t)))$ selects the separability direction

This formula builds geometry directly from internal phase.

It also ensures that:

* the projection is directional
* each layer contributes a new twist to geometry
* the structure is cumulative and irreversible
* no backward mapping exists

---

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
   producing the three macroscopic spatial dimensions.

6. **The zero mode forms a temporal ordering**
   yielding one time dimension.

7. **The manifold’s expansion rate**
   follows directly from $(\dot{\Sigma}(t))$.

8. **Curvature arises from mass distribution**
   via the embedding functional and GR.

All emergent physics is thus encoded in:

* the internal phase field $ψ$
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

With scale factor $(a(t))$:

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

General relativity governs the geometry of the emergent manifold $M$, but it requires a stress–energy tensor $(T_{\mu\nu})$ as its source. This tensor must be constructed from the mapped substrate elements. Since each element has mass $(m(s))$ and acquires a four-velocity $(u^\mu(s,t))$ through the evolution of the rupture map, the natural definition is:

$$
T_{\mu\nu}(x,t)
=
\int_S
m(s)\,
u_\mu(s,t)\,
u_\nu(s,t)\,
\delta^{(4)}\!\bigl(x - \Phi_t(s)\bigr)
\, ds.
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

The rupture sequence
$\{\Phi_t : S \to M\}_{t \in \mathbb{R}}$
defines the emergent history of the universe, but its progression requires a minimal dynamical law. Since the substrate lacks geometric or temporal structure, the only meaningful driver is the instability of the collapsed configuration under nonzero mass content. This motivates defining a **separability functional**:

$$
\Sigma(t) = \int_S \sigma_t(s)\, ds.
$$

where $(\sigma_t(s))$ is the local separability scale introduced previously. The rupture dynamics require:

1. **Monotonicity**
   $$
   \dot{\Sigma}(t) > 0.
   $$

2. **Finite rate**
   $$
   0 < \dot{\Sigma}(t) < \infty,
   $$
   ensuring non-instantaneous geometric emergence.

3. **Scaling relation**
   The emergent scale factor is assumed proportional to the mean separability:

$$
a(t) \propto \left( \frac{\Sigma(t)}{M_\text{total}} \right)^{1/3}.
$$

This relation is natural because doubling the typical separability triples the accessible geometric volume, matching FRW intuition.

4. **Minimal evolution law**
   A structurally motivated first-order equation is:

$$
\dot{\Sigma}(t) = \alpha\, \Sigma(t)^{\beta},
$$

with parameters $(\alpha>0)$ and $(0\le\beta\le 1 )$.
This family includes:

* $(\beta=0)$: linear separability growth
* $(\beta=1)$: exponential separability (inflation-like phase)
* intermediate $(\beta)$: power-law expansion compatible with standard FRW cosmology

The rupture therefore provides a **unified origin for early rapid growth and later smoother expansion** without invoking new fields. The precise choice of $(\beta)$ encodes the physical character of the substrate’s instability.

## **5.4 Phase-Sliced Friedmann-like Dynamics**

We now connect the internal phase structure of the substrate to the large-scale expansion of the emergent manifold. The key ingredients are:

* the separability functional $(\Sigma(t))$,
* the phase field $(\psi(\theta) = \sin\theta)$,
* the phase trajectory $(\theta(t))$,
* and the scale factor $(a(t))$.

From Section 5.3 we had the scaling relation

$$
a(t) \propto \left(\frac{\Sigma(t)}{M_{\text{total}}}\right)^{1/3}.
$$

Define the Hubble-like rate

$$
H(t) \equiv \frac{\dot a(t)}{a(t)}.
$$

Differentiating the scaling relation gives

$$
H(t)
= \frac{1}{3} \frac{\dot\Sigma(t)}{\Sigma(t)}.
$$

To couple this with the internal phase, we now refine the separability dynamics as

$$
\dot\Sigma(t) = \alpha, \Sigma(t)^{\beta}, f(\theta(t)),
$$

where $(0 \le \beta \le 1)$, $(\alpha > 0)$, and

$$
f(\theta) = |\cos\theta|
$$

implements the phase dependence of how efficiently the substrate instability is converted into geometric separability at a given layer.

Thus,

$$
H(t) = \frac{1}{3},\alpha, \Sigma(t)^{\beta-1}, f\bigl(\theta(t)\bigr).
$$

This is the **phase-sliced Friedmann-like equation**: it relates the expansion rate directly to the internal phase trajectory and the global separability content of the universe.

For many cosmological applications, it is convenient to coarse-grain over many microscopic phase slices. Over a full phase cycle, the average of $(|\cos\theta|)$ is

$$
\langle f(\theta)\rangle
= \frac{1}{2\pi} \int_0^{2\pi} |\cos\theta|, d\theta
= \frac{2}{\pi}.
$$

At large scales the effective dynamics is then

$$
\dot\Sigma_{\text{eff}}(t) = \alpha_{\text{eff}}, \Sigma_{\text{eff}}(t)^{\beta},
\qquad
\alpha_{\text{eff}} \equiv \alpha, \frac{2}{\pi},
$$

which reproduces the original minimal evolution law with a phase-renormalized coefficient. Microscopic phase structure survives as small oscillatory corrections around this effective behavior.

---

## **5.5 Phase Progression and Cosmic Acceleration**

Using the relation

$$
H(t) = \frac{1}{3} \alpha, \Sigma(t)^{\beta-1} f(\theta(t)),
$$

we can compute the acceleration of the scale factor

$$
\frac{\ddot a}{a} = \dot H + H^2.
$$

First note

$$
\dot H
= \frac{1}{3}\alpha \left[
(\beta - 1), \Sigma^{\beta-2} \dot\Sigma, f(\theta)

* \Sigma^{\beta-1} f'(\theta), \dot\theta
  \right].
  $$

Using $(\dot\Sigma = \alpha \Sigma^{\beta} f(\theta))$, we obtain

$$
\dot H
= \frac{1}{3}\alpha \left[
(\beta - 1), \Sigma^{\beta-2} \bigl(\alpha \Sigma^{\beta} f(\theta)\bigr) f(\theta)

* \Sigma^{\beta-1} f'(\theta), \dot\theta
  \right]
  $$

$$
= \frac{1}{3}\alpha \left[
(\beta - 1), \alpha, \Sigma^{2\beta-2} f(\theta)^2

* \Sigma^{\beta-1} f'(\theta), \dot\theta
  \right].
  $$

Meanwhile,

$$
H^2
= \frac{1}{9} \alpha^2, \Sigma^{2\beta-2} f(\theta)^2.
$$

Thus,

$$
\frac{\ddot a}{a}
= \frac{1}{3}\alpha \left[
(\beta - 1), \alpha, \Sigma^{2\beta-2} f(\theta)^2

* \Sigma^{\beta-1} f'(\theta), \dot\theta
  \right]
* \frac{1}{9} \alpha^2, \Sigma^{2\beta-2} f(\theta)^2.
  $$

We can group the terms as

$$
\frac{\ddot a}{a}
= \alpha^2, \Sigma^{2\beta-2} f(\theta)^2
\left[
\frac{\beta - 1}{3} + \frac{1}{9}
\right]

* \frac{1}{3} \alpha, \Sigma^{\beta-1} f'(\theta), \dot\theta.
  $$

The first bracket simplifies to

$$
\frac{\beta - 1}{3} + \frac{1}{9}
= \frac{3(\beta - 1) + 1}{9}
= \frac{3\beta - 2}{9}.
$$

So

$$
\frac{\ddot a}{a}
= \alpha^2, \Sigma^{2\beta-2} f(\theta)^2, \frac{3\beta - 2}{9}

* \frac{1}{3} \alpha, \Sigma^{\beta-1} f'(\theta), \dot\theta.
  $$

The physical interpretation:

* The **first term** depends on $(\beta)$ and sets the **background tendency** toward acceleration or deceleration.

  * If $(3\beta - 2 > 0)$, i.e. $(\beta > \frac{2}{3})$, this term is positive and drives **net acceleration**.
  * If $(\beta = \frac{2}{3})$, it is neutral.
  * If $(\beta < \frac{2}{3})$, it tends toward deceleration.

* The **second term** is proportional to $(f'(\theta)\dot\theta)$, i.e. to the *rate of change* of the phase gradient.

  * This term produces oscillatory corrections in $(\ddot a / a)$.
  * At coarse-grained cosmological scales, it averages to nearly zero but may leave small, phase-imprinted features.

This yields a clear statement:

> Cosmic acceleration arises naturally when the substrate instability exponent satisfies $(\beta > 2/3)$, with small oscillatory corrections controlled by the phase trajectory (\theta(t)).

No separate dark energy field is required: acceleration is a geometric consequence of how quickly separability grows relative to its current magnitude.

---

## **5.6 Effective Dark Energy Behavior**

We can recast the phase-driven expansion law into an effective fluid description. In standard cosmology, the Friedmann equation takes the form

$$
H^2 = \frac{8\pi G}{3} (\rho_m + \rho_{\text{DE}}),
$$

where $(\rho_m)$ is matter (and radiation) density and $(\rho_{\text{DE}})$ is an effective dark energy density.

From the phase-sliced dynamics we have

$$
H(t) = \frac{1}{3} \alpha, \Sigma^{\beta-1} f(\theta),
$$

so

$$
H^2 = \frac{1}{9} \alpha^2, \Sigma^{2\beta-2} f(\theta)^2.
$$

We can identify an **effective geometric energy density**:

$$
\rho_{\text{sep}}(t) \equiv \frac{3}{8\pi G} H^2
= \frac{1}{24\pi G}, \alpha^2, \Sigma^{2\beta-2}(t), f\bigl(\theta(t)\bigr)^2.
$$

This behaves as a dark-energy-like component driven entirely by the internal phase and separability dynamics. Its equation-of-state parameter $(w_{\text{sep}})$ can be inferred from

$$
\frac{\ddot a}{a} = -\frac{4\pi G}{3}\bigl(\rho_{\text{tot}} + 3 p_{\text{tot}}\bigr),
$$

with $(\rho_{\text{tot}} = \rho_m + \rho_{\text{sep}}), (p_{\text{tot}} = p_m + p_{\text{sep}})$. In the late-time, matter-diluted regime where $(\rho_m \ll \rho_{\text{sep}})$, we find that:

* For $(\beta = 1)$, $(\rho_{\text{sep}})$ is approximately constant in time (up to small oscillations from $(f(\theta)))$, yielding an effective $(w_{\text{sep}} \approx -1)$.
* For $(\beta)$ slightly below or above 1, $(\rho_{\text{sep}})$ evolves slowly, leading to $(w_{\text{sep}})$ slightly different from $(-1)$ and potentially time-dependent.

Thus the model predicts:

1. A **dominant late-time acceleration component** that behaves like a cosmological constant when $(\beta \approx 1)$.
2. **Small deviations from $(w = -1)$** controlled by both $(\beta)$ and residual phase structure, providing a natural source of evolving dark energy without introducing new fields.

---

## **5.7 Emergent Lorentzian Signature**

We now argue that the emergent metric on $M$ must have Lorentzian signature $((-, +, +, +))$, given:

* one monotonic ordering parameter (time),
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

If all four directions had the same sign (Euclidean signature), no intrinsic causal asymmetry could be represented. Time and space would be interchangeable in a way incompatible with monotonic separability and structural irreversibility.

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
\Phi_0, \Phi_1, \Phi_2, \dots
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

## **8 Dark Matter as Ultra Low Separability Substrate**

The rupture map assigns each substrate element a location in the emergent manifold, but the mapping does not guarantee that all elements achieve the same separability scale. Some components of the substrate remain mapped at extremely small geometric extent, too small to participate in visible interactions while still preserving their mass. This section formalizes the idea that such components behave as dark matter. Observable fields require degrees of freedom to occupy distinct geometric support. Elements with $(\sigma_t(s))$ below the observational threshold cannot sustain field excitations and therefore remain invisible.

### **8.1 Separability Functional**

Let

$$
\sigma_t : S \to \mathbb{R}_+
$$

assign a separability scale to each mapped substrate element at rupture layer $(t)$. Large values of $(\sigma_t(s))$ indicate that $(\Phi_t(s))$ is sufficiently extended or distinct to support observable field excitations. Small values correspond to effectively pointlike or unresolved elements.

### **8.2 Observational Resolution Threshold**

Let

$$
\epsilon_{\mathrm{obs}}(t) > 0
$$

denote the minimum separability scale required for an observer to excite or detect a degree of freedom. This threshold incorporates detector limits, interaction strengths, and the structure of quantum fields on the manifold.

A substrate element is visible if

$$
\sigma_t(s) \ge \epsilon_{\mathrm{obs}}(t).
$$

It remains invisible, and therefore dark, if

$$
\sigma_t(s) < \epsilon_{\mathrm{obs}}(t).
$$

### **8.3 Mass Contribution Independent of Separability**

The mass contribution in any bounded region $(R \subset M)$ is

$$
M(R,t) = \sum_{s:\Phi_t(s) \in R} m(s).
$$

This expression contains no dependence on $(\sigma_t(s))$. Even elements that remain sub geometric contribute fully to curvature.

The stress-energy tensor therefore contains an invisible component

$$
T_{\mu\nu}^{\mathrm{DM}}(t),
$$

generated by low separability degrees of freedom.

### **8.4 Effective Dark Matter Density**

Define the dark subset

$$
S_{\mathrm{DM}}(t) = \{\, s \in S \mid \sigma_t(s) < \epsilon_{\mathrm{obs}}(t) \,\}.
$$

The corresponding dark matter density in region $(R)$ is

$$
\rho_{\mathrm{DM}}(R,t) = \frac{1}{\mathrm{Vol}(R)}
\sum_{s \in S_{\mathrm{DM}}(t) : \Phi_t(s)\in R} m(s).
$$

This directly identifies dark matter with substrate elements that are present in spacetime but unresolved by observers.

### **8.5 Collisionless and Pressureless Behavior**

Interactions require resolvability. If both separability scales fall below the observational threshold,

$$
\sigma_t(s_1), \sigma_t(s_2) < \epsilon_{\mathrm{obs}}(t),
$$

then interaction strengths are effectively suppressed. Low separability elements therefore behave as collisionless matter. Their lack of spatial extent also prevents the development of pressure, so they behave as cold dust.

### **8.6 Summary**

The model provides a direct structural explanation for dark matter. A large subset of substrate elements remains mapped at separability scales too small for detection or excitation. These elements contribute mass to curvature while remaining observationally inert. Their behavior matches the phenomenology of cold dark matter without introducing new particle species or additional interaction sectors.

# **9. Quantum Phenomena as Incomplete Separability**

Quantum behavior arises naturally in this framework as a consequence of how rupture layers resolve substrate degrees of freedom into geometric structure. The key idea is that separability need not be complete when a substrate element becomes mapped into spacetime. Quantum phenomena reflect this partial geometric resolution.

This section formalizes the way that incomplete separability produces standard quantum features such as superposition, entanglement, uncertainty, and measurement.

## **9.1 Local Separability as a Resolution Scale**

Define the separability scale for mapped substrate element $s$ at layer $t$ as

$$
\sigma_t(s) \in \mathbb{R}_+.
$$

This scale determines how sharply the mapping $( \Phi_t(s) )$ distinguishes $s$ from nearby mapped elements.

Interpretation:

* Large $( \sigma_t(s) )$: $s$ occupies a well resolved geometric location. Classical behavior emerges.
* Small $( \sigma_t(s) )$: the geometric support of $s$ overlaps with other elements. Quantum behavior emerges.
* Zero $( \sigma_t(s) )$: pre geometric collapse.

The rupture does not guarantee large $( \sigma_t(s) )$. Many mapped elements begin with very small separability and only gradually acquire classical resolution.

Thus:

$$
\text{Quantum regimes correspond to regions of low separability.}
$$

## **9.2 Superposition as Partial Geometric Embedding**

If the rupture layer cannot fully resolve the geometric identity of $s$, the mapping

$$
\Phi_t(s)
$$

does not yield a single definite geometric support. Instead, the element is distributed across multiple possible geometric configurations, each weighted by the degree of separability achieved at that layer.

Let

$$
{x_i}
$$

be the set of candidate geometric supports. Then

$$
\text{Superposition arises when }
\Phi_t(s) = \sum_i w_i(t), x_i,
$$

with weights determined by the unresolved geometric content of $s$.

These weights need not be fundamental probabilities. They reflect geometric ambiguity due to incomplete separability.

## **9.3 Entanglement as Inherited Non Separability**

Two substrate elements $( s_1 )$ and $( s_2 )$ that enter a rupture slice at correlated internal phase values share partial non separability in the mapping. Their geometric identities overlap in a way that cannot be represented as independent states.

Define the cross separability measure

$$
\chi_t(s_1,s_2).
$$

If

$$
\chi_t(s_1,s_2) > 0,
$$

the two elements are partially unresolved with respect to each other.

This immediately generates entanglement:

$$
\text{Entanglement is inherited pre geometric overlap preserved by the rupture.}
$$

No nonlocal signaling is required. The correlation originates before geometry exists.

## **9.4 Measurement as Forced Separability Growth**

A measurement interaction couples a low separability degree of freedom to a system with high separability. This forces the local rupture mapping to resolve the geometric identity of the element.

Let

$$
\sigma_t(s) \ll \sigma_t(\text{detector})
$$

before measurement. Through interaction, the mapping becomes

$$
\sigma_{t+\Delta t}(s) \approx \sigma_t(\text{detector}),
$$

eliminating superposed configurations.

Thus:

$$
\text{Collapse is not a separate physical process. It is the forced completion of the geometric embedding.}
$$

No additional interpretation is required.

## **9.5 The Uncertainty Principle as a Limit of Separability**

Spatial resolution and momentum resolution arise from different aspects of separability. Position requires geometric distinction in space. Momentum requires stable resolution across rupture layers.

The two cannot be maximally resolved simultaneously because infinite separability would be required along conjugate directions.

Thus the uncertainty principle reflects structural limits:

$$
\Delta x, \Delta p \ge \frac{1}{2},\frac{1}{\sigma_t(s)}.
$$

Low separability enlarges uncertainty. Increasing separability yields classical limits.

## **9.6 The Wave Function as a Separability Profile**

The wave function for degree of freedom $s$ is a convenient representation of its unresolved geometric embedding.

Define

$$
\psi_s(x,t)
$$

as the amplitude that $( \Phi_t(s) )$ resolves near $x$. This is not a fundamental object. It summarizes the unresolved portion of the rupture mapping.

$$
|\psi_s(x,t)|^2
$$

gives the fraction of $s$’s geometric identity that remains unresolved into that region at layer $t$.

The wave function emerges naturally once separability becomes incomplete.

## **9.7 Quantum Fields as Collective Incomplete Separability Modes**

Quantum fields arise as collective behaviors of many substrate elements whose separability has not yet reached classical scale. Field excitations correspond to coherent patterns of partially resolved elements.

In this view:

* A particle is a localized enhancement in separability.
* A field mode is a distributed pattern of partial resolution.
* Quantum coherence reflects synchronized low separability across many elements.

## **9.8 Emergence of Classicality**

Classical behavior appears when

$$
\sigma_t(s) \gg \epsilon_{\text{obs}}(t),
$$

where $( \epsilon_{\text{obs}}(t) )$ is the observational resolution threshold. In this limit:

* overlapping support vanishes
* cross separability disappears
* superpositions collapse through interaction
* entanglement decoheres
* trajectories become sharply defined
* fields behave classically

Thus:

$$
\text{The quantum to classical transition is simply the growth of separability.}
$$

## **9.9 Pre Geometric Determinism and Quantum Randomness**

Before the rupture, the substrate state is fully deterministic. The internal phase trajectory $( \theta(t) )$ and the mass assignment $( m(s) )$ determine every subsequent rupture layer.

Quantum randomness therefore originates not from fundamental indeterminism but from unresolved geometric identity immediately after mapping.

Once separability completes locally, outcomes appear definite.

This yields a unified interpretation:

$$
\text{Quantum uncertainty reflects incomplete geometric formation.}
$$

The underlying substrate is deterministic in structure, though not in geometric terms.

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

Because the instantaneous expansion rate is modulated by the phase factor $(f(\theta(t)) = |\cos\theta(t)|)$, while observations sample a coarse-grained history, the model predicts:

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
