# Car Acceptability Classification Project

This project is part of **Micro Project 4** for the ANA500 Data Science course. It involves building machine learning models to classify car acceptability using a real-world dataset. The goal is to compare different learning algorithms and identify which model best predicts whether a car is considered "acceptable" based on multiple input attributes.

## Files in This Repository

- `Car_Acceptability_Classification.ipynb` — Main Jupyter Notebook containing all preprocessing, model building, and evaluation steps.
- `cars.data` — Dataset used for modeling (UCI Car Evaluation dataset).
- `README.md` — This file.

## Project Summary

The dataset includes categorical features such as buying price, maintenance cost, safety rating, and capacity, with the target being binary classification: **acceptable vs. unacceptable**.

### Models Used
- **Logistic Regression** — Baseline interpretable model for binary prediction.
- **Support Vector Machine (SVM)** — Effective in high-dimensional spaces.
- **Neural Network (Keras)** — Captures complex nonlinear relationships with higher accuracy.

### Objective & Evaluation
- The target variable is whether a car is "acceptable" or not.
- Models are evaluated on their ability to **identify acceptable cars** accurately.
- Metrics compared: **Accuracy**, **Precision**, **Recall**, and **F1-score** using the `'acceptable'` class scores.

## Tools & Libraries Used

- Python 3.x
- Jupyter Notebook
- Pandas, NumPy
- Scikit-learn
- TensorFlow/Keras
- Matplotlib, Seaborn

## How to Run the Code

To run this project locally:

1. **Clone or download** this repository to your local machine.
2. Make sure you have **Python 3.x** installed.
3. Open a terminal or Anaconda Prompt and install required libraries if you do not have them:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn tensorflow
   ```

4. Launch the Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

5. Open the file `Car_Acceptability_Classification.ipynb` and run the cells sequentially.

Make sure `cars.data` is located in the same directory as the notebook before running.