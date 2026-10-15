# Student Academic Performance Prediction — Random Forest Baseline

This project implements a Random Forest classification model to predict student academic outcomes (Dropout, Enrolled, or Graduate) using the UCI *Predict Students' Dropout and Academic Success* dataset.

The implementation forms part of Phase 2 of the coursework based on Islam et al. (2025).

## Dataset

- Source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/697/predict+students+dropout+and+academic+success)
- Records: 4,424 students
- Input features: 36
- Target classes: Dropout, Enrolled, Graduate

## Implementation

The model was developed in Python using Scikit-learn and includes:

- Stratified 80:20 training and testing split
- One-hot encoding of categorical features
- Random Forest classifier with 100 decision trees
- Classification report and confusion matrix
- Five-fold stratified cross-validation

## Results

| Evaluation Metric | Result |
|---|---|
| Test Accuracy | 76.16% |
| Mean Cross-Validation Accuracy | 77.28% |
| Cross-Validation Standard Deviation | 1.66% |
| Macro F1-Score | 0.66 |

## Running the Notebook

1. Download or clone this repository.
2. Open `phase02.ipynb` in VS Code or Jupyter Notebook.
3. Ensure `data.csv` is in the same directory as the notebook.
4. Install the required Python libraries: `pandas`, `numpy`, `matplotlib`, `scikit-learn`, and `ipykernel`.
5. Run all notebook cells in order.

## Reference

Islam et al. (2025). *The Integration of Explainable AI in Educational Data Mining for Student Academic Performance Prediction and Support System.*

https://doi.org/10.1016/j.teler.2025.100203