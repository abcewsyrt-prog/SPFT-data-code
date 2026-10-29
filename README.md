# SPFT supporting data and code

Supporting materials for *Joint Preservation of Retrieval and Decay Statistics during Mamba-2 Adaptation*.

Download `ESM_1.zip` and extract it locally. The archive contains experiment and analysis code, configurations, per-example predictions, figure source data, model/tokenizer fingerprints, and the fixed controlled-model reference checkpoint. Full pretrained backbone weights and natural-language corpus text are not redistributed; the archive includes reconstruction scripts and source fingerprints.

## Privacy

The public archive excludes manuscript copies and author/contact information. Personal home-directory prefixes have been replaced with `/workspace`; adjust figure script paths to your local checkout before running. Scientific measurements and prediction records are preserved.

## Contents

- `backbone/`, `pilot/`: experiment implementations
- `results/`: experimental records and predictions
- `reproducibility/`: configurations, source snapshots, provenance and reconstruction metadata
- `paper/figures/`: plots and their source data
- `tools/`, `tests/`: analysis and verification scripts
- `checkpoints/`: controlled-model reference checkpoint

`MANIFEST.json` records SHA-256 hashes of the archived files. `SHA256SUMS.txt` records the archive hash.
