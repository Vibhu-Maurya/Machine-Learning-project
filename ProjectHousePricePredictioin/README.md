🏠 House Price Prediction using Simple Linear Regression

This project demonstrates a Simple Linear Regression model built from scratch using scikit-learn to predict house prices based on house features.

The notebook is designed for learning and practice, focusing on understanding the end-to-end ML workflow.

🚀 Project Overview

Manually created dataset (no external files)

Implements Simple Linear Regression

Uses scikit-learn

Visualizes training results using Matplotlib

Runs seamlessly on Google Colab

📓 Notebook
8e3b7278-1cd8-499f-bacb-60acf12c3a1f.ipynb


The notebook includes an Open in Colab button for easy execution.

🧠 What This Notebook Does

Imports required libraries:

pandas

numpy

matplotlib

scikit-learn

Creates a sample housing dataset manually:

sqft_living → feature (X)

price → target (Y)

Converts the dataset into a Pandas DataFrame

Splits the data into:

Training set

Test set

Trains a Linear Regression model

Makes predictions on:

Training data

Test data

Prints model parameters:

Slope (coefficient)

Intercept

Visualizes:

Training data

Regression line

📊 Dataset Description
Feature	Description
sqft_living	Size of the house in square feet
price	Price of the house

Dataset is synthetically created for learning purposes.

🛠️ Technologies Used

Python 🐍

Pandas

NumPy

Matplotlib

Scikit-learn

Jupyter Notebook

Google Colab

▶️ How to Run
Option 1: Google Colab (Recommended)

Open the notebook

Click Open in Colab

Run cells sequentially

Option 2: Run Locally
pip install pandas numpy matplotlib scikit-learn
jupyter notebook

📈 Output & Visualization

Scatter plot of training data

Best-fit regression line

Model coefficients printed in output

This helps visualize how house price changes with house size.

❗ Notes

This project is for educational purposes

No external dataset is used

No model weights are saved

Focus is on concept clarity, not deployment

🌱 Future Improvements

Use a real housing dataset

Add evaluation metrics (R², MAE)

Extend to Multiple Linear Regression

Add test data visualization

📜 License

This project is intended for learning and educational use only.

⭐ Acknowledgement

Built as part of Machine Learning fundamentals practice.
