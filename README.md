# Lightweight Skin Lesion Classification with Neural Architecture Search

**Abu Sufian Basith | BSc Data Science & Artificial Intelligence, University of East London, 2025 (First Class Honours)**

Undergraduate dissertation exploring a lightweight CNN classifier for imbalanced skin-lesion images, using **Keras Tuner Hyperband** and follow-up evaluation experiments. Based on ISIC 2019. The notebooks document academic experiments, **not a clinically validated diagnostic system**.

## Approach

- Image preprocessing and augmentation.
- Neural architecture search with Keras Tuner Hyperband.
- Experiments with class weighting, focal loss and threshold selection.
- ROC and precision–recall evaluation, confusion matrices and stratified cross-validation.

## Notebooks

| File | Contents |
|---|---|
| [00_NAS_Architecture_Search.ipynb](00_NAS_Architecture_Search.ipynb) | Define/search candidate CNN architectures. |
| [01_InDepth_Model_Evaluation.ipynb](01_InDepth_Model_Evaluation.ipynb) | Evaluate models and visualise classification performance. |
| [02_Improving_NAS_Model.ipynb](02_Improving_NAS_Model.ipynb) | Address imbalance and refine training/evaluation. |
| [03_Testing_NAS_Variants.ipynb](03_Testing_NAS_Variants.ipynb) | Compare architecture/training variants. |
| [04_Stratified_KFold_CrossValidation.ipynb](04_Stratified_KFold_CrossValidation.ipynb) | Cross-validation experiments. |

These notebooks were developed in Google Colab and require appropriate dataset access. Dataset download and environment setup steps are described within the notebooks. Exact metrics vary by experimental checkpoint; do not interpret every notebook output as the final selected model.

**Reproducibility note:** a pinned standalone environment, selected trained weights and a one-command deployment are not published in this repository. Follow ISIC dataset terms for imagery. The First Class Honours classification refers to the completed **degree**, not a separate verified classification for this dissertation.
