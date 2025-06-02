# Classification of Leukemia Subtypes Using Gene Expression Data

This project explores the classification of acute leukemia subtypes — Acute Lymphoblastic Leukemia (ALL) and Acute Myeloid Leukemia (AML) — using gene expression profiles from microarray data. The dataset, originally published in the landmark study by Golub et al. (“Molecular Classification of Cancer: Class Discovery and Class Prediction by Gene Expression Monitoring”), contains expression values for over 7,000 genes across 72 patient samples.

After preprocessing (including transposition, normalization, and dimensionality reduction via PCA), a logistic regression model was trained with hyperparameter tuning using GridSearchCV. The goal was to distinguish between ALL and AML patients based on their transcriptomic signatures.

While the final test accuracy was modest (~58.8%), the project demonstrates how classical machine learning approaches can be applied to high-dimensional biological data. This analysis serves as a starting point for future improvements using additional classifiers, feature selection methods, and more advanced dimensionality reduction techniques.
