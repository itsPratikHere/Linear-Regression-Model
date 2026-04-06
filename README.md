# Linear-Regression-Model
Student Marks Predictor (Linear Regression)

🚀 Project Overview
This repository contains a Machine Learning project that predicts a student's Total Marks based on their performance in five core subjects. The project demonstrates a complete end-to-end data science pipeline, from Exploratory Data Analysis (EDA) to real-time prediction for unseen data.

📊 Key Highlights
Data Analysis: Utilized Seaborn and Matplotlib to analyze score distributions and identify patterns.

Preprocessing: Handled data cleaning, including dropping non-numeric features like Name and Grade to prepare for mathematical modeling.

Model: Implemented a Linear Regression model using Scikit-Learn.

Performance: Achieved a perfect 100% R2 Score and a Mean Absolute Error (MAE) of 0.0000, proving the model's ability to perfectly map subject scores to the total.

🛠️ Tech Stack

Language: Python 3.x

Libraries: Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn

Environment: Google Colab

📂 Repository Structure

LinearRegressionModel.ipynb: The main Jupyter Notebook containing the code.

student_marks_500.csv: The dataset containing 500 student records.

README.md: Project documentation.

📝 How to Use
Clone the Repo: ```bash
git clone https://www.google.com/search?q=https://github.com/YOUR_USERNAME/Student-Marks-Predictor.git

Run the Notebook: Open the .ipynb file in Colab or Jupyter.

Predict: Input a nested list of marks to the model:

model.predict([[Maths, Physics, Chemistry, English, Computer]])

💡 Results & Conclusion
The model successfully learned the additive relationship between individual subjects and the total score. This project serves as a robust baseline for understanding how Linear Regression identifies coefficients in structured datasets.
