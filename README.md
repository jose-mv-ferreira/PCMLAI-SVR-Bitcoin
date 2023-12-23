# BITCOIN PRICE PREDICTION USING SVR


## NON-TECHNICAL EXPLANATION OF THE PROJECT
This project aims to develop a price prediction model for Bitcoin using SVR. It uses historical data for market price for Bitcoin as well as for a number of financial and Bitcoin specific metrics. Support Vector Regression (SVR) is closely related to Support Vector Machine (SVM); both are supervised learning methods developed from the same foundational principles. SVM is primarily used for classification tasks, whereas SVR is adapted for regression.

## DATA
The dataset comprises historical Bitcoin prices, including features like mining difficulty, trading volume, and other relevant associated indicators. This data was sourced from Blockchain https://www.blockchain.com/explorer/charts/difficulty, exported as JSON files.

## MODEL 
I employed Support Vector Regression (SVR), as after some research it appeared as well-suited for handling complex, non-linear data patterns often found in financial markets. SVR was chosen for its effectiveness in capturing intricate relationships in the data, providing reliable predictions under varying market conditions.

## HYPERPARAMETER OPTIMISATION
Hyperparameter optimisation involved fine-tuning SVR settings to enhance model performance. Techniques used include Grid Search and Random Search, each methodically exploring a range of parameters to identify the most optimal configuration for our SVR model. Given compute limitations we used the optimisation on a subset of the data set whihch might be improved by using the full data set instead.

## RESULTS
The optimized SVR model demonstrated promising results in predicting Bitcoin prices. Evaluation metrics like RMSE (Root Mean Squared Error) and MAE (Mean Absolute Error) indicated a high degree of accuracy. Additionally, cross-validation ensured the model's robustness and reliability in its predictions.

## CONTACT DETAILS
For more information or collaboration opportunities, feel free to connect with at: jose.mv.ferreira@gmail.com

