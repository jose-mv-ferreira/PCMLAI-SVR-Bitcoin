# Datasheet Template

## Motivation

The dataset was created to enable the analysis and prediction of Bitcoin prices. The goal is to understand market trends and predict future values, providing valuable insights for investors and researchers. The source of the data was blockchain.com with their associated bitcoin variables over time exported in json format.

 
## Composition

- Data Instances: The dataset primarily represents historical data of Bitcoin, including daily price, trading volume, market capitalization, and other financial indicators.
- Volume: The dataset includes several thousand instances, each representing daily Bitcoin financial data and related metrics.
- Missing Data: Data was not available for all days, so forward fill and bacward fill was used for all metrics other than market price
- Confidentiality: The dataset does not contain confidential information. All data is aggregated and anonymized, focusing solely on market-driven metrics without personal or sensitive information.

## Collection process

- Data Acquisition: The data was acquired from publicly available graphs in blockchain.com
- Sampling: The data represents a comprehensive historical record, not a sample of a larger set.

## Preprocessing/cleaning/labelling

- Preprocessing and Cleaning: The data was cleaned to handle missing values, correct anomalies, and normalize the features. Specific preprocessing steps included filling missing values, standardizing date formats, and scaling numerical features.
- Labelling: No specific labelling was applied as the dataset is used for regression (predictive modeling) rather than classification.
 
## Uses

- Intended Uses: This dataset is intended for predictive modeling, specifically for forecasting Bitcoin prices. It's suited for time-series analysis, machine learning models, and financial market simulations.
- Unintended Uses: The dataset is not intended for identifying individual trading strategies, nor for making short-term trading decisions. The data should not be used as the sole basis for real-world investment decisions without expert advice.

## Distribution

- Dataset is publicly available

## Maintenance

- blockchain.com

