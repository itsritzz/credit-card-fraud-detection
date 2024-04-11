# Fraud Detection in Digital Payments

## Problem Setting
- Detection of fraudulent activities in modern digital payments.
- Safeguarding trust and economic stability.
- Challenges include evolving fraud methods and the need for robust detection.

## Problem Definition
- Construct a resilient and adaptable model for fraud identification and prevention.
- Deal with perpetually evolving fraud patterns and class imbalance.
- Ensure model interpretability and effective feature creation.

## Data Source
- "Credit Card Fraud Detection Dataset 2023" from Kaggle.
- Over 550,000 records from European cardholders in 2023.
- Contains anonymized transaction attributes like V1-V28 and transaction amount.

## Data Considerations
- Chose a balanced dataset to avoid biases in model training.
- Ensured equal representation of fraudulent and non-fraudulent transactions.
- Used Principal Component Analysis (PCA) for dimensionality reduction.

## Modelling
### Logistic Regression Classification
- Achieved 96.30% accuracy.
- Balanced precision and recall.
- Confusion matrix highlighted correct classifications.

### Random Forest Classification
- Achieved 99.98% accuracy.
- Perfect precision, recall, and F1-score.
- No misclassifications.

### Isolation Forest
- Implemented anomaly detection with 51% accuracy.
- AUC-PR value of 0.45 suggests moderate performance.
- Considered precision-recall trade-off.

### KNN Classifier
- Demonstrated exceptional performance with near-perfect metrics.
- Indicative of potential overfitting.

## Impact of Project Outcomes
- Enhances security and reliability of digital payment systems.
- Models can be deployed for real-world fraud detection.
- Feature importance analysis provides insights for model interpretation.

## Considerations
- Metrics beyond accuracy are crucial for imbalanced datasets.
- Overfitting should be carefully assessed.
- Precautions for working with imbalanced data in the future.

## Conclusion
- Successful development and evaluation of multiple classification models.
- High-performing models and insights into data patterns.
- Foundation for deploying effective fraud detection systems.
