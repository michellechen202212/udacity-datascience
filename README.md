## Overview
This project focuses on analyzing and predicting business growth using the **Business Formation Statistics Weekly Data** provided by the U.S. Census Bureau. The analysis follows the CRISP-DM framework, answering key questions about data trends, feature importance, and predictive modeling. The blog post accompanying this project provides a non-technical summary of findings.

### Blog Post
Read the full story and insights on Medium:  
[Predicting Business Growth: Which Model Does It Best?](https://medium.com/@isabelladatascience/predicting-business-growth-which-model-does-it-best-c152f151d26f)

### GitHub Repository
Find the complete project, including the code and dataset, on GitHub:  
[Jupyter notebook](https://github.com/michellechen202212/udacity-datascience/blob/main/blog_post.ipynb)

[Dataset](https://github.com/michellechen202212/udacity-datascience/blob/main/bfs_us_apps_weekly_nsa.csv)


---

## Motivation
Understanding the dynamics of business applications is vital for economists, policymakers, and entrepreneurs. This project:
1. Identifies the most important features driving business growth.
2. Uses predictive modeling to analyze future trends.
3. Evaluates the performance of various machine learning models.

---

## Dataset
**Business Formation Statistics Weekly Data**  
- Source: [U.S. Census Bureau](https://www.census.gov/econ/bfs/data/weekly.html)
- Key Variables: `BA_NSA`, `HBA_NSA`, `WBA_NSA`, `Year`, etc.

---

## Methodology
The project follows the **CRISP-DM framework**:
1. **Business Understanding**:
   - Key questions addressed include feature importance and predictive accuracy.
2. **Data Understanding**:
   - Data exploration and visualization to understand trends.
3. **Data Preparation**:
   - Handling missing values and feature engineering.
4. **Modeling**:
   - Comparing Linear Regression and Random Forest.
5. **Evaluation**:
   - Metrics such as MAE and \( R^2 \) are used to evaluate model performance.
6. **Deployment**:
   - Insights are shared via a blog post.

---

## Project Highlights
1. **Data Analysis**:
   - Identified `HBA_NSA` and `Year` as the most influential features.
2. **Modeling Results**:
   - Linear Regression performed best with a high \( R^2 \) score, effectively explaining variance in the target variable.
3. **Visualizations**:
   - Actionable insights were derived from the correlation matrix and feature importance plots, alongside a comparison of actual vs. predicted values using linear regression and random forest models.

