# Binary Classification of Insurance Cross Selling
### Goal:
The objective of this competition is to predict which customers respond positively to an automobile insurance offer.

### Evaluation:
Submissions are evaluated using area under the **ROC curve using the predicted probabilities and the ground truth targets.**
### Dataset Description
The dataset for this competition (both train and test) was generated from a deep learning model trained on the Health Insurance Cross Sell Prediction Data dataset. Feature distributions are close to, but not exactly the same, as the original. Feel free to use the original dataset as part of this competition, both to explore differences as well as to see whether incorporating the original in training improves model performance.

### Observations:
- For this Classification problem, we have chosen ROC_AUC_score as the metrics and the performance achieved through various model is as follows:

    - Logistic Regression AUC: Train-0.5030039902175314, Test-0.5030442897102999
    - Decision Tree AUC: Train-1.0, Test-0.6211547671101074
    - XGBoost: Train-0.5419574280820364, Test-0.5409840305051081
    - Artifical Neural Network has given the **Best performance:** Train-0.8552, Test-0.8560142517089844
