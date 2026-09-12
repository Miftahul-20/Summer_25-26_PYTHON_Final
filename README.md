# Student Performance Analysis

A machine learning based Student Performance Analysis project developed as part of a university Python programming course.

This project analyzes student performance data and uses K-Nearest Neighbors (KNN), Support Vector Machine (SVM), and Random Forest classification models to predict whether a student will pass or fail using survey-based features that exclude direct grade information.

## 1. Features:

- Student performance data processing and cleaning
- Missing value and duplicate row checking
- Pass/fail classification based on final grade
- Categorical data encoding
- Feature and target preparation
- Training and testing data split
- Feature standardization using StandardScaler
- Machine learning models: KNN, SVM, RF
- Confusion matrix visualization
- Accuracy, precision, recall and F1-score evaluation
- Model performance comparison

## 2. Technologies:

- Python 3
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

## 3. Installation:

pip install pandas numpy matplotlib scikit-learn jupyter

## 4. Usage:

Open the notebook using Jupyter Notebook.

The notebook can also be opened and executed using Google Colab.

The dataset is loaded directly from the project's GitHub repository.


## 5. Model Results:

The notebook evaluates three classification models using accuracy, precision, recall and F1-score.

| Model | Accuracy | Precision | Recall | F1 Score |
|---|---:|---:|---:|---:|
| KNN | 0.7703 | 0.7093 | 0.7703 | 0.7139 |
| SVM | 0.7225 | 0.7528 | 0.7225 | 0.7346 |
| Random Forest | 0.7990 | 0.7715 | 0.7990 | 0.7630 |

Random Forest achieved the highest accuracy and F1-score among the three models in the evaluation.

## 6. Team Contributions:

This project was developed collaboratively by a team of three students as part of a university Python programming course.

I. Miftahul Jannat- Data processing and cleaning, encoding and feature preparation

II. Arham Jarif Alam- Feature scaling, K-Nearest Neighbors (KNN) model implementation and evaluation

III. Arif Billah Fardin- Support Vector Machine (SVM) model implementation and evaluation, Random Forest (RS) model implementation and evaluation and final analysis

All team members collaborated on testing, debugging, analysis, and the overall development of the project.
