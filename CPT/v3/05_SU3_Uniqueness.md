# Orbit-Color Identification and the Uniqueness of SU(3) as the Colour Gauge Group

**A Proof from Configuration Propagation Theory**

*Eldhose Mani — Draft v2, August 2026*
*Companion to: "Why the Universe Has Exactly Three Generations of Matter"*

---

## Abstract

The Standard Model colour gauge group SU(3) is introduced as an empirical input: quarks come in three colours, and the non-abelian gauge group that describes their interactions is SU(3). No derivation from more fundamental principles exists within the Standard Model itself. In this paper we prove, within the Configuration Propagation Theory (CPT) framework, that SU(3) is the *unique* simple compact Lie group consistent with the CPT orbit structure. The argument has two stages. First, we prove the **orbit-colour identification**: the Z₃ discrete symmetry of the CPT period-3 fermionic orbit is gauge-consistent with the Z₃ centre of the colour group, identifying quark colour charge with orbit vertex position. Second, we apply the **Cartan classification** of simple Lie groups: among all simple compact Lie groups, exactly two have centre Z₃ — namely SU(3) and E₆. The period-3 orbit has exactly 3 vertices, requiring the colour group's fundamental representation to have dimension 3. SU(3) has fundamental dimension 3; E₆ has fundamental dimension 27. Therefore SU(3) is uniquely selected. The orbit-colour identification itself is classified as a structural axiom (∂ Derived), not derived from the two CPT axioms alone. The SU(3) uniqueness *given* this identification is a theorem.

---

## 1. Introduction

### 1.1 The Colour Gauge Group: An Empirical Input

Quantum chromodynamics [Fritzsch-Gell-Mann-Leutwyler 1973] describes the strong force between quarks as a non-abelian SU(3) gauge theory. The choice of SU(3) — rather than SU(4), SO(6), or any other group — is justified empirically: proton contains three quarks, not four; the ground state baryon is a colour singlet formed from three colour-antisymmetric quarks; the ratio R = σ(e⁺e⁻ → hadrons)/σ(e⁺e⁻ → μ⁺μ⁻) = 3Σq_f² implies three colours. All evidence points to SU(3) but none *derives* it.

Grand Unified Theory attempts [Georgi-Glashow 1974] embed SU(3) into larger groups such as SU(5), SO(10), or E₆. These provide partial explanations but introduce new assumptions (the GUT group, its breaking pattern).

### 1.2 CPT's Approach

CPT derives the gauge structure from the orbit structure of the propagation operator. Fermions are period-3 orbits; their Z₃ cyclic symmetry identifies with the Z₃ centre of the colour group. This identification, combined with the Cartan classification, uniquely selects SU(3).

The argument is not circular: it does not assume SU(3) and derive its properties. It assumes only:
1. Fermionic orbits are period-3 (follows from the N_g = 3 theorem in the companion paper)
2. Colour charge = orbit vertex label (the orbit-colour identification — a structural assumption)
3. The Cartan classification of simple Lie groups (pure mathematics)

### 1.3 Context: Why E₆ Appears

The Cartan classification produces an unexpected candidate: E₆, the exceptional Lie group, also has centre Z₃. Its appearance here is not a coincidence — E₆ is the gauge group of certain GUT models and appears naturally when embedding the Standard Model into a larger structure. We show why E₆ is excluded: its fundamental representation has dimension 27, not 3. If E₆ were the colour group, quarks would come in 27 colours, not 3. This contradicts both the orbit structure (3 vertices) and all experiments.

### 1.4 Organisation

Section 2 defines the orbit-colour identification and proves its gauge consistency. Section 3 presents the complete Cartan classification for groups with centre Z₃. Section 4 proves SU(3) uniqueness. Section 5 connects to the N_g = 3 proof. Section 6 discusses limitations and open problems.

---

## 2. The Orbit-Colour Identification

### 2.1 Setup: Period-3 Fermion Orbits

In CPT, quarks are stable period-3 orbits of the propagation operator $\hat{T}\hat{C}$. The orbit visits three states $\{v^{(0)}, v^{(1)}, v^{(2)}\}$ with Z₃ cyclic symmetry:

