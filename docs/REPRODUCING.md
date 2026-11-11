# Reproduction instructions

1. Open `notebooks/Reproduce_Manuscript.ipynb` in Google Colab with a CPU runtime.
2. Keep GitHub mode to load the public source automatically. Alternatively, select Reviewer ZIP and upload all three `reproduction/Phase1_Manuscript_Reproduction_Source.zip.part*` files together.
3. Run all cells. The notebook checks the source archive and manifest, installs pinned dependencies in an isolated environment, and rebuilds the publication outputs.
4. Download and retain the final output ZIP and execution receipt.

GitHub mode downloads the source ZIP from `reproduction/` at an exact commit. No access token is required for this public repository.

The package contains all code and frozen inputs needed for this saved-evidence reproduction. Extract it to inspect the assembly and statistics modules. For local execution, use its requirements in an isolated environment, set MPLBACKEND=Agg, and run its run_all.py. A local run is not a Colab execution.

The package's `statistics/references` directory contains expected numerical CSV outputs used for validation, not literature PDFs. Its manifests are required to detect unintended input changes. The package is a privacy-cleaned derivative of verified v21, with new checksums and unchanged analytical values. REPOSITORY is set to `AnawatBen/megalopa-counting-reproducibility`; GitHub mode records the exact source commit.

Full retraining or new inference requires additional datasets/model artifacts outside this repository. The visible data folders provide readable convenience copies; the notebook uses the source ZIP as its authoritative input.

[Repository](https://github.com/AnawatBen/megalopa-counting-reproducibility) | [Open in Colab](https://colab.research.google.com/github/AnawatBen/megalopa-counting-reproducibility/blob/main/notebooks/Reproduce_Manuscript.ipynb)
