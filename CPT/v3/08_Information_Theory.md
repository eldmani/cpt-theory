# Information Theory and the Universe as a Compressed Program

*Eldhose Mani — Draft v3, August 2026*
*Part of the Configuration Propagation Theory series*

---

## Abstract

We examine the information-theoretic structure of Configuration Propagation Theory (CPT). The universe, under CPT, is a running program: a small compressed seed executing two simple rules that generate exponentially expanding explicit information. Three quantities evolve independently: (1) information per node decreases as the universe expands (dilution); (2) total structural information increases proportionally to the cosmological scale factor a(t); (3) Kolmogorov complexity of the rules is constant — the program never changes. These are not contradictions; they operate at different levels of description. We show that the information amplification rate equals the Hubble parameter: λ(t) = H(t). Physical expansion and information expansion are the same phenomenon. The Hubble horizon, event horizons, and the Planck scale are all instances of a single mechanism — soft boundaries beyond which c() amplitude decays exponentially but never vanishes. This is quantum tunneling at the atomic scale, Hawking radiation at the black hole scale, and cosmological horizon leakage at the cosmic scale. All are the same mathematical object. We also discuss information conservation globally (total information = constant when the full configuration space is considered, not just our observable region), the seeding of new universes via accumulated horizon leakage, and the information-theoretic meaning of the heat death of the universe.

---

## 1. Introduction: The Universe as a Running Program

DNA does not contain a human being. It contains a compressed set of rules that, when executed, generate a human being. The genome encodes the program; the organism is the output of running that program.

The CPT framework makes an analogous claim about the universe: the Big Bang seed v₀ does not contain the current universe. It contains two rules (c and t) that, when executed, generate the universe. The universe we observe is the decompression of an ancient, compact program.

This is not a metaphor. It is a mathematical statement about Kolmogorov complexity, information content, and the relationship between a generative rule and its output.

---

## 2. Three Distinct Information Quantities

Consider a simple generative rule f(x) = x² applied to seed x₀ = 2:

| Step | Value | Bits to describe |
|------|-------|-----------------|
| n=0 | 2 | 1 bit |
| n=1 | 4 | 2 bits |
| n=2 | 16 | 4 bits |
| n=3 | 256 | 8 bits |
| n | x₀^(2ⁿ) | 2ⁿ bits |

The information required to describe the state grows exponentially. Yet the seed x₀=2 and the rule f(x)=x² are unchanged — their combined description requires a constant number of bits: K(seed) + K(rule).

This illustrates the three distinct information quantities in CPT:

### 2.1 Information Per Node: Decreasing

Each individual node in the propagation network carries a share of the original seed information. As the network expands, this share dilutes:

$$i(t) = \frac{I_0}{N(t)} \propto \frac{1}{a(t)^3}$$

where N(t) is the number of resolved nodes and a(t) is the scale factor. Individual nodes become less informative as the universe expands.

### 2.2 Total Structural Information: Increasing

The total information in all resolved nodes grows with the network:

$$I(t) = N(t) \cdot i(t) = I_0 \cdot \frac{a(t)}{a(0)}$$

**Total information grows proportionally to the scale factor.** Each propagation step makes implicit information (encoded in the rules) explicit (encoded in new configurations).

### 2.3 Kolmogorov Complexity of the Rules: Constant

The description of the complete universe at any time t requires only:

$$K(\text{universe at }t) \approx K(\text{seed}) + K(t)$$

The first term is the Kolmogorov complexity of the seed v₀ — a fixed, finite number. The second term is the description of the current time step — logarithmic in t. The total grows at most logarithmically. The universe looks increasingly complex as it evolves, but it has always been fully described by the seed plus a step counter.

---

## 3. Information Amplification Rate = Hubble Parameter

**Theorem 3.1 (Information-expansion identity — ∂ Derived).** *The information amplification rate λ(t) equals the Hubble parameter H(t):*

$$\lambda(t) = \frac{\dot{I}}{I} = \frac{\dot{a}}{a} = H(t)$$

*Proof sketch.* From §2.2: I(t) ∝ a(t). Differentiating: dI/dt = I₀·ȧ/a(0). The amplification rate λ = (dI/dt)/I = ȧ/a = H(t). □

**Physical interpretation.** The Hubble constant H₀ ≈ 67.4 km/s/Mpc is simultaneously:
1. The rate at which galaxies recede from each other (cosmological expansion)
2. The rate at which the resolution front expands (CPT propagation)
3. The rate at which new explicit information is generated (information expansion)

These are the same phenomenon described at different levels of abstraction.

**Status: ∂ Derived.** The identification of CPT information growth with cosmological expansion uses the resolution-horizon = Hubble-horizon identification from Paper 02. This is consistent but not proved from the two axioms alone.

---

## 4. The Soft Boundary and Universal Tunneling

### 4.1 What Is a Boundary?

The Hubble horizon (R_H = c/H₀), black hole event horizons, and the Planck scale are all instances of a **soft boundary** q — a surface beyond which c() amplitude decays exponentially but never reaches zero:

