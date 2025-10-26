# Notebooks Playground

Personal sandbox for rebuilding classic algorithms, exploring datasets, and sharing concise learning notes. Each subfolder contains either a standalone script or a Jupyter notebook that documents the experiment from data prep to evaluation.

## What You Will Find
- **notebooks/** – interactive explorations (e.g., perceptron from scratch, PCA intuition).
- **datasets/** – small, open datasets kept alongside experiments for reproducibility.
- **pyproject.toml** – dependency and tooling metadata for reproducible environments.

Expect lightweight implementations with clear commentary, comparisons against baseline models, and incremental refactors as I iterate on ideas.

## Getting Started
1. Create and activate a Python 3.11+ virtual environment (e.g., `uv venv && source .venv/bin/activate`).
2. Install dependencies: `uv pip install -e .` (editable install keeps notebooks aligned with the latest utilities).
3. Launch Jupyter Lab or VS Code notebooks to run the explorations.

> Tip: The notebooks are written to be rerun end-to-end; they avoid hidden state and set random seeds where relevant.

## Sharing & Contributions
This repository primarily supports my learning journey, but feedback is welcome via GitHub issues or pull requests. If you re-run or extend an experiment, mention the original notebook and describe the change so others can follow along.

Happy experimenting!
