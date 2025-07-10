# Skin Lesion Classification — NAS & Deep Learning Experiments

This repository contains the complete set of experimental notebooks for my undergraduate dissertation at the University of East London. The project focused on classifying skin lesions (benign vs malignant) using Neural Architecture Search (NAS) and deep learning, with robust evaluation methods relevant to medical imaging applications.

This dissertation was awarded **First Class Honours**.

---

## 🧩 Project Overview

Early detection of skin cancer is crucial for patient outcomes. My work demonstrates a full AI research workflow:
- Designing and executing a custom NAS pipeline to automatically discover an optimized CNN architecture.
- Comparing, refining, and testing model performance using best practices in medical imaging research.
- Validating model robustness to ensure generalizability and practical reliability.

---

## 📂 Notebooks

| # | Filename | Description |
|---|----------|--------------|
| **00** | `00_NAS_Architecture_Search.ipynb` | Defines the NAS search space using Keras Tuner, runs the architecture search on the skin lesion dataset, and saves the best model for further training. |
| **01** | `01_InDepth_Model_Evaluation.ipynb` | Loads trained models and performs detailed performance analysis: ROC curves, precision-recall curves, and confusion matrices. |
| **02** | `02_Improving_NAS_Model.ipynb` | Refines the NAS architecture with class balancing, optimal thresholding, and improved data handling to boost accuracy. |
| **03** | `03_Testing_NAS_Variants.ipynb` | Tests multiple saved NAS variants, aggregates key metrics, and visualizes performance comparisons. |
| **04** | `04_Stratified_KFold_CrossValidation.ipynb` | Validates the final NAS model using stratified K-Fold cross-validation to assess robustness and generalizability for medical applications. |

---

## 🛠️ How to Run

- All notebooks were developed and tested in **Google Colab**.
- Dataset download and environment setup steps are included within each notebook.
- You will need Kaggle API access for dataset downloads.

---

## 📍 Author

**Abu Sufian Basith**  
BSc (Hons) Artificial Intelligence — University of East London (**First Class Honours**)  
Applying for MSc Artificial Intelligence and Medical Imaging  

