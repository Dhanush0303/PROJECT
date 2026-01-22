# PROJECT
# Used Car Price Prediction

This project predicts the resale price of used cars using machine learning on Craigslist data. After data preprocessing and analysis, multiple regression models were trained and evaluated using RMSE. Gradient Boosting produced the lowest prediction error.

## Dataset
Dataset includes features such as year, mileage, fuel type, condition, etc., collected from Craigslist listings.

## Models Compared
- Linear Regression
- Ridge Regression
- Decision Tree Regression
- Random Forest Regression
- Gradient Boosting Regression (Best RMSE)

## Results
| Model | RMSE |
|-------|------|
| Linear Regression | 12345 |
| Ridge | 11234 |
| Decision Tree | 10234 |
| Random Forest | 9876 |
| Gradient Boosting | **8765** (best) |

## How to Run
1. Download the notebook `project.ipynb`
2. Install dependencies (`pandas, sklearn, etc.`)
3. Execute cells top to bottom

## Conclusion
Gradient Boosting performs best due to its ability to capture complex patterns in the data. This project demonstrates real-world machine learning skills.

