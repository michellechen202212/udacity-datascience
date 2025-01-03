## **Overview**
This project analyzes and predicts business growth using the [Business Formation Statistics Weekly Data](https://github.com/michellechen202212/udacity-datascience/blob/main/bfs_us_apps_weekly_nsa.csv) from the U.S. Census Bureau. By leveraging the CRISP-DM framework, the project explores trends, identifies key features, and evaluates predictive modeling for actionable insights. The accompanying blog post presents the findings in a non-technical format.

### **Blog Post**
Read the complete story on Medium:  
[Predicting Business Growth: Which Model Does It Best?](https://medium.com/@isabelladatascience/predicting-business-growth-which-model-does-it-best-c152f151d26f)

### **GitHub Repository**
Find all project resources on GitHub:  
- [Jupyter Notebook](https://github.com/michellechen202212/udacity-datascience/blob/main/blog_post.ipynb)  
- [Dataset](https://github.com/michellechen202212/udacity-datascience/blob/main/bfs_us_apps_weekly_nsa.csv)

## **Motivation**
This project highlights the importance of understanding business application trends to guide policymakers, economists, and entrepreneurs. The key objectives are to:
1. Identify significant features influencing business growth.
2. Predict future trends using machine learning models.
3. Assess model accuracy and applicability to real-world scenarios.

## **Dataset**
**Business Formation Statistics Weekly Data**  
- **Source**: [U.S. Census Bureau](https://www.census.gov/econ/bfs/data/weekly.html)  
- **Features**: Includes variables like `BA_NSA` (Business Applications), `HBA_NSA` (High-Propensity Applications), `WBA_NSA` (Applications with Planned Wages), and `Year`.

## **Methodology**
The analysis adheres to the **CRISP-DM framework**:
1. **Business Understanding**: Explore feature importance, accuracy, and hypothetical predictions.
2. **Data Understanding**: Investigate trends and highlight dominant features.
3. **Data Preparation**: Handle missing values and engineer relevant features.
4. **Modeling**: Compare the performance of Linear Regression and Random Forest.
5. **Evaluation**: Use metrics like MAE and \(R^2\) to assess model effectiveness.
6. **Deployment**: Communicate findings via visualizations and a blog post.

## **Key Highlights**
1. **Feature Importance**:  
   - `HBA_NSA` and `Year` emerged as the most influential predictors of business activity.
2. **Modeling Insights**:  
   - **Linear Regression**: Achieved the highest \(R^2\) score, making it effective for straightforward relationships.  
   - **Random Forest**: Demonstrated superior performance in capturing non-linear interactions and provided conservative predictions, making it suitable for strategic decision-making.  
3. **Visualization**:  
   - Included feature importance plots, a correlation matrix, and a comparison of actual vs. predicted values for both models.  
4. **Creative Predictive Scenario**:  
   - Explored the impact of a 20% increase in `HBA_NSA`, highlighting Linear Regression's sensitivity and Random Forest's robustness in real-world dynamics.

This project bridges the gap between technical analysis and real-world applications, offering valuable insights for data-driven decision-making.

