# Sales Prediction Using Advertising Data 📈

## Overview

This project focuses on predicting sales based on advertising spend across three channels: TV, radio, and newspaper. The analysis explores the relationship between advertising budgets and sales, demonstrating the process of data preprocessing, visualization, model building, and evaluation. By leveraging machine learning models, this project aims to provide insights into the most effective advertising channels for driving sales.

## Dataset Information

The dataset includes 200 records with the following features:

- **TV**: Budget spent on TV advertising (in thousands of dollars)
- **Radio**: Budget spent on radio advertising (in thousands of dollars)
- **Newspaper**: Budget spent on newspaper advertising (in thousands of dollars)
- **Sales**: Target variable representing sales (in thousands of dollars)

This dataset is ideal for understanding how advertising investments in different media channels correlate with sales.

###  Data Preprocessing

- Checked for missing values and handled any inconsistencies to ensure data quality.
- Standardized the data to improve model performance.

###  Exploratory Data Analysis (EDA)

- **Pair Plot**: Visualized pairwise relationships between features to understand their distributions and relationships with sales.
- **Correlation Matrix**: Displayed the correlation between features and the target variable to identify strong predictors of sales.

###  Splitting the Data

- Divided the dataset into training and testing sets using an 80-20 split.
- A fixed `random_state` was used to ensure reproducibility.

###  Model Building

- Multiple regression models were tested to compare their performance:
    - **Decision Tree Regressor**
    - **Random Forest Regressor**

###  Model Evaluation

- Models were evaluated based on the R² score to measure the proportion of variance explained by each model and by mean absolute error
#### Visualization of model results
    - **Scatter Plots**: Displayed actual vs. predicted sales for each model to assess their predictive power visually.
    - **Bar Chart**: Compared the R² scores of each model to identify the best-performing model.

###  Results

- **Random Forest Regressor**: Achieved an R² score of 0.98, indicating strong predictive accuracy.
- **Decision Tree Regressor**: Achieved an R² score of 0.94, showing good performance but slightly lower than Random Forest.

## Conclusion

This project highlights the effectiveness of machine learning in predicting sales from advertising spend data. Random Forest emerged as the most accurate model, likely due to its ability to capture complex interactions between features. This analysis provides a foundation for understanding which advertising channels may yield the highest returns.


## Requirements

Install the necessary libraries using pip:
```
pip install pandas numpy matplotlib seaborn scikit-learn

```

