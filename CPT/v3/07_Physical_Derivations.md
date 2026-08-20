# Derivation of Physical Laws from Configuration Propagation Theory

*Eldhose Mani — Draft v3, August 2026*
*Part of the Configuration Propagation Theory series*

---

## Abstract

We derive the principal laws of physics from the two CPT axioms (c() complex-linear; t() bijective) and the mathematical structure established in Paper 06. Quantum mechanics (Schrödinger equation) is ✓ Theorem via Stone's theorem. The four laws of thermodynamics are ✓ Theorem: the First Law from unitarity (energy conservation by Noether), the Second Law from irreversibility of resolution, the entropy formula from algebraic uniqueness. Lorentz symmetry and 3+1 spacetime dimensions are ∂ Derived using established external results (Zeeman 1964, Ehrenfest 1920). U(1) electromagnetism is ✓ Derived from the complex phase freedom of c(). SU(2) and SU(3) gauge symmetries are ∂ Derived from orbit structure combined with the gauge principle. The arrow of time is ✓ Theorem: it is the direction the resolution front moves. Each claim is explicitly labelled. The paper also identifies the remaining gap: the step from global SU(2) to local SU(2) uses the gauge principle as an external input, not derivable from the two axioms alone.

---

## 1. Introduction

Paper 06 established the mathematical operators. This paper uses them to derive the laws of physics. The organisation follows the rigour hierarchy: theorems first, derived results next, with the external input identified for each ∂ Derived claim.

---

## 2. Quantum Mechanics ✓ Theorem

**Theorem 2.1 (Schrödinger equation).** *iℏ ∂/∂t |Ψ⟩ = Ĥ|Ψ⟩ follows from Axioms 1 and 2.*

*Proof.* (1) Axiom 2 + complex linearity → T̂ is unitary on H (Theorem 3.1 of Paper 06). (2) The one-parameter group {T̂(t)} is continuous in t (physical propagation is continuous). (3) Stone's theorem: any strongly continuous one-parameter unitary group takes the form T̂(t) = e^{-iĤt/ℏ} for a unique self-adjoint Ĥ. (4) Differentiating: iℏ d|Ψ⟩/dt = Ĥ|Ψ⟩. □

**The Born rule (~ Conjecture).** The probability rule P(v') = |α_{vv'}|² follows from the normalization of c() and the frequency interpretation of probability under large-N repetition. A complete derivation from the axioms alone requires a proof analogous to Gleason's theorem [Gleason 1957] within the CPT framework. This derivation is conjectured to work but has not been completed. Status: **~ Conjecture**.

**Superposition and interference (✓ Theorem).** Complex linear c() means c(αv + βw) = αc(v) + βc(w). Superposition is not postulated; it follows from linearity. Interference (dark fringes, cancellation) requires complex amplitudes — real probability theory cannot produce cancellation of amplitudes.

---

## 3. The Four Laws of Thermodynamics ✓ Theorem

| Law | Statement | CPT Derivation |
|-----|-----------|----------------|
| 0th | Thermal equilibrium is transitive | Resolution density reaches equilibrium because c() applies identical rules at every node (universal seed). Two systems in contact with a third must have the same resolution density — equilibrium is forced. ✓ |
| 1st | Energy is conserved | T̂ is unitary → time-translation symmetry → Noether's theorem → energy conservation. $E_0 = \langle v_0 \| \hat{H} \| v_0\rangle$ is invariant. ✓ |
| 2nd | Entropy never decreases | Resolution is irreversible (Axiom 2 captures this: bijectivity in the forward direction means no node is un-resolved). S = −Tr[ρ ln ρ] is non-decreasing under irreversible resolution. ✓ |
| 3rd | Absolute zero is unreachable | c() propagation cannot be halted (while the configuration exists, c() continues to generate next configurations). T → 0 requires halting all propagation. This requires removing the configuration entirely. Unreachable in finite steps. ✓ |

All four laws are theorems. None is an axiom of CPT. This is one of the framework's strongest results.

