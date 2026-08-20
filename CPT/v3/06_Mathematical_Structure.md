# The Mathematical Structure of Configuration Propagation Theory

*Eldhose Mani — Draft v3, August 2026*
*Part of the Configuration Propagation Theory series*

---

## Abstract

We develop the formal mathematical framework of Configuration Propagation Theory (CPT). The configuration space is a complex separable Hilbert space H, forced by the complex-linearity of the propagation function c(). The propagation operator Ĉ and transformation operator T̂ are defined precisely; bijectivity of t() uniquely implies unitarity of T̂ on H. The fixed-point equation v₀ = T̂·Ĉ(v₀) is shown to be equivalent to the ground-state eigenvalue equation Ĥ|v₀⟩ = E₀|v₀⟩ via Stone's theorem. The requirement that the Hamiltonian Ĥ be invariant under the derived symmetry group G = Poincaré × U(1) × SU(2) × SU(3) and renormalizable uniquely selects the Standard Model Lagrangian. The von Neumann entropy formula S = −Tr[ρ ln ρ] is shown to be the unique function satisfying four algebraically necessary properties of the CPT propagation structure. The paper also establishes the boundary structure (Hubble horizon as soft boundary) and derives quantum tunneling as the natural leakage of c() beyond the horizon. All derivations from the two CPT axioms are explicitly labelled; external mathematical theorems used (Stone, Zeeman, uniqueness of von Neumann entropy) are cited.

---

## 1. Introduction

Paper 01 of this series stated the two CPT axioms and gave an overview of what follows from them. This paper develops the mathematical formalism in full, establishing the Hilbert space structure, the operator algebra, and the fixed-point equation in rigorous terms. Paper 07 applies this formalism to derive the physical laws.

---

## 2. Configuration Space

**Definition 2.1.** The configuration Hilbert space is:

$$\mathcal{H} = \overline{\text{span}_\mathbb{C}\{|v\rangle : v \in C\}}$$

Configurations $v \in C$ form an orthonormal basis. Their complex superpositions form the full quantum state space. This is the quantum Hilbert space — not an assumption, but a consequence of Axiom 1 (c() is complex-valued and linear).

**Remark.** In standard quantum mechanics, the Hilbert space structure is postulated. In CPT, it is derived: since c() assigns complex amplitudes, and since states that differ only in global phase are physically equivalent (as probabilities depend only on |α|²), the set of physically distinct states carries exactly the structure of a complex Hilbert space.

---

## 3. The Core Operators

### 3.1 The Propagation Operator Ĉ

$$\hat{C} : \mathcal{H} \to \mathcal{H} \otimes \mathcal{H}$$

$$\hat{C}|v\rangle = \sum_{v' \in C} \alpha_{vv'}\, |v\rangle \otimes |v'\rangle$$

