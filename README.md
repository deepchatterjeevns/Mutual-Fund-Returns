# Mutual Fund Returns
 
## Problem Statement
The data given is of the mutual funds in the USA. The objective of this problem is to predict the ‘basis point spread’ over AAA bonds i.e. feature ‘bonds_aaa’ against each Serial Number. Basis Point Spread indicates the additional return a mutual fund would give over the AAA-rated bonds.

### Model Accuracies
| S.NO. |            MODEL            | rmse-Score |
|--- | --- | --- |
|   1   |      Linear Regression      |   16.05    |
|   2   |       Ridge Regression      |   16.06    |
|   3   | Hypertuned Ridge Regression |   16.06    |
|   4   |       Lasso Regression      |   20.04    |
|   5   | Hypertuned Lasso Regression |   16.07    |

### Technologies:
- Programming Language: Python
- Libraries: Pandas, Numpy, Scikit-learn, Matplotlib, Seaborn

### TO Do
- Feature Enginnering and use of more models to bring down the rmse further.

### Acknowledment
- Thank you [GreyAtom](https://greyatom.com/) for the guidance and dataset.