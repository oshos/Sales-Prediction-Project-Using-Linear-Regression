# Sales Prediction Using Linear Regression

## Project Overview
This project focuses on building a **linear regression model** to predict product sales based on advertising expenditure across different marketing channels. The goal is to understand how TV, Radio, and Newspaper advertising impact sales and to provide data-driven insights for better marketing budget allocation.

---

## Problem Statement
Can we accurately predict product sales using advertising spend across multiple media channels?

Businesses invest heavily in advertising, and understanding which channels drive sales the most is critical for maximizing return on investment (ROI). This project addresses that problem using linear regression.

---

## Dataset
The dataset used is the **Advertising dataset**, which contains 200 observations and the following features:

| Feature     | Description |
|------------|-------------|
| TV         | TV advertising spend |
| Radio      | Radio advertising spend |
| Newspaper  | Newspaper advertising spend |
| Sales      | Product sales (target variable) |

All variables are numeric, and the dataset contains no missing values.

You can find the dataset at https://www.kaggle.com/datasets/tawfikelmetwally/advertising-dataset

---

## Tools & Technologies
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

## Exploratory Data Analysis (EDA)
Key insights from EDA include:
- **TV advertising** shows a strong positive linear relationship with sales.
- **Radio advertising** also has a significant positive impact.
- **Newspaper advertising** exhibits a weak relationship with sales.

Correlation analysis and scatter plots were used to visualize these relationships.

---

## Model Building
- Model Used: **Linear Regression**
- Features: TV, Radio, Newspaper
- Target Variable: Sales
- Data Split: 80% training, 20% testing

---

## Model Evaluation
The model was evaluated using standard regression metrics:

- **R² Score:** 0.90  
- **MAE:** Low average prediction error  
- **RMSE:** Indicates good predictive accuracy  

An R² score of 0.90 means that the model explains **90% of the variance in sales**, indicating strong performance.

---

## Model Interpretation
- **Radio advertising** has the largest coefficient, suggesting it has the strongest marginal impact on sales.
- **TV advertising** also contributes positively to sales.
- **Newspaper advertising** contributes minimally, aligning with insights from EDA.

Residual analysis and actual vs predicted plots confirm that the model assumptions are reasonably satisfied.

---

## Business Insights & Recommendations
- Increase investment in **Radio and TV advertising** to maximize sales impact.
- Re-evaluate spending on **Newspaper advertising**, as it shows minimal contribution.
- The model can be used as a decision-support tool for marketing budget allocation and sales forecasting.

---

## Conclusion
This project demonstrates how linear regression can be applied to solve a real-world business problem. By combining data analysis, visualization, model building, and interpretation, the project highlights the importance of data-driven decision-making in marketing analytics.

---

## Repository Structure
sales-prediction-linear-regression/
│── sales_prediction_linear_regression.ipynb
│── Advertising.csv
│── README.md

## Author
**Oshomoshiofu Precious Alabi**  
Aspiring Data Scientist  
