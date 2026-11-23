# MATH3092 Mathematics Project

Notes written as Jupyter notebooks. Each one works through the maths (derivations and proofs in LaTeX) and then checks it with code, with plots.

## Contents

| Notebook | Topics |
|---|---|
| [MLEs, Linear Regression and Learning Theory](notes/MLEs%2C%20Linear%20Regression%20and%20Learning%20Theory.ipynb) | Maximum likelihood, least squares and the normal equations, ridge and lasso, MAP estimation, why lasso is sparse, cross-validation, bias-variance tradeoff |
| [Logistic Regression](notes/Logistic%20Regression.ipynb) | Sigmoid and log-odds, cross-entropy loss, gradient and Hessian derivations, convexity, GD and SGD, separable data and L2, softmax regression, Naive Bayes, precision/recall, ROC and AUC |
| [Nonparametric Methods](notes/Nonparametric%20Methods.ipynb) | k-nearest neighbours, curse of dimensionality, decision trees (CART), bagging, random forests, out-of-bag error, feature importance (MDI and permutation) |

## Running the notebooks

```bash
pip install numpy matplotlib jupyter scikit-learn
jupyter lab
```

The notebooks only need `numpy` and `matplotlib`. `scikit-learn` is used only to load the Iris dataset in the nonparametric methods notes. All models are implemented from scratch in numpy.

## Reference

K. P. Murphy, *Probabilistic Machine Learning: An Introduction* (MIT Press, 2022)
