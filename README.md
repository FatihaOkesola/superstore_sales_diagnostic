# Superstore Sales Performance Diagnostic

## Overview

Built to practice diagnostic analytics and scenario modelling on a real business problem. This project evaluates regional and product-level profitability using the Superstore dataset, identifies drivers of margin erosion, and estimates the impact of a targeted pricing intervention.

## Key Findings

- Overall profit margin: **12.47%** (stable at company level)
- **Regional margin dispersion**: Central underperforms vs peers
- **Category imbalance**: Furniture contributes ~32% of revenue but ~6% of profit (margin-dilutive)
- **Loss concentration**: Tables losses are disproportionately concentrated in the East region
- **Scenario impact**: Reducing East Tables discount from 37.4% to 25% reduces losses by ~ 73% (~ $8.1K improvement)

## Deliverables

- `Superstore Sales project.ipynb` — Full analysis (cleaning, benchmarking, diagnostics, scenario modeling)
- `Superstore_Sales_Performance_Diagnostic.pdf` — Executive slide deck (no code)
- Charts exported from the notebook and embedded in the slide deck

## Tools Used

Python · pandas · matplotlib

## How to Run

```bash
pip install pandas matplotlib
jupyter notebook "Superstore Sales project.ipynb"
```

## Dataset

[Superstore Sales Dataset — Kaggle](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)

## Notes / Assumptions

This dataset is public and not tied to a specific company. Insights are interpreted as directional and based on the assumptions stated in the notebook.
