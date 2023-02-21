CA03 – Decision Tree Algorithm
-----------------------------------------

To estimate a person's income category based on their demographic data, a Decision Tree Classifier model is being built for this project. The Census Bureau provided the seven demographic characteristics that were used in this project's data. There are 7 columns and 48,842 rows in the dataset. The target variable is the income category, which has the classifications ">50K" and "=50K."

------------------------------------------
Data Source and Contents

The dataset is obtained from the Census Bureau and represents salaries of people along with seven demographic variables. The following is a description of our dataset:

Number of target classes: 2 ('>50K' and '<=50K') [ Labels: 1, 0 ]
Number of attributes (Columns): 7
Number of instances (Rows): 48,842

Data Source: Use the following exact “path” in your code as the data source: "https://github.com/ArinB/MSBA-CA-03-Decision-Trees/blob/master/census_data.csv?raw=true".

------------------------------------------

Use scikit learn's "DecisionTreeClassifier" algorithm. Details about the sklearn tree algorithm can be found below. Scitkit Learn uses an optimized version of the CART algorithm and can be used for both binary and multi-class classifications. It can be used for both classification and regression. Examine the following link thoroughly, especially Section 1.10.5. (Tips on Practical Use).

https://scikit-learn.org/stable/modules/tree.html#tree-algorithms-id3-c4-5-c5-0-and-cart
