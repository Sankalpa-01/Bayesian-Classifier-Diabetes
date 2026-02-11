# Diabetes Prediction Analysis using Bayesian Classifier

An AI-driven classification project that utilizes a **Gaussian Naive Bayes** model to predict the likelihood of diabetes in patients based on physiological metrics.

## Project Overview
This project demonstrates the application of Bayesian probability to medical diagnostic data. By analyzing glucose levels and blood pressure, the model identifies patterns to classify patients into "Diabetic" or "Non-Diabetic" categories with high precision.

## Tech Stack
* **Language:** Python
* **Libraries:** * `Scikit-Learn` (Machine Learning Modeling)
    * `Pandas` (Data Manipulation)
    * `Matplotlib` & `Seaborn` (Statistical Data Visualization)

## Key Results
* **Accuracy:** 92.96%
* **R² Score:** 0.71
* **Evaluation:** The model was validated using a Confusion Matrix and a comprehensive Classification Report (Precision, Recall, F1-Score).

## Visualizations
The project includes several key analytical plots:
* **KDE Plots:** To visualize the density and distribution of Glucose and Blood Pressure.
* **Scatter Plots:** To observe the decision boundaries and class separation between features.
* **Confusion Matrix:** To track True Positives vs. False Positives.

## How to Run
1. Clone the repository:
   ```bash
   git clone [https://github.com/Sankalpa-01/your-repo-name.git](https://github.com/Sankalpa-01/your-repo-name.git)
   ```
2. Install dependencies:
   ```bash
   pip install pandas scikit-learn seaborn matplotlib
   ```
3. Run the analysis script or open the Jupyter Notebook.

## Dataset
The dataset Naive-Bayes-Classification-Data.csv contains:
glucose: Patient glucose levels.
bloodpressure: Patient blood pressure readings.
diabetes: Target variable (1 for Positive, 0 for Negative).
