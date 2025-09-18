## 🧠 Core Concepts & Statistics
### Difference between Data Science and Data Analytics:
Data science focuses on building models and algorithms to predict or classify data, while data analytics emphasizes interpreting existing data to find actionable insights.
### Marginal Probability:
The probability of a single event occurring, regardless of other events.
### Conditional Probability:
Probability of event A given that event B has occurred:
P(A|B) = \frac{P(A \cap B)}{P(B)}
### Probability Axioms:
- Non-negativity: P(E) \geq 0
- Normalization: P(S) = 1
- Additivity: For disjoint events A and B, P(A \cup B) = P(A) + P(B)
### Bias-Variance Trade-off:
High bias → underfitting; high variance → overfitting. The goal is to balance both for optimal model performance.
###Survivorship Bias:
Focusing only on successful cases and ignoring failures, leading to misleading conclusions.

## 📊 Machine Learning & Modeling
### Machine Learning vs Deep Learning:
ML uses algorithms to learn patterns; DL uses neural networks with multiple layers for complex tasks like image recognition.
### Logistic Regression:
A classification algorithm that predicts probabilities using the sigmoid function. Example: predicting customer churn.
### Random Forest:
An ensemble of decision trees that vote on the final output. It reduces overfitting and improves accuracy.
### Support Vectors in SVM:
Data points closest to the decision boundary; they define the margin and influence the model.
### Handling Imbalanced Datasets:
Use techniques like SMOTE, undersampling, oversampling, or adjusting class weights.

## 🧮 Mathematics & Data Wrangling
### Eigenvectors and Eigenvalues:
In linear algebra, they help in dimensionality reduction (e.g., PCA).
A \cdot v = \lambda \cdot v, where v is the eigenvector and \lambda is the eigenvalue.
### Long vs Wide Format:
Long: multiple rows per subject; Wide: one row per subject with multiple columns.
### Sampling Techniques:
Simple random, stratified, cluster sampling. Advantage: reduces computation and cost while maintaining representativeness.
### Resampling:
Used for model validation (e.g., cross-validation) or to adjust data distributions.

## 🧪 Model Evaluation & Metrics
### Confusion Matrix:
A table showing TP, FP, FN, TN. Helps evaluate classification performance.
### RMSE vs MSE:
RMSE: square root of MSE; both measure prediction error. RMSE penalizes large errors more.
### Overfitting vs Underfitting:
Overfitting: model too complex, fits noise.
Underfitting: model too simple, misses patterns.

## 🧰 Tools & Practical Scenarios
### Training on 10GB with 4GB RAM:
Use batch processing, data generators, or cloud-based solutions like Google Colab or AWS.
### Explaining to Non-Technical Stakeholders:
- Use analogies, visuals, and focus on business impact rather than technical jargon.
### Managing Deadlines:
  Prioritize tasks, use agile methods, and communicate progress regularly.

