# Low-cost edge-AI megalopa counter

One CPU Colab notebook reproduces manuscript figures, tables and statistical analyses from saved prediction and measurement records. It verifies 46 numerical tables. No training, model inference or compilation occurs.

[Public repository](https://github.com/AnawatBen/megalopa-counting-reproducibility) | [Open in Colab](https://colab.research.google.com/github/AnawatBen/megalopa-counting-reproducibility/blob/main/notebooks/Reproduce_Manuscript.ipynb)

Open the notebook using the Colab link above. No GitHub token is required for this public repository.

## Run in Colab

1. Click **Open in Colab** above and connect to a CPU runtime.
2. Keep **SOURCE_MODE = GitHub** and select **Runtime > Run all**.
3. Download the output ZIP and execution receipt when the run finishes.

The notebook downloads the source package from this public repository and records its exact commit. For offline source review, select Reviewer ZIP and upload all three source parts together when prompted. Full training datasets are not required.

## Contents

- notebooks: the single Colab entry point.
- reproduction: self-contained analysis package and dependencies.
- data/results: readable retained results.
- data/measurements: timing, power and cost records.
- data/figure_examples: selected illustrations, not full training datasets.
- docs: instructions and scope.

Private advisor documents, full literature texts and manuscript working files are excluded. Essential citations and integrity checks remain inside the package. Public meter images have no embedded EXIF metadata; the original measurement timestamps remain in structured records and originals are retained privately.

No open-source license is granted by this snapshot; rights remain with the respective owners.
