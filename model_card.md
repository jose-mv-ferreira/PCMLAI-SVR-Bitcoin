# Model Card

Bitcoin Price Prediction Using SVR

## Model Description

**Input:** Historical data of Bitcoin including features like daily price, trading volume, market capitalization, and other financial indicators.

**Output:** Predicted future price of Bitcoin.

**Model Architecture:** Support Vector Regression (SVR) with optimized hyperparameters. The model uses a kernel (selected from RBF, polynomial, and linear) to map data into a higher-dimensional space, where a hyperplane is fitted for regression.

## Performance

The model's performance was evaluated using metrics like Root Mean Squared Error (RMSE), Mean Absolute Error (MAE), and R² (Coefficient of Determination). Cross-validation was employed to ensure robustness and generalizability. The model demonstrated high accuracy in predicting Bitcoin prices, with a strong R² value indicating a good fit to the data.

## Limitations

The model may not capture sudden, unpredictable market events or anomalies (e.g., drastic market crashes or spikes) due to its reliance on historical data patterns. The hyperparameter optimisation could also be improved by using more powerful compute resources. 

## Trade-offs

There is a trade-off between model complexity and interpretability. While the SVR model captures complex relationships in the data, it is less interpretable compared to simpler models. Additionally, the model's performance might vary with different kernel choices, impacting its suitability for various data scenarios.
