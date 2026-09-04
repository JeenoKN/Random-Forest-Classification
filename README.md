# Random Forest Classification Project

A supervised machine learning project for binary classification using a Random Forest model. The project covers data preparation, preprocessing, model training, evaluation, and prediction on a separate live dataset.

## Project Objective

The goal is to predict a binary target (`0` or `1`) from structured tabular data while maintaining balanced performance and reliable detection of the positive class.

## Dataset

The training dataset contains 20,900 records and 19 columns, including the target label. The live dataset contains 6,967 records and 18 feature columns.

The data includes both numerical and categorical features, so separate preprocessing pipelines are applied before model training.

## Machine Learning Workflow

```text
Training Data
     |
     v
Feature / Target Split
     |
     v
Numeric + Categorical Preprocessing
     |
     v
Random Forest Classifier
     |
     v
Hyperparameter Tuning / Evaluation
     |
     v
Live Dataset Prediction
```

## Preprocessing

### Numerical Features
- Missing-value imputation
- Standard scaling

### Categorical Features
- Missing-value handling
- One-hot encoding

The preprocessing steps are combined with the classifier using Scikit-learn pipelines to keep training and prediction transformations consistent.

## Model

- Algorithm: Random Forest Classifier
- Framework: Scikit-learn
- Task: Binary Classification
- Evaluation focus: balanced classification performance and positive-class detection

## Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

## Repository Structure

```text
Random-Forest-Classification/
├── Dataset/                     # Training and live datasets
├── RF/                          # Random Forest notebook and comparison work
├── model1/                      # Earlier model experiment
├── G19_predictions.live.csv     # Final prediction output
├── G19_report.pdf               # Final project report
├── step1_data_preparation.pdf   # Coursework documentation
├── step2_preprocessing.pdf
├── step3_data_modeling.pdf
├── step4_prediction.pdf
└── README.md
```

## Main Notebook

The main Random Forest workflow is available in:

```text
RF/Random_Forest.ipynb
```

It includes:

- Dataset loading and inspection
- Feature and target separation
- Numerical and categorical preprocessing
- Random Forest model training
- Model evaluation
- Prediction generation for the live dataset

## Running the Project

### 1. Clone the repository

```bash
git clone https://github.com/JeenoKN/Random-Forest-Classification.git
cd Random-Forest-Classification
```

### 2. Create a virtual environment (recommended)

```bash
python -m venv .venv
```

Activate it, then install the dependencies:

```bash
pip install -r requirements.txt
```

### 3. Open the notebook

```bash
jupyter notebook RF/Random_Forest.ipynb
```

## Key Learning Outcomes

This project provided hands-on experience with:

- Supervised machine learning
- Tabular data preprocessing
- Scikit-learn pipelines
- Random Forest classification
- Handling numerical and categorical features
- Model evaluation
- Generating predictions for unseen data

## Project Type

Course Project  
Bachelor of Engineering in Computer Engineering

## Author

**Theeramonrapat Vichaisri**  
Computer Engineering Student
