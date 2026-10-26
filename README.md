# Predicting the Economic Impact of Natural Disasters

**Machine learning · Regression · Missing-data methods · Responsible AI**

> Individual bachelor's thesis project, Bocconi University. Predictions and performance figures are those reported in the supplied thesis materials.

## Overview
This research investigates machine-learning approaches to estimating economic damage from natural disasters using the **EM-DAT** database, while addressing data completeness, systematic reporting bias and responsible deployment.

## Approach
- Filtered natural-disaster records and excluded pre-2000 events to address historical reporting inconsistencies.
- Engineered disaster-impact features and within-hazard magnitude ranks.
- Compared **Gradient Boosting, XGBoost, Random Forest and Ridge Regression**.
- Explored missing-data strategies including group-wise median imputation, iterative Bayesian imputation and complete-case analysis.
- Evaluated ethical and governance considerations using the **capAI** framework.

## Highlight
The supplied project README reports **R² = 0.5865** for **XGBoost with median imputation**. See the thesis report for the experimental context and limitations; this metric has not been independently reproduced here.

## Files
- [`Thesis_Code.ipynb`](Thesis_Code.ipynb) — analysis and model comparison.
- [`Thesis_Report.pdf`](Thesis_Report.pdf) — complete thesis and ethical assessment.

## Run locally
Install packages from `requirements.txt` and open the notebook in Jupyter. The original EM-DAT dataset is **not included**; obtain data through its official source subject to its access and reuse terms. Update local data paths as needed. The notebook has not been independently run in this packaged version.

## Responsible use
This is an academic exploration, not a production system for allocating emergency resources. Dataset gaps and geographic/reporting biases limit interpretation and deployment.

## Author
**Alice Agazzi** — individual thesis project, Bocconi University.
