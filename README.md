# Anomaly Detection in Cloud Activity Logs

This project focuses on detecting anomalous and malicious behavior in cloud environments
using machine learning techniques applied to structured event logs.

The work includes binary and multiclass classification of attack-related activities,
as well as attacker profiling based on temporal behavior patterns.

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
## How to Run the Project

1. Clone the repository:
```bash
git clone https://github.com/sapircss/anomaly-detection-project.git
cd anomaly-detection-project
```

3. Create and activate a virtual environment:
```bash
python -m venv .venv
source .venv/bin/activate
```

5. Install required packages:
```bash
pip install -r requirements.txt
```

7. Place the dataset in the following structure:
```bash
data/
├── raw/
└── processed/
```

9. Run the notebooks in order:
```bash
01_data_loading.ipynb

02_feature_engineering.ipynb

03_binary_classification.ipynb

04_multiclass_classification.ipynb

attacker_profiling.ipynb
```


---

## Literature Review

A PDF file containing the literature review used for this project is included
---

## Summary

The notebooks demonstrate the feasibility of detecting anomalous cloud activities
and distinguishing between different attack types using supervised learning models.


## Author

Sapir Shenhav & Ofri Gross 



