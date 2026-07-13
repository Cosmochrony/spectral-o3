This repository contains the source of the **O3** Cosmochrony paper  
*Projective Dynamics and Mass Hierarchy: Hierarchical Amplification via Growing Relational Valence*.

This work extends the **spectral relaxation programme** by addressing the
remaining limitation identified in O1: the insufficient amplitude of the
inter-generational mass hierarchy.

While **O1** restores the correct ordering of ADE levels through the geometric
mechanism of support contraction, it does not produce the observed large
mass ratios. The present work introduces the minimal dynamical ingredient
required to amplify this hierarchy.

The central idea is that the relational valence grows along the cascade
according to a structural law:

$p(n) \sim n^\beta$.

This induces a non-linear relation between spectral level position and
stabilisation rank, allowing small spectral differences to generate large
hierarchical separations.

# Core Result

The paper studies the **dynamic valence-growth regime**

$p(n) \to \infty$

with a power-law scaling

$p(n) \sim n^\beta$.

In this regime, the exit condition of a spectral level $\lambda_i$ is defined by

$\lambda_i = \lambda_+(p(n_{\mathrm{exit}}))$,

where $\lambda_+(p)$ is the upper edge of the Kesten--McKay support.

Solving this relation yields a strongly non-linear dependence of exit rank
on spectral position.

# Hierarchical Amplification

The key result is that the stabilisation ranks satisfy

$n_{\mathrm{exit}}(\lambda_i) \sim f(\lambda_i; \beta)$

with a rapidly increasing sensitivity to $\lambda_i$ as $\beta$ increases.

As a consequence:

- small differences between ADE eigenvalues
- are mapped to large separations in cascade depth
- which translate into exponentially large mass ratios

This provides a purely structural amplification mechanism.

# Mass Ratio Scaling

Under the power-law growth hypothesis, the ratio of stabilisation ranks becomes

$\frac{n_i}{n_j} \sim \left(\frac{\Delta_j}{\Delta_i}\right)^{1/\beta}$

where $\Delta_i = |\lambda_i - 1|$ measures the distance to the support midpoint.

This yields:

- weak hierarchy for small $\beta$
- strong hierarchy for larger $\beta$

A single structural parameter $\beta$ controls the entire hierarchy.

# Resolution of the Amplitude Problem

O3 resolves the main limitation of previous steps:

- **Spectral Relaxation (fixed valence)**  
  → correct structure, wrong ordering and amplitude

- **O1 (variable valence)**  
  → correct ordering, insufficient amplitude

- **O3 (dynamic valence growth)**  
  → correct ordering and scalable amplitude

Thus O3 closes the amplitude gap without introducing additional physics.

# Compatibility with Stratigraphy

The mechanism preserves the structural results of **Spectral Stratigraphy**:

- the number of levels (three) remains fixed
- the ADE eigenvalues remain unchanged
- only the mapping $\lambda \to n_{\mathrm{exit}}$ is modified

This confirms the separation of roles:

- topology → number of generations
- dynamics → mass hierarchy

# Regime Structure

The analysis identifies three regimes:

1. **Static regime (β ≈ 0)**  
   Fixed-valence behaviour, no hierarchy

2. **Intermediate regime**  
   Moderate amplification, insufficient for SM

3. **Dynamic regime (β > β\*)**  
   Strong amplification compatible with observed mass ratios

This defines a **regime diagram** controlled by β.

# What O3 Resolves

O3 provides:

- a structural amplification mechanism for mass ratios
- a single control parameter β
- a falsifiable prediction linking spectral data to hierarchy strength

It eliminates the need for:

- ad hoc scaling laws
- external calibration of masses
- additional dynamical assumptions

# Residual Open Problem

O3 introduces the parameter β but does not derive it from first principles.

The remaining task is:

- **Derivation of β from relational dynamics**

This corresponds to the next structural step in the programme.

# Conceptual Structure

O3 connects:

1. Spectral admissibility (mode selection)
2. Spectral stratigraphy (level structure)
3. Variable-valence dynamics (O1)
4. Non-linear mapping between spectrum and cascade rank
5. Emergence of hierarchical amplification

The result is a complete structural pipeline from spectrum to hierarchy.

# Physical Interpretation

In the Cosmochrony framework, the growth of relational valence reflects an
increase in effective connectivity of the substrate along the relaxation cascade.

This induces:

- contraction of spectral support (O1)
- non-linear exit dynamics (O3)
- amplification of stabilisation separations

Mass hierarchy is therefore not imposed but emerges from the geometry and
dynamics of the relational substrate.

# Open Directions

Three directions remain:

1. **Derivation of β**  
   From first-principles dynamics of the relaxation graph

2. **Extension to full Standard Model**  
   Including quarks and neutrinos

3. **Numerical validation**  
   Precise fitting of β against observed mass ratios

# Status

This framework is:

- spectral-dynamical
- structurally minimal
- analytically controlled
- falsifiable via β

It does not assume:

- particle fields
- free mass parameters
- external hierarchy inputs

# Repository Structure
```
paper/
├── out/ # Compiled O3 PDF
├── tex/ # LaTeX sources
└── README.md
```

# Citation

If you reference this work, please cite:

> J. Beau, *Projective Dynamics and Mass Hierarchy: Hierarchical Amplification via Growing Relational Valence*, Zenodo, 2026. :contentReference[oaicite:0]{index=0}

# Acknowledgements

Portions of the derivations, numerical exploration, and editorial refinement
benefited from iterative interactions with large language models used as
analytical assistants.  
All theoretical results and interpretations remain the sole responsibility
of the author.

# Contributions

This repository is intended as a research reference.

Critical feedback, independent numerical studies, and alternative derivations
of the β parameter are welcome.

Please open an issue to discuss conceptual points,
technical details, or possible extensions.
