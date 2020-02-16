# House-Price
In here there are two house price problem.One is house house-price and another is Housing.In house-price problem the dataset is kc_house_data.

1 . Data Preprocessing. 

2 . Exploratory Data Analysis

3 . Building Model(Linear Regression and Decision Tree)


# Housing

**Problem Statement**
Consider a real estate company that has a dataset containing the prices of properties in the some region. It wishes to use the data to optimise the sale prices of the properties based on important factors such as area, bedrooms, parking, etc.


**Dataset**
Dataset is provided here,also it can be find in Kaggle.


**Data Preparation**
- Converting binary categorical value into 0 and 1.
- Checking the pairplot
- Check the co-relation matrix
- Normalized the data


**Building Model**
- Using statmodels find the negetively corelated features
- Also use VIF to find the multicolinearity.
- Checking both VIF and statmodels and delete some columns
- When deleting check the corelation matrix
- Check the final model and visualize the error term
