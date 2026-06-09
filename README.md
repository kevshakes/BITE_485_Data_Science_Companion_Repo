# BITE 485 — Data Science
## Tharaka University | Department of Computer Science and ICT
### May–August 2026

![Python](https://img.shields.io/badge/Python-3.11-blue)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![License](https://img.shields.io/badge/License-Academic-green)

---

## About This Repository

This is the official companion repository for **BITE 485: Data Science**, a fourth-year undergraduate course in the Bachelor of Science in Information Technology programme at Tharaka University.

The repository contains **11 Jupyter notebooks**, one per lecture, with fully annotated, runnable Python code covering every topic in the course. Each notebook mirrors the lecture notes and includes:

- Concept explanations in Markdown
- Runnable code examples using real and synthetic datasets
- Visualisations with Matplotlib and Seaborn
- End-of-notebook exercises for self-assessment

**Lecturer:** K. Tuei | kevin.tuei@tharaka.ac.ke | 0712 838 653

---

## Course Structure

| # | Notebook | Topics Covered |
|---|---|---|
| 01 | [Introduction to Data Science](notebooks/L01_Introduction_to_Data_Science.ipynb) | Data science workflow, Python ecosystem, problem types |
| 02 | [Statistical Inference](notebooks/L02_Statistical_Inference.ipynb) | Distributions, hypothesis testing, confidence intervals |
| 03 | [Statistical Modelling](notebooks/L03_Statistical_Modelling.ipynb) | Linear regression, logistic regression, model assumptions |
| 04 | [Exploratory Data Analysis](notebooks/L04_Exploratory_Data_Analysis.ipynb) | EDA workflow, missing values, outliers, correlation |
| 05 | [Machine Learning Fundamentals](notebooks/L05_Machine_Learning_Fundamentals.ipynb) | Bias-variance, overfitting, cross-validation, regularisation |
| 06 | [Classification Algorithms](notebooks/L06_Classification_Algorithms.ipynb) | Decision trees, Naive Bayes, KNN, Random Forest, XGBoost |
| 07 | [Regression and Clustering](notebooks/L07_Regression_and_Clustering.ipynb) | Advanced regression, K-Means, hierarchical clustering |
| 08 | [Feature Engineering](notebooks/L08_Feature_Engineering.ipynb) | Transformations, encoding, scaling, feature selection |
| 09 | [Model Evaluation and Selection](notebooks/L09_Model_Evaluation_and_Selection.ipynb) | Confusion matrix, AUC-ROC, class imbalance, hyperparameter tuning |
| 10 | [Graph Mining](notebooks/L10_Graph_Mining.ipynb) | Graph structures, PageRank, community detection, NetworkX |
| 11 | [Data Visualisation and Ethics](notebooks/L11_Data_Visualisation_and_Ethics.ipynb) | Chart selection, algorithmic bias, privacy, explainability |

---

## Setup Instructions

### Option 1: Using pip (recommended for most students)

```bash
# 1. Clone the repository
git clone https://github.com/your-username/BITE485-DataScience.git
cd BITE485-DataScience

# 2. Create a virtual environment
python -m venv venv
source venv/bin/activate        # On Windows: venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Launch Jupyter
jupyter notebook
```

### Option 2: Using conda

```bash
# 1. Clone the repository
git clone https://github.com/your-username/BITE485-DataScience.git
cd BITE485-DataScience

# 2. Create and activate the conda environment
conda env create -f environment.yml
conda activate bite485

# 3. Launch Jupyter
jupyter notebook
```

### Option 3: Google Colab (no local installation required)

Each notebook can be opened directly in Google Colab. Click the Colab badge at the top of each notebook, or navigate to [colab.research.google.com](https://colab.research.google.com) and open from GitHub.

> **Note for students using Colab:** Run the first cell in each notebook to install required packages.

---

## Repository Structure

```
BITE485-DataScience/
├── README.md                          # This file
├── requirements.txt                   # pip dependencies
├── environment.yml                    # conda environment
├── notebooks/                         # Main lecture notebooks
│   ├── L01_Introduction_to_Data_Science.ipynb
│   ├── L02_Statistical_Inference.ipynb
│   ├── L03_Statistical_Modelling.ipynb
│   ├── L04_Exploratory_Data_Analysis.ipynb
│   ├── L05_Machine_Learning_Fundamentals.ipynb
│   ├── L06_Classification_Algorithms.ipynb
│   ├── L07_Regression_and_Clustering.ipynb
│   ├── L08_Feature_Engineering.ipynb
│   ├── L09_Model_Evaluation_and_Selection.ipynb
│   ├── L10_Graph_Mining.ipynb
│   └── L11_Data_Visualisation_and_Ethics.ipynb
├── solutions/                         # Instructor solutions (restricted)
│   └── README.md
└── data/
    └── README.md                      # Dataset sources and download instructions
```

---

## Prerequisites

Students should be comfortable with:
- Basic Python programming (variables, loops, functions, classes)
- Basic mathematics (algebra, basic calculus concepts)
- Spreadsheet data (understanding rows, columns, and data types)

No prior machine learning experience is required.

---

## Academic Integrity

These notebooks are provided as learning resources. Students are expected to:
- Run and understand each code cell before moving to the next
- Attempt exercises independently before consulting solutions
- Not share completed exercise notebooks with other students

---

## Licence

These materials are provided for educational use at Tharaka University. Redistribution outside the university requires written permission from the lecturer.

---

*BITE 485 Data Science | Tharaka University | Department of Computer Science and ICT*
*kevin.tuei@tharaka.ac.ke | 0712 838 653*
