# System Architecture (Text UML)

## Context Diagram
User → [Emotion Recognition System] → FER-2013 Dataset

## Building Block View
┌─────────────────┐    ┌──────────────────┐    ┌─────────────────┐
│   Input Image   │ →  │   Preprocessing  │ →  │   ML Model      │ → Prediction
│   (48x48 gray)  │    │ (flatten, scale) │    │ (RF/GB/LR)      │
└─────────────────┘    └──────────────────┘    └─────────────────┘

Tools: scikit-learn, pandas, matplotlib, seaborn, joblib