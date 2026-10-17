# Breast Cancer Prediction with Neural Network model

This project uses a Neural network model to predict whether a breast tumor is **malignant** or **benign** based on measured characteristics from cancer images.

> This project is for educational machine-learning practice only. It must not be used for real medical diagnosis.

## Dataset

Each row represents one patient and includes:

- `id`: unique patient identifier
- `diagnosis`: target variable
  - `M`: malignant tumor
  - `B`: benign tumor
- Numeric features describing tumor characteristics, including:
  - `radius_mean`
  - `texture_mean`
  - `perimeter_mean`
  - `area_mean`
  - `smoothness_mean`
  - `compactness_mean`
  - `concavity_mean`
  - `concave points_mean`

## Goal

Train a nn model to predict the `diagnosis` column from the numerical tumor measurements.

```text
Input:  tumor measurements
Output: M (malignant) or B (benign)
