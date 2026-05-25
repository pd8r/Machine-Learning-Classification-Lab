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
* `customer_segmentation.ipynb` -> Core Jupyter Notebook containing data pipeline executions.
* `Wholesale customers data.csv` -> Local source dataset in CSV format for seamless cross-platform loading.
* `README.md` -> Technical overview of the project architecture.

## 🚀 Getting Started
1. Clone the repository:
   ```bash
   git clone [https://github.com/pd8r/Machine-Learning-Classification-Lab.git](https://github.com/pd8r/Machine-Learning-Classification-Lab.git)



## Step 4: Add it to Your Master Profile Landing Page 🔄

Once that is saved, let's make sure it shows up on your main homepage. Go to your **`pd8r`** profile repository, edit its `README.md`, and update your **Featured Pipelines** section so all three projects sit side-by-side:

```markdown
## 📂 Featured Pipelines
* 🏠 [AmesHousing-ML-Pipeline](https://github.com/pd8r/AmesHousing-ML-Pipeline) - End-to-end regression pipeline focusing on data cleaning, log transformations, and robust scaling.
* 📦 [Wholesale-Customer-Segmentation](https://github.com/pd8r/Wholesale-Customer-Segmentation) - Unsupervised learning pipeline utilizing UMAP, K-Means, and DBSCAN for multi-dimensional data clustering.
* 🎯 [Machine-Learning-Classification-Lab](https://github.com/pd8r/Machine-Learning-Classification-Lab) - Supervised learning framework evaluating decision boundaries and hyperparameter tuning across SVM, Random Forests, KNN, and Logistic Regression.
