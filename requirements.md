# Requirements – Emotion Recognition (CSEMCSPCSP01)

## Functional Requirements
- Load and preprocess FER-2013 dataset (35,887 grayscale images)
- Train 3 models: Logistic Regression, Random Forest, Gradient Boosting
- Achieve ≥80% accuracy on test set
- Save best model as .joblib
- Generate confusion matrix + classification report

## Non-Functional Requirements
- Run on CPU (no GPU needed)
- Inference time <1 second per image
- Code fully documented and tested
- Public GitHub with proper commit history
- No personal data (FER-2013 is anonymized)

Target: Mental health apps, customer sentiment analysis