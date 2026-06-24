# Iris Classification using KNN 🌸

DecodeLabs Industrial Training | Batch 2026 | Project 2

## About
A supervised machine learning model that classifies Iris flowers
into 3 species — Setosa, Versicolor, and Virginica —
using the K-Nearest Neighbors (KNN) algorithm.

## Results
- Accuracy: 100%
- Algorithm: K-Nearest Neighbors
- Optimal K: 2 (via Elbow Method)

## Dataset
- Iris Dataset (sklearn)
- 150 samples | 3 classes | 4 features
- Features: Sepal Length, Sepal Width, Petal Length, Petal Width

## Pipeline
1. Load Iris dataset
2. Feature scaling (StandardScaler)
3. Train-Test split (80/20)
4. KNN model training
5. Prediction + Evaluation
6. Confusion Matrix & Elbow Curve visualization

## Files
- `iris_classification_knn.ipynb` — Main notebook
- `confusion_matrix.png` — Model evaluation
- `elbow_curve.png` — Optimal K selection

## Tech Stack
Python | Scikit-learn | Pandas | Matplotlib | Seaborn | KNN
