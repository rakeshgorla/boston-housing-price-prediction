# boston-housing-price-prediction
# Boston Housing Price Prediction

## Dataset Description:
This project uses the **Boston Housing Dataset**, which contains information about various features of houses in Boston, such as crime rate, number of rooms, property tax rate, and more. The target variable is the median value of owner-occupied homes.

## Preprocessing Steps:
1. Loaded the dataset using Scikit-learn.
2. Checked and handled missing values (none were present).
3. Normalized the feature values using `StandardScaler`.
4. Split the data into training (80%) and testing (20%) sets.

## Models Used and Evaluation:
- **Model:** Linear Regression
- **Evaluation Metrics:**
  - **Mean Absolute Error (MAE):** ~3.19
  - **Root Mean Squared Error (RMSE):** ~4.93
- A scatter plot of actual vs predicted prices is used to visualize model performance.

## How to Run:
1. Ensure you have Python installed with the following libraries:
   - scikit-learn
   - pandas
   - matplotlib
   - numpy

2. Run the script:
```bash
python boston_price_prediction.py

