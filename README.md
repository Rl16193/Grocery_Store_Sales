# Grocery_Store_Sales
Predict Store Sales

## Aim of the Study

The primary aim of this study is to develop a robust forecasting model that accurately predicts unit sales for a wide range of products across multiple Favorita stores. By applying machine learning techniques to the provided dataset, the goal is to refine the ability to forecast sales with greater precision. This will enable better inventory management, reduce the risks associated with overstocking or understocking, and ultimately enhance customer satisfaction by ensuring the availability of desired products. Success in this endeavor could also contribute to reducing food waste and optimizing operational efficiency in grocery retail.

## Methodology

Utilized Python and its libraries—pandas and scikit-learn—to efficiently extract, transform, and load data into machine learning models. The primary objective was to evaluate the accuracy of various regression models and assess their performance by analyzing negative sales predictions as a secondary measure.

The data preprocessing involved several key transformations:

1. Datatype Conversion: Standardized date-time formats and other data types.
2. Dataset Integration: Merged multiple datasets to create a comprehensive dataset.
3. Data Cleaning: Addressed missing values by removing or imputing them.
4. Categorical Encoding: Applied encoding techniques to convert categorical variables into numerical format.
5. Model Fitting: Prepared the data for machine learning algorithms.

For model evaluation, the following regression models were compared:

1. Random Forest Regressor
2. LightGBM Regressor
3. XGBoost Regressor
The analysis aimed to determine which model offered the best accuracy and how each model handled predictions of negative sales values.

## Algorithm Performance

1. LightGBM achieved a Mean Squared Logarithmic Error (MSLE) of 2.88 and produced the highest percentage of negative predictions at 26.2%. This indicates that while LightGBM was effective in terms of the MSLE metric, it had a notable tendency to predict negative values.

2. XGBoost yielded a higher MSLE of 8.45 but demonstrated the lowest percentage of negative predictions, approximately 0%. This suggests that although XGBoost had a higher MSLE, it was effective in minimizing negative value predictions.

3. The Random Forest Regressor delivered satisfactory results overall, balancing accuracy and handling of negative values effectively. Its performance was competitive, though specific metrics should be reviewed for a comprehensive assessment.