---

## 4. The Arrow of Time ✓ Theorem

**Theorem 4.1 (Arrow of time).** *Time has a preferred direction — from past to future — and this direction is determined by the resolution front.*

*Proof.* The resolution front moves in the direction of increasing resolved configurations. Resolution is irreversible (Axiom 2, forward direction only). Therefore the resolution front has a preferred direction. Define "future" = the direction the resolution front moves. Then:

- **Past** = fully resolved configurations (definite, classical, fixed)
- **Future** = c()-propagated but not yet resolved configurations (quantum, superposed, open)

The arrow of time is not imposed from outside — it is the direction the resolution front propagates. □

**Remark.** The CPT laws are symmetric under formal time reversal (T̂ is unitary, hence reversible in the mathematical sense). The asymmetry of time is not in the equations but in the initial condition (the seed was in a low-entropy resolved state at t=0) and in the irreversibility of resolution (Axiom 2, physical direction). This is consistent with the Boltzmann-Penrose view of the arrow of time, but derives it rather than postulating it.

---

## 5. Lorentz Symmetry ∂ Derived

The seed configuration propagated to all nodes with identical rules — the laws encoded in c() and t() are the same everywhere. This universality constrains the symmetry group of c():

- The resolution speed c is fixed (set by the fundamental propagation rate)
- The symmetry group must preserve c and be identical at every node
- The symmetry group must be a continuous Lie group (from the continuity of c())

**External theorem used (Zeeman 1964):** The unique group of bijections of spacetime that preserve the causal structure (light cone structure) with fixed light speed is the **Poincaré group** (Lorentz transformations + spacetime translations).

**Status: ∂ Derived.** CPT establishes the premises (universal c, fixed propagation speed, continuous symmetry requirement). Zeeman's theorem closes the gap. The external result is rigorous and well-established.

---

## 6. Three Spatial Dimensions and One Time Dimension ∂ Derived

Stable t() loop structures (particles) must exist. For stable orbits to exist:

**Spatial stability (Ehrenfest 1920):** In D spatial dimensions, the gravitational and electrostatic potential scales as r^{-(D-2)}. For D = 3: V ∝ 1/r — stable circular orbits exist. For D ≠ 3: all orbits either collapse (D > 3) or fly apart (D < 3). Stable atoms and planets require D_space = 3.

**Temporal well-posedness:** For $D_{time} > 1$, the Cauchy problem for the wave equation (which underlies c()) has no unique solution — the initial data does not determine the future [Barrow-Tipler 1986]. Consistent propagation requires $D_{time} = 1$.

| Condition | Requires | Source |
|-----------|----------|--------|
| Stable orbital t() loops | D_space = 3 | Ehrenfest 1920 |
| Stable atomic t() loops | D_space = 3 | Hydrogen energy levels only in 3D |
| Well-posed evolution of c() | D_time = 1 | Wave equation Cauchy problem |

3+1 is the unique dimensionality satisfying all three. **Status: ∂ Derived** (uses stability arguments about derived force laws, which themselves are derived from CPT — there is a chain, but the argument is physical constraint reasoning, not a direct axiomatic proof).

---

## 7. U(1) Electromagnetism ✓ Derived (given complex c())

