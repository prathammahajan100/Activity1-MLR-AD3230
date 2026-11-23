# Activity 1: Multiple Linear Regression (California Housing)

**Course:** Regression and Classification Algorithms (T.Y. B.Tech AI & DS, Sem V), CIE 2, Unit I
**Name / Roll No.:** Pratham Mahajan, Roll No. AD3230
**GitHub:** [complexiota](https://github.com/complexiota)

## Activity
Predict the median house value of a California neighbourhood from several numeric features using multiple linear regression, including a manual normal-equation calculation, comparison with a single-feature model, coefficient interpretation, residual analysis and VIF.

## Dataset
California Housing (1990 US Census), via `sklearn.datasets.fetch_california_housing`. Source: https://scikit-learn.org/stable/datasets/real_world.html#california-housing-dataset
Target: `MedHouseVal` ($100,000s). Features: MedInc, HouseAge, AveRooms, AveBedrms, Population, AveOccup.

## Work completed
- Data inspection and cleaning (outliers removed, decisions logged)
- Scatter plots and correlation heatmap
- Manual calculation of b = (XᵀX)⁻¹Xᵀy on 6 rows, verified with scikit-learn
- Single-feature baseline vs multiple regression (80:20 split, seed 42)
- MAE, MSE, RMSE, R², adjusted R², residual plots, predicted-vs-actual plot, VIF
- New prediction, limitations and decision log

## Key results
(Fill in after running: test RMSE, R², adjusted R² for both models, strongest feature, VIF findings.)

## Files
- `Activity1_Multiple_Linear_Regression.ipynb`: full notebook
- `manual_worksheet.pdf` (or photo): hand calculation
