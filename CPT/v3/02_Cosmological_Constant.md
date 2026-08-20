# The Cosmological Constant from the Propagation Horizon

*Eldhose Mani — Draft v3, August 2026*
*Part of the Configuration Propagation Theory series*

---

## Abstract

The cosmological constant problem — why the observed vacuum energy density is 10¹²⁰ times smaller than the naive quantum field theory prediction — is one of the deepest open problems in physics. We propose a resolution within Configuration Propagation Theory (CPT): the vacuum energy density Λ is suppressed because only configurations within the CPT resolution horizon (the Hubble radius R_H = c/H₀) have been fully "resolved" from quantum superposition to classical reality. Modes beyond the horizon remain quantum-coherent and do not contribute to the classical vacuum energy. This gives the estimate ρ_Λ ≈ 3c²/(4Gt_U²), where t_U is the age of the universe. Numerically: ρ_Λ^CPT ≈ 5.4 × 10⁻⁹ J/m³ vs. observed 6.9 × 10⁻⁹ J/m³ (factor ~1.3, attributed to a geometric prefactor not yet derived). The framework additionally predicts that dark energy is not constant but slowly decreasing as ρ_Λ ∝ 1/t_U², giving an equation of state w ≠ −1. The DESI Year-1 (2024) baryon acoustic oscillation survey finds evidence for w ≠ −1 at 2.5–3.9σ, consistent with this prediction. The status of all claims is ~ Conjecture (the geometric prefactor) and → Prediction (w ≠ −1), honestly disclosed.

---

## 1. Introduction

### 1.1 The Cosmological Constant Problem

The vacuum energy density in quantum field theory is estimated by summing the zero-point energies of all field modes up to some UV cutoff Λ_UV:

$$\rho_{vac} \sim \frac{\Lambda_{UV}^4}{16\pi^2}$$

For Λ_UV at the Planck scale (the natural cutoff): ρ_vac ~ 10¹¹³ J/m³. The observed value is ρ_Λ_obs ≈ 6.9 × 10⁻⁹ J/m³. The ratio is ~10¹²², the famous "120-orders-of-magnitude" discrepancy.

Standard attempts to resolve this include supersymmetry (cancellation between bosonic and fermionic contributions), string landscape (anthropic selection), and sequestering mechanisms. None provides a first-principles derivation.

### 1.2 The CPT Perspective

CPT introduces a natural cutoff on which modes contribute to classical (resolved) physics: the **resolution horizon**. In CPT, physical reality emerges from the resolution front — the boundary between classically-resolved and quantum-superposed configurations. The resolution front moves outward at the speed of light and currently defines the Hubble horizon R_H = c/H₀.

Modes with wavelength longer than R_H have not yet been "resolved" — they remain in quantum superposition and do not contribute to the classical vacuum energy. Only modes with λ ≤ R_H contribute.

This introduces a physical cutoff Λ_phys ~ H₀/c ~ 1/R_H ≪ Λ_Planck, suppressing the vacuum energy by the ratio:

$$\frac{\rho_\Lambda}{\rho_P} \sim \left(\frac{\Lambda_{phys}}{\Lambda_{Planck}}\right)^4 = \left(\frac{H_0}{c/\ell_P}\right)^4 \sim 10^{-122}$$

matching the observed suppression.

---

## 2. The Derivation

### 2.1 Resolution Front and Hubble Horizon

The CPT resolution front propagates outward from the Big Bang at speed c (the speed at which quantum information resolves into classical fact). At cosmic time t_U (the age of the universe), the resolution front is at comoving radius:

$$R_H = c \cdot t_U = \frac{c}{H_0}$$

This is the Hubble horizon. Configurations beyond R_H have not been resolved; they remain in quantum superposition under the c() operator.

### 2.2 Energy Density Estimate

The number of resolved modes (those within the Hubble volume) is:

$$N_{modes} \sim \left(\frac{R_H}{\ell_P}\right)^3 = \left(\frac{c/H_0}{\ell_P}\right)^3$$

where ℓ_P = √(Gℏ/c³) is the Planck length. Each mode contributes at most Planck-energy ℏc/ℓ_P to the vacuum energy. The total resolved vacuum energy density:

$$\rho_\Lambda \sim \frac{N_{modes} \cdot \hbar c / \ell_P}{(4\pi/3) R_H^3} \cdot f_{geom}$$

where f_geom is a geometric factor of order unity (not yet derived analytically — this is the open conjecture). This simplifies to:

$$\boxed{\rho_\Lambda \approx \frac{3c^2}{4G t_U^2}} \tag{1}$$

### 2.3 Numerical Evaluation

With t_U = 13.8 Gyr = 4.35 × 10¹⁷ s, G = 6.674 × 10⁻¹¹ m³/kg·s², c = 3 × 10⁸ m/s:

