# Discreteness from Identifiability

**Why continuous physics produces integers: observation maps carry integer-valued invariants that can change only discretely.**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Overview

Discrete phenomena pervade physics: quantum numbers, particle species, phase transitions, symbolic codes. Yet the underlying state spaces are continuous. We identify a unifying mechanism: observation maps carry integer-valued invariants (rank, dimension, index) that can change only discretely.

The key invariant is the **identifiable dimension** (rank of the observation differential), which controls how many effective degrees of freedom are accessible. When this rank changes, qualitative transitions occur.

**Core claim:** Discreteness is not fundamental; identifiability is.

## The Dimensional Gradient Theorem

The paper proves that any useful observer requires:

$$0 < \mathrm{rank}(dh) < \dim X$$

where $h: X \to \mathcal{S}$ is the observation map from environment to representation.

**Proof sketch:**
- **Rank > 0**: If rank = 0, the representation carries no information. No prediction or control is possible.
- **Rank < dim X**: If rank = dim X, every microstate maps to a unique representation. No compression, no noise tolerance, no generalization.

This is the **minimal anthropic condition**: not carbon, not water, not specific constants—just a gap between environment complexity and representation complexity.

## What This Paper Claims (and Does NOT Claim)

**What we claim:**
- Observation maps carry integer-valued invariants (rank, dimension, index)
- Discrete transitions correspond to discrete changes in these invariants
- Dimensional gradients are *necessary* for observation (proven)

**What we do NOT claim:**
- Quotients automatically produce discrete equivalence classes (they don't - see Section 2.3)
- Continuous spectra don't exist (they do - see Section 4.2)
- Dimensional gradients are *sufficient* for observers (necessity ≠ sufficiency)

## Key Results

- **Integer invariants**: Observation maps carry rank, dimension, index — all integers
- **Dimensional Gradient Theorem**: Proves 0 < rank < dim X for any useful observer
- **Worked example**: Gaussian sum shows rank jump under coupling activation
- **Cross-domain unification**: Same structure in Fisher rank, quantum degeneracies, symbol alphabets

## Paper

**Discreteness from Identifiability: Why Continuous Physics Produces Integers**

Todd, I. (2026). *IPI Letters* (in preparation).

Part of the IPI Letters program:
- [Thermodynamic Foundation](https://github.com/todd866/infodynamics-foundation) — microscopic thermodynamics
- [Black Hole Aperture](https://github.com/todd866/black-hole-aperture) — observer-relative time dilation
- [Cosmic Relaxation](https://github.com/todd866/cosmic-relaxation) — cosmological origins

## Citation

```bibtex
@article{todd2026discreteness,
  author  = {Todd, Ian},
  title   = {Discreteness from Identifiability: Why Continuous Physics Produces Integers},
  journal = {IPI Letters},
  year    = {2026},
  note    = {In preparation}
}
```

## License

MIT License
