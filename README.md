
# AIMEX

**Active Inference on Multimodal Explainable Knowledge Graphs for Rare Disease Discovery**



## Overview
AIMEX is a framework integrating multimodal biomedical knowledge graph
encoding with a curiosity-driven Active Inference agent for explainable
rare disease discovery.

## Requirements
Python 3.10, PyTorch 2.0, PyTorch Geometric 2.3

    pip install -r requirements.txt

## Reproduction
Run the complete pipeline (all 18 figures):

    python kg_mmvgae_complete.py

For a fast test (1 seed, ~30 min):
Set QUICK_MODE = True on line ~155 of kg_mmvgae_complete.py

## Data
Monarch Initiative KG v2024-07-12:
https://monarch-initiative.org (downloaded automatically on first run)

## Citation

If you use AIMEX in your research, please cite:

```bibtex
@software{obite2025aimex,
  author    = {Obite, Felix},
  title     = {AIMEX: Active Inference on Multimodal Explainable
               Knowledge Graphs for Rare Disease Discovery},
  year      = {2025},
  url       = {https://github.com/Felix-Obite/AIMEX},
  note      = {Manuscript under review}
}
```

> **Note:** A journal publication is forthcoming. This page will be
> updated with the full citation upon acceptance.
