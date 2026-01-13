# Breast Cancer Identifiers

This repository contains three machine learning projects for breast cancer
classification and staging, implemented using Python and Jupyter Notebooks.

The projects use two well-known clinical datasets:
- The Wisconsin Breast Cancer Diagnostic dataset
- The SEER (Surveillance, Epidemiology, and End Results) breast cancer dataset

---

## Repository Structure

```text
breast-cancer-identifiers/
├─ README.md
├─ requirements.txt
├─ notebooks/
│  ├─ 01-wisconsin-binary.ipynb
│  ├─ 02-seer-multiclass-5stages.ipynb
│  └─ 03-seer-multiclass-3stages.ipynb
├─ data/
│  ├─ raw/
│  │  └─ data.csv              (Wisconsin)
│  └─ data.csv                 (SEER)

> Important:
> The repository does NOT include any dataset files due to datasets' license. 
> Users must download the datasets separately and place them exactly as shown above.

---

## Projects Overview

### 1. Wisconsin Breast Cancer – Binary Classification
- Task: Binary classification (Benign vs Malignant)
- Dataset: Wisconsin Breast Cancer Diagnostic Dataset
- Notebook: `01-wisconsin-binary.ipynb`
- Models: Logistic Regression, Random Forest, and others
- Evaluation: Accuracy, confusion matrix, classification report

---

### 2. SEER Breast Cancer – Multiclass Classification (5 Stages)
- Task: Multiclass classification using 5 AJCC 6th edition stages
- Dataset: SEER Breast Cancer Dataset
- Notebook: `02-seer-multiclass-5stages.ipynb`

---

### 3. SEER Breast Cancer – Multiclass Classification (3 Stages)
- Task: Classification of stages IIA, IIB, and IIIA only
- Dataset: SEER Breast Cancer Dataset
- Notebook: `03-seer-multiclass-3stages.ipynb`

---

## Dataset Download and Placement Instructions

### Wisconsin Breast Cancer Dataset

Source:
https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data

Steps:
1. Download the dataset 
2. Rename the file to: data.csv
3. Save it inside data/raw/data.csv

---

### SEER Breast Cancer Dataset

Source:
https://www.kaggle.com/datasets/sujithmandala/seer-breast-cancer-data

Important legal note:
SEER data is distributed under a Research Data Use Agreement.
Raw SEER data may not be redistributed publicly.
For this reason, the dataset is not included in this repository.

Steps:
1. Download the dataset 
2. Rename the file to: data.csv
3. Save it inside data/data.csv


---

## Installation and Environment Setup

1. Create a virtual environment (recommended):
open terminal inside the main directory
$python -m venv venv

2. Activate the virtual environment:

$.venv\Scripts\activate

3. Install requirements

$pip install -r requirements.txt

4. Running the Notebooks
Launch them using Jupyter Notebook or Visual Studio Code.

Run the notebook cells in order from top to bottom.
