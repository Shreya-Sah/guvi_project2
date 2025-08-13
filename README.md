#  Student Score Prediction – GUVI Project 2

---

##  Table of Contents
- [Project Overview](#project-overview)  
- [Files in the Repository](#files-in-the-repository)  
- [Technologies Used](#technologies-used)  
- [Model Development Workflow](#model-development-workflow)  
- [Excel Dashboard Features](#excel-dashboard-features)  
- [How to Use](#how-to-use)  
- [Model Performance](#model-performance)  
- [Ethical & Bias Awareness](#ethical--bias-awareness)  
- [Author](#author)  

---

## Project Overview  
Predict a student's **Final Score** using **Hours Studied** and **Attendance Percentage**.  
The workflow includes data preprocessing, training a **Linear Regression** model, evaluating its accuracy, and building an interactive **Excel dashboard**.

---

## Files in the Repository  
| File Name                | Description |
|--------------------------|-------------|
| `guvi_project2.ipynb`    | Python notebook (Colab/Jupyter) for data cleaning, visualization, model building, evaluation. |
| `student_scores.csv`     | Dataset containing columns: Hours Studied, Attendance, Final Score. |
| `student_dashboard.xlsx` | Interactive Excel dashboard with charts, dropdowns, prediction formula, and formatting. |
| `README.md`              | This documentation file. |

---

## Technologies Used
- **Python Packages**: pandas, numpy, matplotlib, seaborn, scikit-learn  
- **Excel Tools**: Data Validation (dropdowns), Scatter Charts, Trendlines, Conditional Formatting, Formulas  

---

## Model Development Workflow
1. **Load & Clean Data**  
   - Import `student_scores.csv` using pandas and handle missing values.  
2. **Exploratory Data Analysis**  
   - Visualized relationships using `pairplot`.  
3. **Train Linear Regression Model**  
   - Feature inputs: Hours Studied, Attendance.  
4. **Evaluate**  
   - Metrics: R² (goodness of fit), MAE (average error).  
5. **Make Prediction**  
   - Test with custom inputs and display predicted score.

---

## Excel Dashboard Features
- Two **Scatter Plots**:
  - *Hours Studied vs Final Score*  
  - *Attendance vs Final Score*  
- **Trendlines** with equations and R² values.  
- **Dropdown menus** to select Hours & Attendance.  
- **Automatic Prediction** updates using model formula.  
- **Conditional Formatting** to highlight low scores or attendance.  
- Transparent **1-line note** about model limitations.

---

## How to Use
1. Open `guvi_project2.ipynb` in Colab or Jupyter; run all cells to build and evaluate the model.  
2. Open `student_dashboard.xlsx` in Excel:  
   - Choose values from dropdowns in I2/I3.  
   - Prediction updates automatically in I4.  
   - View charts and model accuracy metrics.

---

## Model Performance
- **R² Score**: Indicates how well inputs explain the variance in final scores.  
- **Mean Absolute Error (MAE)**: Shows average prediction error in points.

*(Insert actual values from your model here)*

---

## Ethical & Bias Awareness
This model is built on a **limited dataset** and may not generalize to all student populations. Real-world factors (e.g., motivation, environment, personal background) are not included. Use predictions as **approximations only**.

---

## Author
**Shreya Sah**  
GitHub: [Shreya-Sah](https://github.com/Shreya-Sah)  
Feel free to reach out for questions or feedback!  
