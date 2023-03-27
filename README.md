# Shipping

The SCMS Delivery History Dataset is a dataset containing information about the procurement, shipment, and delivery of health products (such as medicines, vaccines, and medical supplies) from suppliers to end-users in low- and middle-income countries. The dataset is published by the Supply Chain Management System (SCMS), which is a partnership of multiple organizations including the United States Agency for International Development (USAID) and the Global Fund to Fight AIDS, Tuberculosis and Malaria.

The dataset contains detailed information about each delivery, including the product code, the date and location of the shipment, the quantity of the product shipped, the price per unit, and the type of shipment (e.g. air or sea). It also includes information about the delivery partner (i.e. the organization responsible for delivering the products to the end-user), the end-user facility (e.g. a hospital or clinic), and the funding source for the delivery.

The dataset is valuable for understanding the challenges and complexities involved in delivering health products to low- and middle-income countries, as well as for analyzing trends and identifying areas for improvement in the global health supply chain.


Here's a brief overview of the four regression models used in our analysis:

Linear Regression: Linear regression is a simple yet powerful regression algorithm that assumes a linear relationship between the input features and the output variable. It estimates the coefficients of the linear equation that best predicts the output variable based on the input features.

Gradient Boosted Tree Regressor: Gradient boosting is an ensemble method that combines multiple decision trees to improve prediction accuracy. The algorithm builds a series of decision trees, with each subsequent tree learning from the errors of the previous tree. Gradient boosted trees are known for their ability to handle non-linear relationships and high-dimensional datasets.

Decision Tree Regressor: Decision tree regression is a non-parametric algorithm that builds a regression model as a tree structure. It recursively splits the data into smaller and smaller subsets, using the features that best separate the data based on their target values. The final result is a tree with decision nodes and leaf nodes, where the leaf nodes represent the predicted values.

Random Forest Regressor: Random forest regression is another ensemble method that combines multiple decision trees. However, instead of building a single decision tree, random forest builds a collection of decision trees and averages their predictions. Random forest is known for its ability to handle noisy and unbalanced datasets, and for its resistance to overfitting.

Each of these regression models has its own strengths and weaknesses, and the best model for a given dataset depends on various factors such as the size and complexity of the dataset, the distribution of the target variable, and the specific problem being addressed. In our analysis, we used these models to compare their performance in predicting delivery costs based on the features in the SCMS Delivery History Dataset.