$$v^{(k)} \xrightarrow{\hat{T}\hat{C}} v^{(k+1 \bmod 3)}$$

This is not an assumption about the gauge structure — it follows from the existence of period-3 fixed-point solutions of the CPT ground-state equation.

### 2.2 Definition: Orbit-Colour Identification

**Definition 2.1.** *The colour charge of a quark in state $v^{(k)}$ is its orbit vertex label $k \in \{0,1,2\}$. Colour states (red, green, blue) correspond to $(k=0, k=1, k=2)$ respectively.*

This definition must be checked for gauge consistency: the colour assignment must be preserved under all gauge transformations of the derived gauge group $G_{SM} = U(1)\times SU(2)\times SU(3)$.

### 2.3 Gauge Consistency Theorem

**Theorem 2.2 (Orbit-Colour Consistency).** *The orbit-colour identification is gauge-consistent: the orbit Z₃ action commutes with all gauge transformations in $U(1)\times SU(2)\times SU(3)$.*

*Proof.*
- **U(1) hypercharge**: acts as a phase on quark fields, independent of colour index k. Commutes with the Z₃ orbit cycling. ✓
- **SU(2)_L**: acts on the SU(2) doublet structure of left-handed quarks, independent of colour index. Commutes with Z₃ cycling. ✓
- **SU(3)_C**: acts on the 3-dimensional colour representation. The Z₃ centre of SU(3) acts as $\psi_k \mapsto e^{2\pi ik/3}\psi_k$. The orbit Z₃ cycles $k \mapsto k+1$ (mod 3), which generates the same phase pattern on the colour wavefunction. Therefore the orbit Z₃ and the SU(3) centre Z₃ act identically on the colour space: they are the same group action. ✓

The orbit-colour identification is therefore gauge-consistent with the full derived gauge structure. □

**Remark.** Theorem 2.2 shows the identification is *consistent*, not that it is *forced* by the CPT axioms. It is possible, in principle, to have a CPT solution where colour charge is defined differently. This is why the orbit-colour identification is classified as **∂ Derived** (a structural assumption whose consistency is proved, but whose derivation from Axioms 1 and 2 alone remains open).

### 2.4 Corollary: Centre of Colour Group = Z₃

**Corollary 2.3.** *The centre of the colour gauge group has order 3 (i.e., it is Z₃).*

*Proof.* The orbit has period 3, so the orbit Z₃ has order 3. By Theorem 2.2, the orbit Z₃ is the centre of the colour group acting on the colour space. Therefore the colour group centre has order 3, i.e., it contains Z₃. Combined with the requirement that this is the *full* centre (from minimality of the orbit structure), the centre is exactly Z₃. □

---

## 3. The Cartan Classification

### 3.1 Complete Classification of Simple Lie Groups with Centre Z₃

The Cartan classification [Cartan 1894] of simple compact Lie groups is one of the great theorems of 19th-century mathematics. It gives a complete and exhaustive list:

- **Classical series**: $A_n = SU(n+1)$, $B_n = SO(2n+1)$, $C_n = Sp(2n)$, $D_n = SO(2n)$
- **Exceptional groups**: $G_2$, $F_4$, $E_6$, $E_7$, $E_8$

The centre of each classical series:
- $A_n = SU(n+1)$: centre $\mathbb{Z}_{n+1}$. Centre = Z₃ only for $n=2$, giving **SU(3)**.
- $B_n = SO(2n+1)$: centre $\mathbb{Z}_2$. No B_n has centre Z₃.
- $C_n = Sp(2n)$: centre $\mathbb{Z}_2$. No C_n has centre Z₃.
- $D_n = SO(2n)$: centre $\mathbb{Z}_2 \times \mathbb{Z}_2$ or $\mathbb{Z}_4$. No D_n has centre Z₃.

The centre of each exceptional group:
- $G_2$: trivial centre $\mathbb{Z}_1$.
- $F_4$: trivial centre $\mathbb{Z}_1$.
- **$E_6$: centre $\mathbb{Z}_3$.** ✓
- $E_7$: centre $\mathbb{Z}_2$.
- $E_8$: trivial centre $\mathbb{Z}_1$.

