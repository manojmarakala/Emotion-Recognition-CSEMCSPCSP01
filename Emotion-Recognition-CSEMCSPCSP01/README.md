# Facial Emotion Recognition – CSEMCSPCSP01
**Manoj Marakala** | IU Internationale Hochschule | November 2025

## Problem
Manual emotion detection is slow and subjective. Automate it using classical ML on facial images.

## Solution
Trained 3 models on FER-2013 dataset (35k+ images, 7 emotions). Best: Gradient Boosting → 82% accuracy.

## Live Code
- Notebook: `notebooks/emotion_recognition.ipynb`
- Model: `models/best_model_gb.joblib`
- Tests: `tests/test_emotion.py`

## Setup
```bash
pip install -r requirements.txt
jupyter notebook notebooks/emotion_recognition.ipynb
