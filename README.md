
# Regression on California Housing Dataset

## Overview
This repository contains a regression analysis on the California housing dataset. The goal is to predict the median house value for California districts based on various features. Multiple regression models are implemented and evaluated for their performance.

## Dataset
This dataset was obtained from the StatLib repository. https://www.dcc.fc.up.pt/~ltorgo/Regression/cal_housing.html

This dataset was derived from the 1990 U.S. census, using one row per census block group. A block group is the smallest geographical unit for which the U.S. Census Bureau publishes sample data (a block group typically has a population of 600 to 3,000 people).

It can be downloaded/loaded using the sklearn.datasets.fetch_california_housing function.

California Housing Dataset in Sklearn Documentation 20640 samples 8 Input Features: MedInc median income in block group HouseAge median house age in block group AveRooms average number of rooms per household AveBedrms average number of bedrooms per household Population block group population AveOccup average number of household members Latitude block group latitude Longitude block group longitude Target: Median house value for California districts, expressed in hundreds of thousands of dollars ($100,000)

## Models
1. **Decision Tree Regression:** A decision tree model that can capture complex relationships in the data.

2. **Random Forest Regression:** An ensemble of decision trees to improve overall predictive performance.

3. **AdaBoost Regression:** Boosting algorithm that adapts to the weaknesses of individual models.

4. **Voting Regressor:** A regression ensemble method that combines predictions from multiple base models.

## Language / Libraries

Language: Python

Packages: Sklearn

## Usage

The code is built on Google Colab on an iPython Notebook.

```bash
Download the repository, upload the notebook and dataset on colab, and execute!
```
## Result

The performance of each model is evaluated using metrics such as mean squared error, mean absolute error, and R-squared. 
| Technique        | R2 Score         | MSE error  |
| ------------- | ------------- |------------- |
| Decision Tree     |0.65         | 0.45              |
| Random Forest          | 0.80        |       0.25           |
| Voting Regressor          | 0.77       |      0.29         |
| Ada Boost           | 0.38       |      0.81           |


Conclusion from Observations:

Random Forest Regressor predicts the best r2score of 0.80

## License

[MIT](https://choosealicense.com/licenses/mit/)
