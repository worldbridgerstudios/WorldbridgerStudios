# HoloCell

**A single eigenvalue generates five fundamental physics constants.**

---

## The Discovery

The 16th triangular number, **T(16) = 136**, serves as a unified eigenvalue from which five fundamental physics constants emerge with extraordinary precision.

### Results

| Constant | HoloCell Expression | Error |
|----------|---------------------|-------|
| Proton-electron mass ratio | 3-term Bloch ball | **1.21 × 10⁻⁷%** |
| Rydberg constant | — | 1.02 × 10⁻⁵% |
| Fine structure constant α⁻¹ ≈ 137 | T(16) + 1 | 1.35 × 10⁻⁵% |
| Muon-electron mass ratio | — | 1.40 × 10⁻⁵% |
| Weinberg angle | — | 4.67 × 10⁻⁴% |

The fine structure constant emerges as **α⁻¹ ≈ 137 = T(16) + 1** — the "plus one" of the bilateral covenant.

---

## Installation

```bash
pip install holocell
```

[:material-package: View on PyPI](https://pypi.org/project/holocell/){ .md-button }

---

## Quick Start

```python
from holocell import HoloCell

# Initialize
hc = HoloCell()

# Get all constants
results = hc.evaluate_all()
for name, data in results.items():
    print(f"{name}: {data['error_percent']:.2e}% error")
```

---

## Architecture

### Terminal Set
- **T(16) = 136** — the eigenvalue
- Architectural integers: 1, 7, 9, 11, 16, 28, 36, 44, 60, 66, 666
- Transcendentals: π, φ, e

### Operators
- **T(n)** — Triangular number function
- **B(x) = x + 1** — Bilateral covenant
- **S(x)** — Six-nine breath operator

### Trinity Extension
**T(16) × 3 = 408** appears at multiple scales:

- Cosmic: Matter density 4.08 × 10⁻²⁸ kg/m³
- Atomic: Gold lattice constant 4.08 Å
- Wave: 4.08 m wavelength

Scale-invariant holographic structure.

---

## Papers

- [**HoloCell: A Triangular Number Eigenvalue**](https://zenodo.org/records/18173219) — Main paper
- [**HoloCell: Methods of the Magi**](https://zenodo.org/records/18186026) — Methodology
- [**HoloCell: Coherence Networks**](https://zenodo.org/records/18186163) — Network analysis

---

## Source Code

[:material-github: GitHub Repository](https://github.com/worldbridgerstudios/holocell){ .md-button }