where $\alpha_{vv'} \in \mathbb{C}$ is the complex amplitude for propagation from configuration v to configuration v'.

**Properties:**
- $|\alpha_{vv'}|^2$ is the probability for configuration v to propagate to v'
- Non-local: v' need not be spatially adjacent; edges are dynamically generated
- Normalization: $\sum_{v'} |\alpha_{vv'}|^2 = 1$ for each v (probability-preserving)
- The tensor product $\mathcal{H} \otimes \mathcal{H}$ is forced because c() is generative — the source configuration v persists while v' is created

### 3.2 The Transformation Operator T̂

$$\hat{T} : \mathcal{H} \to \mathcal{H}, \qquad \hat{T}^\dagger \hat{T} = \mathbb{1}$$

T̂ is unitary. This follows necessarily from Axiom 2:

**Theorem 3.1 (Bijection implies unitarity — ✓ Theorem).** *If t : H → H is bijective and linear over ℂ, then t is unitary (i.e., T̂†T̂ = 𝟙).*

*Proof.* Bijectivity means t has an inverse t⁻¹. Linearity over ℂ means T̂ is a linear operator. For a linear bijection on a complex Hilbert space, preservation of inner products (= no information loss) implies unitarity. Conversely, unitarity implies bijectivity. The two conditions are equivalent for linear operators on complex Hilbert space. □

### 3.3 Global Evolution

One Planck step of global evolution:

$$|\Psi(n+1)\rangle = \hat{T} \cdot \hat{C}\,|\Psi(n)\rangle$$

In the continuum limit (many Planck steps per macroscopic time interval), with $\hat{T} = e^{-i\hat{H}\delta t/\hbar}$ (from Stone's theorem, proved in Paper 01):

$$i\hbar \frac{\partial}{\partial t}|\Psi\rangle = \hat{H}|\Psi\rangle \qquad \text{(Schrödinger equation)}$$

---

## 4. The Fixed-Point Equation and the Ground State

The ground state satisfies the self-consistency condition:

$$v_0 = \hat{T} \cdot \hat{C}(v_0)$$

**Theorem 4.1 (Fixed-point = ground state — ✓ Theorem).** *The fixed-point equation v₀ = T̂·Ĉ(v₀) is equivalent to Ĥ|v₀⟩ = E₀|v₀⟩.*

*Proof.* From Stone's theorem: T̂ = e^{-iĤδt/ℏ} for a unique self-adjoint Ĥ. The fixed-point condition becomes:

$$e^{-i\hat{H}\delta t/\hbar}|v_0\rangle = |v_0\rangle$$

This holds if and only if |v₀⟩ is an eigenvector of e^{-iĤδt/ℏ} with eigenvalue 1, which occurs if and only if |v₀⟩ is an eigenvector of Ĥ with eigenvalue E₀ = nℏ/δt for integer n. Taking E₀ to be the minimum eigenvalue (ground state): Ĥ|v₀⟩ = E₀|v₀⟩. □

**Corollary 4.2.** *The Big Bang seed v₀ is the vacuum state of the derived Hamiltonian Ĥ.* The universe begins in the ground state of its own Hamiltonian — not from arbitrary initial conditions.

---

## 5. What the Hamiltonian Must Be

The Hamiltonian Ĥ is the generator of T̂ (from Stone's theorem). It must satisfy:

1. **Self-adjointness** (from unitarity of T̂): Ĥ = Ĥ†
2. **Symmetry invariance**: Ĥ must be invariant under the derived symmetry group (Paper 07)
3. **Renormalizability**: Ĥ contains only operators of mass dimension ≤ 4 (from the UV fixed-point requirement — at the Planck scale, the theory must be self-consistent)

**Theorem 5.1 (SM Lagrangian uniqueness — ∂ Derived).** *The most general renormalizable Lagrangian invariant under G = Poincaré × U(1) × SU(2) × SU(3) with the CPT-derived particle content is the Standard Model Lagrangian:*

$$\mathcal{L} = -\tfrac{1}{4}F^a_{\mu\nu}F^{a\mu\nu} + \bar{\psi}(i\gamma^\mu D_\mu)\psi + |D_\mu\phi|^2 - V(\phi) + \mathcal{L}_{Yukawa}$$

*Status: ∂ Derived.* This is a standard result in QFT (the uniqueness of the SM under these constraints is well-established). CPT provides the group G from orbit structure; the uniqueness theorem is external but rigorous.

---

## 6. Entropy Formula: Derivation

**Theorem 6.1 (Von Neumann entropy — ✓ Theorem).** *The von Neumann formula S = −Tr[ρ ln ρ] is the unique function of the density matrix ρ satisfying:*

| Property | Why it follows from CPT |
|----------|------------------------|
| Unitary invariance: S(UρU†) = S(ρ) | T̂ is unitary: physics is the same before/after evolution |
| Additivity: S(ρ_A ⊗ ρ_B) = S(ρ_A) + S(ρ_B) | Independent nodes share no information (disjoint c() paths) |
| Maximised at uniform distribution | Maximum uncertainty = no preferred propagation path |
| Continuous in ρ | c() is continuous (complex linear) |

These four properties uniquely determine S = −Tr[ρ ln ρ] [von Neumann 1932; Petz 1992]. The entropy formula is forced by the CPT structure, not borrowed from thermodynamics.

**Corollary 6.2 (Second Law — ✓ Theorem).** *S is non-decreasing.* Since resolution is irreversible (Axiom 2: once a configuration is resolved, it cannot be unresolved), entropy cannot decrease. □

---

## 7. Information Growth Law (∂ Derived)

The total structural information in the resolved universe grows as:

$$I(t) = I_0 \cdot \frac{a(t)}{a(0)}$$

where a(t) is the cosmological scale factor. The information amplification rate equals the Hubble parameter:

$$\lambda(t) = \frac{\dot{a}}{a} = H(t)$$

**Physical expansion = Information expansion.** The universe's spatial expansion and its information expansion are the same phenomenon — the resolution front propagating outward.

*Status: ∂ Derived.* The identification of the CPT resolution front with the cosmological scale factor uses the Hubble radius as the propagation horizon, which is the key assumption of Paper 02 (cosmological constant).

---

## 8. Boundary Structure and Quantum Tunneling

The Hubble horizon, event horizons, and Planck scale are **soft boundaries** of the CPT propagation network — not hard walls. The c() amplitude beyond a boundary q decays exponentially but never vanishes:

$$\alpha_{vv'} \propto e^{-\kappa|v'-q|} \quad \text{for } |v'| > q$$

This leakage mechanism is quantum tunneling — c() probabilistically propagating beyond the classically-forbidden boundary. Tunneling is not a separate phenomenon added to the theory; it is the natural behaviour of c() near any boundary.

The probability current (tunneling flux) satisfies the continuity equation derived from the Schrödinger equation:

$$\frac{\partial \rho}{\partial t} + \nabla \cdot J = 0, \qquad J_{leak} = \oint_q J \cdot dA$$

---

## 9. Conclusion

The CPT mathematical framework rests entirely on the two axioms. The Hilbert space structure follows from complex linearity. Unitarity of T̂ follows from bijectivity. The Schrödinger equation follows from Stone's theorem. The fixed-point equation is the ground-state equation. The Standard Model Lagrangian is the unique renormalizable Hamiltonian invariant under the derived gauge group. The entropy formula is forced by four algebraic properties of the propagation structure. At each step, we have identified which results are ✓ Theorems and which are ∂ Derived (using an established external result).

---

## References

[Petz 1992] D. Petz, Lett. Math. Phys. 24, 211 (1992). [Uniqueness of von Neumann entropy]  
[Stone 1932] M. H. Stone, Ann. Math. 33, 643 (1932).  
[von Neumann 1932] J. von Neumann, Mathematische Grundlagen der Quantenmechanik, Springer (1932).  
[Mani 2026a] E. Mani, "Configuration Propagation Theory: Framework" (Paper 01, this series).  
[Mani 2026b] E. Mani, "Physical Derivations from CPT" (Paper 07, this series).  