**Result**: The complete list of simple compact Lie groups with centre Z₃ is $\{SU(3),\, E_6\}$ — exactly two groups.

### 3.2 Fundamental Representation Dimensions

| Group | Lie type | dim G | Centre | Fund. dim | Notes |
|-------|----------|-------|--------|-----------|-------|
| SU(2) | A₁ | 3 | Z₂ | 2 | — |
| **SU(3)** | **A₂** | **8** | **Z₃** | **3** | **SELECTED** |
| SU(4) | A₃ | 15 | Z₄ | 4 | — |
| SU(5) | A₄ | 24 | Z₅ | 5 | GUT group |
| SO(5) | B₂ | 10 | Z₂ | 5 | — |
| G₂ | G₂ | 14 | Z₁ | 7 | — |
| F₄ | F₄ | 52 | Z₁ | 26 | — |
| **E₆** | **E₆** | **78** | **Z₃** | **27** | centre Z₃ but dim=27 ✗ |
| E₇ | E₇ | 133 | Z₂ | 56 | — |
| E₈ | E₈ | 248 | Z₁ | 248 | — |

---

## 4. SU(3) Uniqueness Theorem

### 4.1 The Fundamental Dimension Constraint

The orbit-colour identification requires: each orbit vertex ↔ one colour state. The period-3 orbit has exactly 3 vertices. Therefore the colour group's **fundamental representation must have dimension 3**.

### 4.2 Main Theorem

**Theorem 4.1 (SU(3) Uniqueness).** *Among all simple compact Lie groups, SU(3) is the unique group satisfying both:*
1. *Centre = Z₃ (to match the period-3 orbit Z₃ symmetry)*
2. *Fundamental representation dimension = 3 (to match the 3 orbit vertices)*

*Proof.*
From Section 3.1: groups with centre Z₃ are exactly $\{SU(3), E_6\}$.

Fundamental representation dimensions:
- SU(3): dimension = **3** ✓
- E₆: dimension = **27** ✗

E₆ is excluded because dim(fund. rep.) = 27 ≠ 3: a "quark" in an E₆ colour theory would come in 27 colour states, not 3. This contradicts the orbit structure (3 vertices) and is falsified by experiment.

SU(3) satisfies both constraints and is therefore the unique colour gauge group. □

### 4.3 Implication for the N_g = 3 Proof

**Corollary 4.2 (Upper bound via orbit-colour).** *$N_g \leq 3$.*

*Proof.* CPT derives that the colour group is SU(3) with centre Z₃ and fundamental dimension 3 (Theorem 4.1). Suppose $N_g = 4$. The generation orbit would have period 4 with Z₄ symmetry. By Corollary 2.3, the colour group's centre would need to be Z₄. But SU(3) has centre Z₃, not Z₄. Contradiction. Therefore $N_g \leq 3$. □

*Note:* The companion paper gives an independent proof of $N_g \leq 3$ via Higgs vacuum stability that does not use the orbit-colour identification. Corollary 4.2 provides an additional, algebraic pathway.

---

## 5. Discussion

### 5.1 The Role of E₆

The appearance of E₆ in the Cartan classification for centre Z₃ is physically significant. E₆ is:
- The gauge group of the Heterotic string compactification [Candelas et al. 1985]
- A candidate GUT group in some supersymmetric models
- Compatible with quark confinement (non-trivial centre)

However, E₆ requires 27-dimensional colour representations. This is inconsistent with the 3-vertex orbit structure and with the empirical fact that quarks come in 3 colours. The Cartan-based argument turns the empirical 3-colour observation into a *theoretical selection criterion*.

### 5.2 N_colours = 3 Without SU(5) Assumptions

A remarkable feature of Theorem 4.1 is that it derives $N_{colours} = 3$ without assuming a GUT embedding. The argument uses only:
1. The period-3 orbit structure (from CPT)
2. The orbit-colour identification (structural assumption)
3. The Cartan classification (pure mathematics)

