# Housing Prize prediction linear regression 

## Tools and Libraries Used
- **Python**: Programming language used for implementing the solution.
- **Scikit-learn**: For implementing linear regression models and metrics evaluation.
- **Pandas**: Data manipulation and cleaning.
- **Matplotlib**: For visualizing the data and results.
- **Seaborn**: For pairwise plotting and visualization of correlations between features.

## Approach

### 1. **Data Preprocessing**
The dataset was loaded and analyzed to identify the key features that contribute to the house price prediction. We used the `pandas` library to perform data cleaning and splitting into training and testing sets.

### 2. **Simple Linear Regression**
- A **simple linear regression** model was built using **area** as the independent variable and **price** as the dependent variable.
- The model was trained on the training set, and predictions were made on the test set.
- A **scatter plot** was created to show the relationship between area and price, with the regression line overlaid on the training data.

### 3. **Multiple Linear Regression**
- A **multiple linear regression** model was built using **area**, **number of rooms**, and **age** as the independent variables to predict **price**.
- The model was trained on the training set, and predictions were made on the test set.
- Two visualizations were created:
  - A **residual plot** to check the assumptions of the regression model.
  - A **predicted vs. actual values plot** to evaluate how well the model predicted the house prices.
  
### 4. **Data Visualization**
Visualizations were created to explore and understand the relationships between the features and the target variable (house price):
- **Residuals vs Fitted Values**: To assess if the residuals have constant variance and check the linearity assumption.
- **Predicted vs Actual Values**: To evaluate the performance of the regression model.
- **Pairwise Plot**: To understand how the independent features (area, number of rooms, and age) relate to each other and the house price.

## Conclusion
Through this project, we implemented both **simple** and **multiple linear regression** models to predict house prices based on available features. The evaluation metrics and visualizations provided insights into the performance of the models, including how well the independent features explain the variation in house prices.

---

This README gives a concise overview of the project and its purpose. Let me know if you'd like to add or modify anything!
