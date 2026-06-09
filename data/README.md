# Datasets

This folder is intentionally empty. Notebooks that use real datasets include a download cell at the top that fetches the data automatically.

## Datasets Used in This Course

| Lecture | Dataset | Source | Download Method |
|---|---|---|---|
| L04 | Student Performance | UCI ML Repository | Auto-downloaded in notebook |
| L05 | Titanic Survival | OpenML | Auto-downloaded in notebook |
| L06 | Breast Cancer Wisconsin | Scikit-learn built-in | Loaded directly, no download |
| L07 | Mall Customer Segmentation | Synthetic (generated in notebook) | None required |
| L08 | Kenya Household Survey (simulated) | Synthetic based on KNBS structure | None required |
| L09 | Credit Card Fraud Detection | Synthetic imbalanced dataset | Generated in notebook |
| L10 | Mobile Money Transaction Network | Synthetic graph data | Generated in notebook |
| L11 | COVID-19 Africa Statistics | Our World in Data | Auto-downloaded in notebook |

## Generating Synthetic Data

Several notebooks generate their own synthetic datasets using `numpy` and `sklearn.datasets`. These datasets are designed to reflect realistic African business and social contexts while avoiding the need for external downloads.

## Adding Your Own Data

Place any additional datasets in this folder. Reference them in notebooks using relative paths:

```python
import pandas as pd
df = pd.read_csv('../data/your_dataset.csv')
```

---
*BITE 485 Data Science | Tharaka University | May–August 2026*
*kevin.tuei@tharaka.ac.ke*
