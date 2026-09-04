# Machine Learning (Graduate Coursework)

This repository contains problem sets, empirical assignments, coding solutions, and the final term project for the graduate-level **Machine Learning** course.

---

## Repository Structure

```text
Machine-Learning/
├── HW1/          # Linear Regression, Ridge/Lasso, and Support Vector Machines (SVMs)
├── HW2/          # Logistic Regression, k-NN, Naive Bayes, and Data Preprocessing
├── HW3/          # Polynomial Regression, Regularization, and Gradient Descent Variants
├── HW4/          # Decision Trees, Random Forests, Information Gain, and Pruning
├── HW5/          # Ensemble Methods, Gradient Boosting, AdaBoost, and Bagging
├── HW6/          # Unsupervised Learning, K-Means, PCA, Hierarchical Clustering, and t-SNE
├── Project/      # Final Term Project:
│   ├── Landscape_and_AI_Authenticity_Classification.ipynb  # Dual-objective CNN & Transfer Learning
│   ├── Machine Learning - Final Project.pdf                # Project specification document
│   ├── train/                                              # Ground-truth dataset (jungle, mountain, sea)
│   └── README.md                                           # Project methodology & findings report
└── handson-ml3/  # Reference implementation modules (Géron, 3rd Edition)
```

---

## Course Assignments Breakdown

- **HW1:** Statistical learning theory, bias-variance tradeoff, closed-form ordinary least squares vs. iterative gradient descent, support vector classifiers with linear and RBF kernels.
- **HW2:** Probabilistic classifiers, Gaussian Naive Bayes, logistic regression with $L_1$ and $L_2$ penalties, k-Nearest Neighbors distance metrics, feature scaling and standardization.
- **HW3:** Polynomial feature mapping, Ridge, Lasso, and ElasticNet regularizations, learning curves, and batch vs. stochastic gradient descent.
- **HW4:** Non-parametric classification and regression trees, CART algorithm, Gini impurity vs. Shannon entropy, tree pruning, and decision boundary visualization.
- **HW5:** Ensemble learning paradigms, bootstrap aggregation (Bagging), Random Forests with feature importance ranking, AdaBoost, and Gradient Tree Boosting.
- **HW6:** Dimensionality reduction via Principal Component Analysis (PCA), singular value decomposition (SVD), K-Means clustering, and agglomerative hierarchical clustering.

---

## Final Project
Located in [`Project/`](Project/):
- **Objective 1:** Multi-class natural landscape classification (`jungle`, `mountain`, `sea`).
- **Objective 2:** Authentic vs. AI-generated image discrimination (real photographs vs. Stable Diffusion / DALL-E outputs).
- **Architectures:** Custom 8-layer deep CNN trained from scratch vs. pre-trained **ResNet-152V2** and **MobileNetV3-Large** transfer learning.
- **Data Pipeline:** Single-pass tabular ingestion, dynamic horizontal flip/zoom/rotation augmentation, and stratified train/validation/test evaluation.
