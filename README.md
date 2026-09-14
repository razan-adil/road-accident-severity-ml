# Road Accident Severity Prediction

Machine learning project for predicting road traffic accident severity using multiple classification models.

## Project Overview

This project explores a road traffic accident dataset and applies a complete machine learning workflow, including:

- Dataset loading and exploration
- Missing-value handling
- Categorical feature encoding
- Feature scaling
- Train/test splitting
- Class balancing with SMOTE
- Logistic Regression
- Random Forest
- Support Vector Machine (SVM)
- XGBoost
- Confusion matrices and classification reports
- Feature-importance analysis
- Model accuracy comparison

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- scikit-learn
- imbalanced-learn
- XGBoost
- Google Colab

## Project File

The original project code is kept unchanged in:

`aml_project.py`

## Dataset

The current project code loads the dataset from a Google Drive path:

`/content/drive/MyDrive/AML Project/RTA Dataset.csv`

To run the project successfully, make sure the dataset is available at the expected path in Google Colab, or update the path locally on your own machine.

## Models

The project compares:

1. Logistic Regression
2. Random Forest
3. Support Vector Machine (SVM)
4. XGBoost

The final section compares model accuracy and selects the best-performing model based on the generated results.

## How to Run

1. Install the required packages:

```bash
pip install -r requirements.txt
```

2. Open the project in Google Colab or a compatible Python environment.
3. Make sure the dataset is available.
4. Run the code from top to bottom.

## Repository Structure

```text
road-accident-severity-ml/
├── aml_project.py
├── README.md
├── requirements.txt
└── .gitignore
```

## Note

This repository is a portfolio-ready presentation of the original academic machine learning project. The project logic and code were preserved without changing the original implementation.
