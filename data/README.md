# Equity Signal Evaluation

This repository contains offline research code for evaluating
cross-sectional equity signals under realistic constraints.

## Scope
- QuantConnect is used for data access and portfolio accounting
- All statistical inference and evaluation is performed offline
- Focus on robustness, regime dependence, and uncertainty

## Structure
- `data/raw`: immutable exports from QuantConnect
- `data/processed`: cleaned and aligned datasets
- `notebooks`: exploratory and evaluation notebooks
- `src`: reusable evaluation and bootstrap code
- `memo`: research memo and figures