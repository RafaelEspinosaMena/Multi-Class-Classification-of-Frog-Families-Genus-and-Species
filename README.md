# Multi-Class Classification of Frog Families, Genus and Species

## Overview

This notebook focuses on multi-class and multi-label classification of frog species, families, and genus, employing a range of machine learning techniques to analyze and classify biological data.

## Method

1) Decision Trees as Interpretable Models

Begins with an exploration of decision trees as a tool for model interpretability. This includes constructing a decision tree for the entire dataset, transforming decision rules into simple IF/THEN statements, and using cost-complexity pruning for optimization.

2) LASSO and Boosting for Regression

The second part focuses on regression models. It starts with data preparation steps such as data splitting and imputation of missing values, followed by a detailed correlation analysis.
The notebook then identifies key features using the coefficient of variation, visualizing them through scatter and box plots. These plots reveal significant relationships among the features, particularly highlighting the role of population in the dataset.
Several regression techniques are applied and compared, including linear regression, ridge regression, LASSO regression (both standardized and unstandardized), PCR model optimization through CV, and L1-penalized gradient boosting tree.

## Conclusion

The models achieve a test MSE of around 0.017, with the L1-Penalized Gradient Boosting Tree showing slightly better performance. However, this method is noted for its longer training time compared to other models like LASSO.
The notebook concludes with insights on model selection, emphasizing the balance between training time and performance improvement, and noting technical aspects of using XGBoost with pandas.
