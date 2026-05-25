# Machine Learning Classification & Decision Boundary Analysis

This repository contains a rigorous evaluation and comparative analysis of various supervised machine learning classification models. The project focuses on understanding how different algorithmic frameworks construct decision boundaries, manage hyperparameter variations, and handle complex classification constraints.

## 🛠️ Tech Stack & Core Libraries
* **Language:** Python 3.13
* **Libraries:** Scikit-Learn, Pandas, NumPy, Matplotlib, Seaborn
* **Environment:** Jupyter Notebook

## ⚙️ Core Algorithmic Evaluations & Implementations

The notebook explores the training mechanics, hyperparameter optimization, and boundary plotting for the following core classification algorithms:

1. **Support Vector Machines (SVM):**
   * Evaluated the effect of different mathematical kernels on geometric decision boundaries: **Linear, Polynomial (Poly), Radial Basis Function (RBF), and Sigmoid**.
   * Analyzed the impact of regularization parameters ($C$, $\gamma$, and degree) on margin optimization and boundary flexibility.
2. **Decision Trees & Ensembles:**
   * Analyzed the structural partitioning mechanics of **Decision Trees**.
   * Evaluated ensemble boosting and bagging capabilities through **Random Forests**, observing how variance reduces across multiple estimator groupings.
3. **Instance-Based & Parametric Baselines:**
   * Implemented **k-Nearest Neighbors (k-NN)** to evaluate localized density-based decision partitions across varying neighborhood weights ($k$).
   * Utilized **Logistic Regression** as a linear parametric baseline to assess probability-driven decision thresholds.
4. **Model Performance Interpretation:**
   * Documented model alignment, overfitting tendencies under loose constraints, and optimal hyperparameter choices based on classification accuracy and visual boundary convergence.

## 📂 Repository Contents
* `ml_classification_analysis.ipynb` -> Core Jupyter Notebook containing data synthesis, model executions, hyperparameter sweeps, and decision boundary visualizations.
* `README.md` -> High-level overview of the classification architecture.

## 🚀 Getting Started
1. Clone the repository:
   ```bash
   git clone [https://github.com/pd8r/Machine-Learning-Classification-Lab.git](https://github.com/pd8r/Machine-Learning-Classification-Lab.git)
