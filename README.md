# Mathematics for Machine Learning — Complete Notes

> **Purpose**: Master every mathematical concept you need to understand, build, and debug ML models.  
> Every section includes **what it is → why ML needs it → how it works → examples**.

---

## Table of Contents

### Theory Notes

| # | Topic | Sections | File |
|---|---|---|---|
| 1 | **Linear Algebra** | Scalars/Vectors/Tensors, Matrix Ops, Determinants, Inverse, Eigenvalues, Diagonalization, SVD, Norms, Rank | [01_Linear_Algebra.md](01_Linear_Algebra.md) |
| 2 | **Calculus** | Derivatives, Partial Derivatives, Chain Rule, Gradient & Gradient Descent, Jacobian, Hessian, Taylor Expansion | [02_Calculus.md](02_Calculus.md) |
| 3 | **Probability & Statistics** | Probability Rules, Bayes' Theorem, Random Variables & PDFs, Expectation & Variance, Covariance & Correlation, Distributions, MLE, Information Theory | [03_Probability_and_Statistics.md](03_Probability_and_Statistics.md) |
| 4 | **Discrete Mathematics** | Sets & Logic, Combinatorics, Graph Theory, Trees & Decision Structures, Algorithmic Complexity | [04_Discrete_Mathematics.md](04_Discrete_Mathematics.md) |
| 5 | **Summary & Roadmap** | Math ↔ ML Algorithm Map, Formula Cheat Sheet, 8-Week Study Plan | [05_Summary_and_Roadmap.md](05_Summary_and_Roadmap.md) |

### Practical Notebooks

| Notebook | Description | Key Concepts |
|---|---|---|
| [linearregression.ipynb](linearregression.ipynb) | Hands-on linear regression using scikit-learn — fit a model, extract slope/intercept, visualize the regression line, and make predictions | Least squares, `LinearRegression`, matplotlib visualization |
| [logisticregression.ipynb](logisticregression.ipynb) | Hands-on logistic regression using scikit-learn — train/test split, model training, accuracy evaluation, and sigmoid curve visualization | Binary classification, `LogisticRegression`, sigmoid function, train-test split |
| [svm.ipynb](svm.ipynb) | Hands-on SVM classification using scikit-learn — feature scaling, RBF kernel, decision boundary visualization, and confusion matrix | `SVC`, kernel trick, `StandardScaler`, decision boundary |

### Sample Data

| File | Description |
|---|---|
| [sample_data/student_data.csv](sample_data/student_data.csv) | Student study hours and pass/fail outcomes for logistic regression |
| [sample_data/iris_binary.csv](sample_data/iris_binary.csv) | Binary Iris subset (Setosa vs Versicolor) for SVM classification |

---

## How to Use These Notes

1. **Sequential study**: Follow files 01 → 05 in order for a structured learning path
2. **Reference lookup**: Jump to any file for a specific topic
3. **Each file is self-contained** with definitions, formulas, worked examples, and ML connections
4. **Navigation links** at the bottom of each file let you move between sections
5. **Run the notebooks**: Open the `.ipynb` files to see the math in action with real code

---

## Prerequisites

- Python 3.8+
- Install dependencies:

```bash
pip install -r requirements.txt
```

---

*These notes cover the mathematical foundations needed for understanding, implementing, and debugging machine learning algorithms.*
