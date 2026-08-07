# Minimum Knowledge — ML Foundations

面接前に最低限、以下を**直感・数式・失敗例**の3方向から説明できる状態にする。

## Probability & Statistics
- [ ] 条件付き確率、Bayes rule
- [ ] expectation / variance / covariance
- [ ] independence と uncorrelated の違い
- [ ] Bernoulli / Binomial / Gaussian / Categorical
- [ ] law of large numbers / central limit theorem の直感
- [ ] MLE と MAP の違い
- [ ] confidence interval と hypothesis testing の基本
- [ ] correlation と causation の違い

## Linear Algebra
- [ ] vector / matrix multiplication の意味
- [ ] rank, basis, linear independence
- [ ] eigenvalue / eigenvector の直感
- [ ] SVD と PCA の関係
- [ ] positive definite matrix
- [ ] trace, determinant の基本的意味
- [ ] matrix norm / cosine similarity

## Optimization
- [ ] gradient descent / SGD / mini-batch SGD
- [ ] momentum / Adam
- [ ] learning rate が大きすぎる・小さすぎると何が起こるか
- [ ] convex vs non-convex
- [ ] local minimum / saddle point
- [ ] conditioning と optimization difficulty
- [ ] gradient clipping

## Information Theory
- [ ] entropy
- [ ] cross entropy
- [ ] KL divergence
- [ ] cross entropy と negative log-likelihood の関係
- [ ] KL が symmetric でない理由

## Core ML Concepts
- [ ] bias–variance tradeoff
- [ ] overfitting / underfitting
- [ ] L1 / L2 regularization
- [ ] train / validation / test split
- [ ] data leakage
- [ ] class imbalance
- [ ] calibration
- [ ] distribution shift / domain shift
- [ ] precision / recall / F1 / ROC-AUC / PR-AUC
- [ ] regression metrics: MSE / MAE / R²

## Classical Models — 面接 coverage
- [ ] linear regression
- [ ] logistic regression
- [ ] decision tree / random forest
- [ ] gradient boosting の直感
- [ ] k-means
- [ ] PCA
- [ ] SVM / kernel trick の直感

## 最低限の derivation
- [ ] Gaussian MLE
- [ ] linear regression の least-squares solution
- [ ] logistic regression + cross entropy gradient の考え方
- [ ] PCA が variance maximization になること

## Must-answer Questions
1. Why does regularization improve generalization?
2. Why is cross entropy commonly used for classification?
3. What is the difference between MLE and MAP?
4. When can accuracy be misleading?
5. How would you detect data leakage?
6. What changes under distribution shift?