No SU(5), SO(10), or E₈ grand unified theory is needed. The 3-colour structure is forced purely by the orbit period and the exhaustive list of Lie groups.

### 5.3 The Orbit-Colour Identification: Status

As stated in Theorem 2.2, the orbit-colour identification is shown to be gauge-*consistent*, not gauge-*forced*. The gap is:

**Open Problem:** Derive the orbit-colour identification — colour charge = orbit vertex label — from CPT Axiom 1 (c() complex-linear) and Axiom 2 (t() bijective) alone, without additional structural assumptions.

Until this is resolved, the SU(3) uniqueness result is classified as **∂ Derived** (proven given the identification as input) rather than a pure **Theorem**.

---

## 6. Conclusion

We have established two results:

1. **Orbit-colour consistency** (Theorem 2.2): The identification of quark colour charge with orbit vertex position is gauge-consistent. The orbit Z₃ cycling and the SU(3) centre Z₃ are the same group action on colour space.

2. **SU(3) uniqueness** (Theorem 4.1): Among all simple compact Lie groups with centre Z₃, only SU(3) has a 3-dimensional fundamental representation. E₆ — the only other candidate from the Cartan classification — has fundamental dimension 27, incompatible with a 3-vertex orbit.

Together, these results provide a theoretical derivation of the colour gauge group SU(3) that does not rely on empirical measurements of the number of colours, but instead reduces it to the mathematical structure of period-3 orbits and the exhaustive Cartan classification.

The main limitation is that the orbit-colour identification itself is a structural assumption, not yet derived from the CPT axioms. Closing this gap would elevate the SU(3) uniqueness result from ∂ Derived to a pure Theorem.

---

## Appendix: The Cartan Classification — Complete Centre Data

The classification of simple compact Lie groups and their centres is a standard result in Lie theory. For completeness:

| Infinite family | Centre | Comment |
|----------------|--------|---------|
| $SU(n) = A_{n-1}$ | $\mathbb{Z}_n$ | Centre = Z₃ only for n=3 |
| $SO(2n+1) = B_n$ | $\mathbb{Z}_2$ | Never Z₃ |
| $Sp(2n) = C_n$ | $\mathbb{Z}_2$ | Never Z₃ |
| $SO(2n) = D_n$ | $\mathbb{Z}_2 \times \mathbb{Z}_2$ (n>2) or $\mathbb{Z}_4$ (n=2) | Never Z₃ |

| Exceptional group | Centre |
|------------------|--------|
| $G_2$ | $\{1\}$ |
| $F_4$ | $\{1\}$ |
| $E_6$ | $\mathbb{Z}_3$ |
| $E_7$ | $\mathbb{Z}_2$ |
| $E_8$ | $\{1\}$ |

The complete list of simple compact Lie groups with centre containing Z₃ is therefore $\{SU(3k) : k \geq 1\} \cup \{E_6\}$. Among these, only $SU(3)$ has a 3-dimensional fundamental representation.

---

## References

[Candelas et al. 1985] P. Candelas, G. Horowitz, A. Strominger, E. Witten, Nucl. Phys. B 258, 46 (1985).  
[Cartan 1894] É. Cartan, Sur la structure des groupes de transformations finis et continus, Paris (1894).  
[Fritzsch-Gell-Mann-Leutwyler 1973] H. Fritzsch, M. Gell-Mann, H. Leutwyler, Phys. Lett. B 47, 365 (1973).  
[Georgi-Glashow 1974] H. Georgi, S.L. Glashow, Phys. Rev. Lett. 32, 438 (1974).  
[Mani 2025] E. Mani, "Configuration Propagation Theory: Framework and Derivations."  
[Mani 2025a] E. Mani, "Why the Universe Has Exactly Three Generations of Matter" (companion paper).  
[PDG 2023] R. L. Workman et al. (Particle Data Group), Prog. Theor. Exp. Phys. 2022, 083C01.  
[Slansky 1981] R. Slansky, Phys. Rep. 79, 1 (1981). [Group theory for unified model building]  
