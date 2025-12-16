# Predicting Smartphone Battery Drain Using Linear Regression

This project applies Simple Linear Regression in Python to analyze the relationship between smartphone screen time and battery drain.

## Dataset
A self-generated dataset simulating real-world smartphone usage behavior, consisting of screen time (hours) and corresponding battery drain percentage.

## Methodology
- Loaded and explored the dataset using Pandas
- Split data into training and testing sets (80–20)
- Trained a Linear Regression model on training data
- Evaluated model performance on unseen test data
- Visualized training data, test data, and regression line

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## Evaluation Metrics
- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)

## Results
The model shows a strong linear relationship between screen time and battery drain, with good generalization on test data.

## How to Run
```bash
pip install -r requirements.txt
python linear_regression.py
