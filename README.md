# Monte Carlo Calibrated Measurement Contexts - Package 2

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17325811.svg)](https://doi.org/10.5281/zenodo.17325811)

**Full Resolution of Hubble Tension through Empirical Tensor Calibration**

## Quick Start

```bash
# Install dependencies
pip install -r code/requirements.txt

# Generate all data (already generated - for reference)
# python generate_all_data.py

# View results
python -c "import json; print(json.dumps(json.load(open('validation_results/final_merged_interval.json')), indent=2))"
```

## Package Contents

- `mcmc_chains/` - Synthetic MCMC posteriors (4 files)
- `tensor_evolution/` - Iterative refinement (7 files: 6 iterations + convergence trace)
- `validation_results/` - Concordance validation (5 files)
- `code/` - Python implementation (4 scripts + requirements)
- `docs/` - Documentation (LaTeX preprint + methodology)
- `checksums/` - SHA-256 integrity verification

## Key Results

**Package 1 → Package 2 Improvement:**
- Δ_T: 1.003 → 1.287 (+28.3%)
- Gap: 0.48 → 0.00 km/s/Mpc (-100%)
- Resolution: 91% → 100% (Complete)

**Mathematical Framework:** Unchanged. Only tensor precision improved.

## Contact

Eric D. Martin
eric.martin1@wsu.edu
Washington State University, Vancouver

## License

- Code: MIT
- Data: CC-BY-4.0
