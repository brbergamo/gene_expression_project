# Classification of Leukemia Subtypes Using Gene Expression Data

This project explores the classification of acute leukemia subtypes — Acute Lymphoblastic Leukemia (ALL) and Acute Myeloid Leukemia (AML) — using gene expression profiles from microarray data. The dataset, originally published in a biomedical study, contains expression values for over 7,000 genes across 72 patient samples.

After preprocessing the data (including transposition, normalization, and dimensionality reduction via PCA), we trained a logistic regression model with hyperparameter tuning using GridSearchCV. The model aimed to distinguish between ALL and AML patients based on their gene expression signatures.

Although the final accuracy was modest (≈ 58.8%), the project provides a strong foundation for exploring how classical machine learning methods can be applied to high-dimensional transcriptomic data. This analysis could be expanded in future work using additional classifiers, feature selection, and more advanced dimensionality reduction strategies.
