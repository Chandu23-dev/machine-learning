# Self-Training with Semi-Supervised Learning on Wine Quality Dataset

This project demonstrates how to apply Self-Training, a semi-supervised learning method, using the Wine Quality dataset.

## Overview

- Dataset: UCI Wine Quality (red wine)
- Simulates 80% missing labels for semi-supervised learning
- Uses Logistic Regression wrapped in SelfTrainingClassifier
- Evaluates using confusion matrix, ROC curve, and F1-score

## How to Run

1. Clone this repository:
    git clone https://github.com/yourusername/self-training-winequality.git
    cd self-training-winequality

2. Install dependencies:
    pip install -r requirements.txt

3. Open the notebook:
    jupyter notebook SelfTraining_WineQuality_Tutorial.ipynb

## Files Included

- `SelfTraining_WineQuality_Tutorial.ipynb`: Complete Jupyter notebook
- `winequality-red.csv`: UCI input dataset
- `README.md`: Project instructions
- `requirements.txt`: Required libraries
- `LICENSE`: MIT license

## Accessibility

- Colorblind-friendly plots
- Semantic headers for screen readers
- Alt-text captions and descriptive markdown
- Clear, step-by-step code explanations

## References

- Nigam et al. (2000): https://doi.org/10.1023/A:1007692713085
- Yarowsky (1995): https://doi.org/10.3115/981658.981684
- Zhu & Goldberg (2009): https://doi.org/10.2200/S00196ED1V01Y200906AIM006
- UCI Wine Quality Dataset: https://archive.ics.uci.edu/ml/datasets/wine+quality