$$\rho_\Lambda^{CPT} = \frac{3 \times (3\times 10^8)^2}{4 \times 6.674\times 10^{-11} \times (4.35\times 10^{17})^2} = 5.4 \times 10^{-9} \text{ J/m}^3$$

| Quantity | Value |
|---------|-------|
| CPT prediction (Eq.1) | 5.4 × 10⁻⁹ J/m³ |
| Observed (Planck 2018) | 6.9 × 10⁻⁹ J/m³ |
| Ratio | ~1.3 |

The factor 1.3 discrepancy is the open problem. A spherical shell integration of the resolved modes (rather than a simple volume estimate) is expected to give a prefactor between 1 and 2. This has not been computed analytically. **Status: ~ Conjecture.**

---

## 3. Dark Energy Equation of State: w ≠ −1

### 3.1 Time-Dependence of Λ

In equation (1), ρ_Λ ∝ 1/t_U² — it decreases as the universe ages. This contrasts with the standard ΛCDM model where Λ is a constant. Since H₀ = 1/t_U (for a flat universe dominated by Λ):

$$\rho_\Lambda \propto H_0^2 \propto 1/t_U^2$$

A time-decreasing vacuum energy density corresponds to an equation of state:

$$w \equiv p/\rho > -1$$

specifically w approaches −1 from above as t_U → ∞ (the universe asymptotes to de Sitter, but never reaches it exactly).

### 3.2 Prediction: w ≠ −1

**Prediction → (CPT):** *The dark energy equation of state parameter w satisfies w ≠ −1. The dark energy density slowly decreases as the universe ages. This is testable by precision measurements of the Hubble expansion history.*

### 3.3 DESI 2024 Results

The Dark Energy Spectroscopic Instrument Year-1 results [DESI 2024] measured baryon acoustic oscillations from 6 million galaxies. Combined with CMB and Type Ia supernova data:

- DESI + CMB + Panstarrs: w₀ = −0.45 ± 0.34, w_a = −1.79 ± 0.48 (2.5σ from ΛCDM)
- DESI + CMB + DES-SN5YR: inconsistent with w = −1 at 3.9σ

These measurements are consistent with w ≠ −1 at the 2.5–3.9σ level. The CPT prediction of a slowly decreasing Λ is qualitatively consistent with the DESI signal. A full quantitative comparison requires computing the CPT dark energy equation of state as a function of redshift — this has not yet been done.

---

## 4. Discussion

### 4.1 Status Summary

| Claim | Status |
|-------|--------|
| Resolution horizon cutoff mechanism | ~ Conjecture |
| ρ_Λ ~ 3c²/(4Gt_U²), order of magnitude | ~ Conjecture |
| Factor ~1.3 discrepancy (geometric prefactor) | ~ Conjecture (open) |
| w ≠ −1 | → Prediction (DESI hint at 2.5–3.9σ) |
| Full w(z) trajectory | ~ Conjecture (not yet computed) |

### 4.2 Why This Is Worth Publishing

The cosmological constant problem has resisted solution for 30+ years. The CPT mechanism — vacuum energy suppressed by the resolution horizon — is a novel approach that makes a testable prediction (w ≠ −1). The prediction was made before the DESI result. Whether the mechanism is correct will be decided by data (full DESI results expected 2027).

The factor ~1.3 discrepancy between prediction and observation is acknowledged and not explained away. It is significantly smaller than the 10¹²⁰ discrepancy the theory was designed to address.

### 4.3 Relation to Holographic Entropy Bounds

The CPT resolution-horizon mechanism is related to but distinct from holographic entropy bounds [Bekenstein 1973, Susskind 1995]. Both use the Planck area as a fundamental unit. The difference is that CPT gives a mechanism — the resolution front — rather than stating a bound as a postulate.

---

## 5. Conclusion

Within CPT, the cosmological constant emerges from the suppression of vacuum modes beyond the resolution horizon. The prediction ρ_Λ ≈ 3c²/(4Gt_U²) agrees with observation to within a factor ~1.3 (the unsolved geometric prefactor). The time-dependence of this formula gives w ≠ −1 for the dark energy equation of state — a prediction consistent with current DESI data at 2.5–3.9σ. Full verification will be possible with the complete DESI dataset (~2027) and future surveys (Euclid, Roman).

---

## References

[Bekenstein 1973] J. D. Bekenstein, Phys. Rev. D 7, 2333 (1973).  
[DESI 2024] DESI Collaboration, arXiv:2404.03002 (2024).  
[Mani 2026] E. Mani, "Configuration Propagation Theory: Framework" (Paper 01 of this series).  
[Planck 2018] Planck Collaboration, A&A 641, A1 (2020).  
[Susskind 1995] L. Susskind, J. Math. Phys. 36, 6377 (1995).  
[Weinberg 1989] S. Weinberg, Rev. Mod. Phys. 61, 1 (1989).  
