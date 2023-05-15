# Regression and Logistic Regression Analysis

This project focuses on performing regression and logistic regression analyses using the datasets "sales.csv" and "customer.csv". The goal is to predict total sales for a new area based on sales from three areas and predict customer purchase behavior.

## Dataset

The project utilizes two datasets:

1. `sales.csv`: This dataset contains information about sales from three different areas. It includes variables such as area sales, interaction effects, and the total sales. The dataset should be downloaded before running the analysis.

2. `customer.csv`: This dataset includes customer information, such as demographic data and purchase behavior. It will be used to train logistic regression models to predict whether a customer will purchase the product.

## Prerequisites

To run the analysis code, you need to have the following dependencies installed:

- Python 3 (https://www.python.org/)
- pandas (https://pandas.pydata.org/)
- numpy (https://numpy.org/)
- statsmodels (https://www.statsmodels.org/stable/index.html)
- scikit-learn (https://scikit-learn.org/stable/)

You can install the required Python packages by running the following command:

pip install pandas numpy statsmodels scikit-learn


## Analysis Steps

This project consists of several analysis tasks:

1. Interactions in Linear Regression:
   - The code will load the `sales.csv` dataset.
   - It will perform linear regression analysis to predict total sales for a new area.
   - The effects of interactions, if any, on the linear regression model will be examined.
   - The results will provide insights into the impact of interactions on the prediction of total sales.

2. Full and Trimmed Logistic Regression Models:
   - The code will load the `customer.csv` dataset.
   - It will develop a full logistic regression model to predict customer purchases.
   - Additionally, trimmed logistic regression models will be trained by selecting relevant features from the data.
   - The "in-sample R2" (pseudo R-squared) metric will be computed for each model, allowing for model comparison.

3. Interpretation of Logistic Regression Coefficients:
   - Among the logistic regression models trained, the best model based on in-sample R2 will be selected.
   - The coefficients of the chosen model will be interpreted to understand their effects.
   - The interpretation will involve analyzing the impact of positive and negative coefficients on the model's predictions.

4. Evaluating Accuracy as a Metric:
   - The project will discuss whether accuracy is a suitable metric for judging the logistic regression models.
   - Reasons and alternatives for assessing model performance will be provided to support the answer.

5. Plotting Interactions of Features:
   - The interactions between the "Age" and "Gender" features with the "Purchased" output will be plotted.
   - The code will generate visualizations to illustrate how these interactions impact the likelihood of a purchase.

6. Effect of Interaction Terms on Likelihood of Buying a House:
   - The project will analyze three plots ("a," "b," and "c") showing the effects of income and change in savings on the likelihood of buying a house.
   - For each plot, the question of whether the regression equation should include interaction terms (between income and average savings) will be answered.
   - Reasoning will be provided to justify the decision to include or exclude the interaction terms.

Please refer to the code files and comments within the project repository for more detailed implementation.

## Conclusion

This project encompasses regression and logistic regression analyses, aiming to predict total sales and customer purchase behavior. Through interactions in linear regression, full and trimmed logistic regression models, interpretation of coefficients, evaluation of metrics, and visualization of interactions,
