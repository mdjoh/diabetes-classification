# Diabetes Classification Challenge
Machine Learning class diabetes classification challenge

## Scope
Binary classification task - Predict whether a person has diabetes (labeled as 1) or not (labeled as 0)

Macro F1 Score was the performance metric used (higher the better)

## Data
The dataset, aside from the target <em>diabetes</em>, consists of 9 features:
- Id
- Number of times pregnant
- Plasma glucose
- Diastolic blood pressure (DBP)
- Triceps skinfold measurement
- Serum insulin level
- BMI
- Pedigree
- Age

## Approach
Four algorithms were used:
- Logistic regression
- AutoML (FLAML)
- XGBoost
- Feedforward neural network with 6 hidden layers

## Results

| Algorithm | Macro F1 Score - Kaggle Submission Score|
| ----------- | ----------- |
| Logistic Regression | 0.72489 |
| AutoML | 0.73662 |
| XGBoost | 0.73021        |
| Neural Network | 0.77229 |