$$\alpha_{vv'} \propto e^{-\kappa|v'-q|} \quad \text{for } |v'| > q, \quad \kappa > 0$$

This is not a hard wall. c() always has non-zero amplitude for configurations beyond q. The boundary is only a suppressor, not a barrier.

### 4.2 Quantum Tunneling as the Universal Mechanism

The exponential decay of c() amplitude beyond q is exactly the WKB tunneling formula for quantum mechanics:

$$P(\text{tunnel}) \propto e^{-2\int_{\text{classically forbidden}} \kappa(x)\,dx}$$

This means **quantum tunneling, radioactive decay, Hawking radiation, and cosmological horizon leakage are all the same mathematical mechanism** — c() leakage through a soft boundary — occurring at different scales with different boundary types:

| Scale | Playing field | Boundary q | CPT leakage | Observed effect |
|-------|--------------|------------|-------------|-----------------|
| Atomic | Classical region | Potential barrier | c() through barrier | Quantum tunneling |
| Nuclear | Nucleus | Coulomb barrier | c() through Coulomb | Alpha decay |
| Black hole | Exterior | Event horizon | c() inward | Hawking radiation |
| Cosmic | Observable universe | Hubble horizon | c() beyond R_H | Dark energy inflow |

The universality of this mechanism across 40 orders of magnitude in scale is a prediction of CPT, not a coincidence.

### 4.3 Information Recovery

For black holes: the information that falls into a black hole is not lost — it is c()-propagated beyond the event horizon. Since t() is globally bijective (Axiom 2), this information is globally conserved. Hawking radiation is the gradual recovery of this information via c() tunneling back through the horizon. The **black hole information paradox is resolved**: information is never destroyed; it leaks back via the same c() mechanism that caused it to appear lost in the first place.

---

## 5. Information Conservation and Global Accounting

Within the observable universe (our "playing field"), information appears to leak out through horizons. This is an artifact of treating a finite region as a closed system. Globally:

$$I_{\text{total}} = I_{\text{inside}}(t) + I_{\text{accumulated, outside}}(t) = \text{constant}$$

This follows directly from Axiom 2: t() is globally bijective, so no information is created or destroyed anywhere in the full configuration space. Conservation holds exactly.

The "leakage" we observe is a redistribution, not a loss.

---

## 6. The Heat Death of the Universe

Standard cosmology: at heat death, all free energy is exhausted, no work can be done, the universe reaches maximum entropy and stays there indefinitely.

CPT reinterpretation: heat death is the moment when the universe is **most expanded** — when a(t) is largest and total resolved information I(t) is greatest. The rules c() and t() are still running. The generation of new configurations continues. The program has not terminated.

More precisely: heat death corresponds to maximum entropy *within the resolved region*. Beyond the Hubble horizon, the unresolved configurations continue to be propagated by c(). The program is still running; only our observable window has reached apparent equilibrium.

This is consistent with CPT's prediction of a time-varying cosmological constant: as t_U → ∞, ρ_Λ ∝ 1/t_U² → 0 — the universe asymptotes to flat spacetime (de Sitter) but never exactly reaches it.

---

## 7. Seeding New Universes (~ Conjecture)

When accumulated leaked information beyond the Hubble horizon reaches a critical threshold, the CPT framework suggests a new seed may crystallise from the accumulated configurations. This would be a "daughter universe" — a new v₀' arising from the accumulated c() propagations beyond our horizon.

This is analogous to how the CPT universe itself began: a seed configuration that became self-consistent under its own rules. If the rules (c and t) are universal, any accumulated configuration beyond a horizon could in principle form a new fixed point.

**Status: ~ Conjecture.** The conditions for daughter universe formation are not derived from the axioms; this is speculative extrapolation. It is included here because it is a natural implication of the framework, transparently labelled.

---

## 8. Conclusion

CPT provides a precise information-theoretic picture of the universe: a compressed program executing two rules, generating exponentially expanding explicit information. Physical expansion = information expansion (the same phenomenon). All boundaries are soft — quantum tunneling, Hawking radiation, and dark energy are the same c()-leakage mechanism at different scales. Information is globally conserved. The universe has always been fully described by the seed; we are watching its decompression. The heat death is not an ending but the maximum-information-density state of the resolved region, while the program continues beyond the horizon.

---

## References

[Bekenstein 1973] J. D. Bekenstein, Phys. Rev. D 7, 2333 (1973).  
[Hawking 1974] S. W. Hawking, Nature 248, 30 (1974).  
[Kolmogorov 1963] A. N. Kolmogorov, Probl. Inform. Transm. 1, 1 (1965).  
[Mani 2026a] E. Mani, "Configuration Propagation Theory: Framework" (Paper 01, this series).  
[Mani 2026b] E. Mani, "The Cosmological Constant from the Propagation Horizon" (Paper 02, this series).  
[Penrose 2004] R. Penrose, The Road to Reality, Jonathan Cape (2004).  
[Susskind 1995] L. Susskind, J. Math. Phys. 36, 6377 (1995).  
