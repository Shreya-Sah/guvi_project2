📊 Student Score Prediction – GUVI Project 2
📌 Project Overview
This project predicts a student’s Final Score based on:

Hours Studied

Attendance Percentage

The workflow involves data preprocessing, building a Linear Regression model, evaluating its accuracy, and creating an interactive Excel dashboard where users can select values from dropdown menus to see predicted scores.

| File Name                   | Description                                                                                                    |
| --------------------------- | -------------------------------------------------------------------------------------------------------------- |
| **Guvi\_project2.ipynb**    | Jupyter/Colab notebook containing data loading, cleaning, visualization, model training, and evaluation.       |
| **student\_scores.csv**     | Dataset containing Hours Studied, Attendance (%), and Final Scores.                                            |
| **student\_dashboard.xlsx** | Interactive Excel dashboard with scatter plots, trendlines, dropdown inputs, and automatic prediction updates. |
| **README.md**               | Project documentation.                                                                                         |

🛠️ Technologies Used
Python (pandas, numpy, matplotlib, seaborn, scikit-learn)

Excel (Data Validation, Scatter Plots, Trendlines, Conditional Formatting)

Linear Regression for prediction

📈 Model Development Steps
Data Import & Cleaning

Used pandas to load student_scores.csv

Removed missing values if any

Exploratory Data Analysis

Scatter plots and pair plots to observe relationships between variables

Model Training

Used LinearRegression from scikit-learn

Features: Hours Studied & Attendance (%)

Target: Final Score

Evaluation Metrics

R² Score: Measures how well the model fits the data

MAE (Mean Absolute Error): Measures average prediction error

📊 Excel Dashboard Features
Two scatter plots:

Hours Studied vs Final Score

Attendance vs Final Score

Trendlines with R² values displayed

Dropdown menus to choose Hours Studied & Attendance %

Automatic predicted score update in the dashboard

Conditional formatting for better visualization

Ethical note: Model is based on limited sample data and may not reflect all real-world scenarios

🚀 How to Use
1️⃣ Run the Model in Google Colab / Jupyter Notebook
Open Guvi_project2.ipynb

Run all cells to see data preprocessing, model training, and accuracy results

2️⃣ Use the Excel Dashboard
Open student_dashboard.xlsx

Select values for Hours Studied and Attendance % from the dropdown menus

The Predicted Score will update automatically

View scatter plots and model accuracy (R² score)

📌 Ethical & Bias Awareness
This model is trained on a small dataset and may not generalize to all student populations.
Factors like study environment, mental health, and teaching quality are not considered.
Predictions should be used as approximations only.

👩‍💻 Author
Shreya Sah
🔗 GitHub: Shreya-Sah

