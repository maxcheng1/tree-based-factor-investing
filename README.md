# Tree-Based Machine Learning for Factor Investing

Implementation for ACTSC 423 / AFM 423 (University of Waterloo) — comparing
random forest and XGBoost against linear benchmarks for US equity factor
portfolios, with probability-scaled position sizing.

## Data access

This project uses CRSP/Compustat data via WRDS, which cannot be
redistributed. Researchers with WRDS access can reproduce the dataset
using the table names, variables, and date ranges documented below.

## Setup

Option A (conda):

1. `conda create -n factor-ml python=3.11 -y && conda activate factor-ml`
2. `pip install -r requirements.txt`

Option B (pip/venv):

1. `python -m venv .venv && source .venv/Scripts/activate`
2. `pip install -r requirements.txt`

## Reproducing results

`python scripts/run_pipeline.py` (details forthcoming)

## Paper

The accompanying report is in preparation and will be linked upon release.
