# Anomaly Detection in Cloud Activity Logs

This project focuses on detecting anomalous and malicious behavior in cloud environments
using machine learning techniques applied to structured event logs.

The work includes binary and multiclass classification of attack-related activities,
as well as attacker profiling based on temporal behavior patterns.

<img width="900" height="607" alt="image" src="https://github.com/user-attachments/assets/2881255f-1085-4ea9-a471-fcb2a5be859e" />


---

## Notebooks Overview

- **01_data_loading.ipynb**  
  Loading and preprocessing raw cloud event logs and labels.

- **02_feature_engineering.ipynb**  
  Feature extraction, aggregation over time windows, and preparation for modeling.

- **03_binary_classification.ipynb**  
  Binary classification: benign vs. malicious activity.

- **04_multiclass_classification.ipynb**  
  Multiclass classification of different attack types.

- **attacker_profiling.ipynb**  
  Analysis and profiling of attackers based on frequency, diversity, and temporal span of attacks.

---

## Data

Due to size and privacy considerations, the dataset is **not included** in this repository.

## Environment

- Python 3.x
- Jupyter Notebook
- Common libraries: pandas, numpy, scikit-learn, matplotlib

A virtual environment should be created locally before running the notebooks.

---

## Literature Review

A PDF file containing the literature review used for this project is included:
- `literature_review.pdf`

---

## Author

Sapir Shenhav & Ofri Gross 



