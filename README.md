# Introduction to Probability (PhD ECFIN) – Problem Sets (A.Y. 2025/2026)

This repository contains my personal submissions for the course problem sets.

## Structure
- `PS1.ipynb`, `PS2.ipynb`, ... : Jupyter notebooks (final submitted versions).
- (Possibly) auxiliary LaTeX or derivation files: `derivation_ps1.tex` etc.
- `environment.yml`: Reproducible Python environment (see below).

## Environment
```bash
mamba env create -f environment.yml   # or: conda env create -f environment.yml
conda activate prob-ps
jupyter lab
```

## Reproducibility Notes
Each notebook attempts to:
- Use a fixed random seed (see top cell).
- Run cleanly from top to bottom (`Kernel > Restart & Run All`) before tagging a final version.

## Version Tags
After finalizing a submission:
```bash
git tag -a ps1-final -m "Final version PS1 (submitted 2025-10-04)"
git push --tags
```

## Academic Integrity
These materials represent my own work for grading purposes. Redistribution of full solutions before course completion is discouraged.

## License
(Undecided) — intentionally omitted to avoid inadvertent reuse during the active academic year.
