README.md

Liver Cirrhosis Stage Detection
Description

This project implements a machine learning system to predict the stage of liver cirrhosis using patient clinical data. The model analyzes medical parameters and classifies patients into three disease stages.

The system uses data preprocessing, multiple classifiers, and performance evaluation to achieve accurate predictions.

Project Structure

data/

liver_cirrhosis.csv

main.ipynb

Complete notebook for preprocessing, training, evaluation, and prediction

model.pkl

Trained XGBoost model

scaler.pkl

StandardScaler object

README.md

Project documentation

Technologies Used

Python

NumPy

Pandas

Scikit-learn

XGBoost

Matplotlib

Seaborn

Workflow

Load dataset

Handle missing values

Encode categorical features

Scale numerical features

Split into training and testing sets

Train machine learning models

Evaluate performance

Save best model

Predict new samples

Model Used

The final model used in this project is XGBoost Classifier.

Reasons for selection:

High accuracy

Robust performance

Efficient handling of complex patterns

Feature importance analysis

How to Run

Install required libraries

Place dataset in data folder

Open main.ipynb

Run all cells in sequence

View results and predictions

Input Format

Input should be a list of numerical values representing patient attributes in the same order as the dataset features.

All values must be preprocessed before prediction.

Output

The system outputs:

Stage 1: Early stage

Stage 2: Moderate stage

Stage 3: Advanced stage

Results

The XGBoost model achieved the highest accuracy among all tested models and provided reliable classification results.

Performance is evaluated using confusion matrix and classification report.

Limitations

Limited dataset

No real-time validation

Depends on data quality

Future Improvements

Web-based application

Mobile interface

Larger datasets

Deep learning integration

Real-time hospital systems

Author

Harsh

B.Tech CSE (AI & ML)
