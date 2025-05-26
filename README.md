# Micro/Nano Plastic Detection via Paper Microfluidic Chips

Tldr: Predicted whether samples are classifiable as "Plastic" or "No Plastic" using various binary algorithms, analysing their respective classification accuracy against formulated hypothesis that samples containing plastics would have an F1 score of 0.80 or above.

Goal: Detection & Classification of MNP’s in Water
(Binary classification: “Plastic” vs “No Plastic”)

Hypothesis 1: Samples are classifiable as “Plastic” or “No Plastic” using various binary algorithms with an F1 score of 0.80 or above.

Hypothesis 2: Bovine Serum Albumin (BSA) and Aspartic Acid will be the two most important reagents for this classification across all algorithms.

Algorithms:
1. Linear methods (Logistic Regression (No regularization, LASSO (L1), Ridge (L2), Linear SVM)
2. Tree methods (Random Forest, Gradient Boosting, Light Boosting, XGboost)


Discussion & Conclusion: 
1. Hypothesis 1 was supported; yes, data were classifiable via binary algorithms
as “plastic” or “no plastic” above an F1 score of 0.80. Model F1 scores were
between 0.882-0.989 with a median of 0.935.

3. Hypothesis 2 was not supported; BSA and Aspartic Acid were not always the
top reagents for classification.