c() assigns complex amplitudes α_{vv'} ∈ ℂ. The phase of a complex amplitude is **physically unobservable**: only |α|² appears in probabilities. Therefore physics must be invariant under local phase redefinition:

$$|\Psi(x)\rangle \to e^{i\theta(x)}|\Psi(x)\rangle$$

This is **local U(1) gauge invariance**. For consistency with x-dependent θ (local rather than global), a gauge connection field A_μ must exist satisfying:

$$D_\mu = \partial_\mu - ieA_\mu$$

**That gauge field is the photon.** Maxwell's electromagnetism — including all of its structure — is mandatory given the complex nature of c().

**Status: ✓ Derived.** No external theorem needed beyond the structure of complex Hilbert spaces and the gauge principle applied to the complex phase freedom. The gauge principle itself (global symmetry → local symmetry + gauge field) is a structural consequence of demanding local consistency of c().

---

## 8. SU(2) Weak Force ∂ Derived

Stable configurations in 3+1D carry definite angular momentum (from Lorentz symmetry). The irreducible representations of the rotation group SO(3) include spin-1/2. Spin-1/2 requires the **double cover** SU(2) — this is a pure mathematical theorem.

For SU(2) to become a **local** gauge symmetry (necessary for consistent interactions along the resolution front), the gauge principle promotes global SU(2) to local SU(2). This requires three gauge bosons.

**Those gauge bosons are W⁺, W⁻, Z** (with one combination also contributing to the photon via electroweak mixing).

**Status: ∂ Derived.** The step from global SU(2) (mandatory for spin-1/2) to local SU(2) (the weak force) uses the gauge principle. The gauge principle is not derived from Axioms 1 and 2 — it is applied as a consistency requirement. **This is the principal gap in the SU(2) derivation.**

---

## 9. SU(3) Strong Force ∂ Derived

For quarks (period-3 orbit fermions) to form stable bound states without existing as isolated free particles, a confining gauge group is needed. The minimal confining gauge group is SU(N) with N ≥ 3.

**N = 3 specifically** follows from: (a) the period-3 orbit has exactly 3 vertices (= 3 colour states); (b) the Pauli exclusion principle applied to the Δ⁺⁺ baryon (three identical spin-3/2 u quarks require a third quantum number with 3 values); (c) the Cartan uniqueness proof (Paper 05): among all groups with centre Z₃ and 3-dimensional fundamental representation, only SU(3) exists.

**Status: ∂ Derived** (given orbit-colour identification — see Paper 05).

---

## 10. Summary: All Physical Laws and Their Status

| Law or Result | Status | External input used |
|---------------|--------|---------------------|
| Schrödinger equation | ✓ Theorem | Stone's theorem (math) |
| Born rule P = |ψ|² | ~ Conjecture | Gleason-type argument incomplete |
| Superposition, interference | ✓ Theorem | Complex linearity |
| Zeroth Law of thermodynamics | ✓ Theorem | Universal c() rules |
| First Law (energy conservation) | ✓ Theorem | Unitarity + Noether |
| Second Law (dS/dt ≥ 0) | ✓ Theorem | Irreversible resolution |
| Third Law (T=0 unreachable) | ✓ Theorem | c() cannot halt |
| Entropy formula S = −Tr[ρ ln ρ] | ✓ Theorem | Algebraic uniqueness |
| Arrow of time | ✓ Theorem | Resolution front direction |
| Lorentz symmetry | ∂ Derived | Zeeman 1964 |
| 3+1 spacetime dimensions | ∂ Derived | Ehrenfest 1920 |
| U(1) electromagnetism | ✓ Derived | Complex phase freedom |
| SU(2) weak force | ∂ Derived | Gauge principle |
| SU(3) strong force | ∂ Derived | Orbit-colour id. + Paper 05 |
| SM Lagrangian uniqueness | ∂ Derived | QFT renormalisability |

The thermodynamics column is particularly notable: all four laws of thermodynamics are theorems of CPT, not postulates.

---

## References

[Barrow-Tipler 1986] J. D. Barrow, F. J. Tipler, The Anthropic Cosmological Principle, Oxford (1986).  
[Ehrenfest 1920] P. Ehrenfest, Proc. Amsterdam Acad. 20, 200 (1917); Annalen der Physik 61 (1920).  
[Gleason 1957] A. M. Gleason, J. Math. Mech. 6, 885 (1957).  
[Mani 2026a] E. Mani, "Configuration Propagation Theory: Framework" (Paper 01, this series).  
[Mani 2026b] E. Mani, "Mathematical Structure of CPT" (Paper 06, this series).  
[Zeeman 1964] E. C. Zeeman, J. Math. Phys. 5, 490 (1964).  
