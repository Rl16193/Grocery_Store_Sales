# Grocery_Store_Sales


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

![image](https://github.com/user-attachments/assets/65f5d874-4ecc-4988-930c-d9d1496fe5ad)

2. XGBoost yielded a higher MSLE of 8.45 but demonstrated the lowest percentage of negative predictions, approximately 0%. This suggests that although XGBoost had a higher MSLE, it was effective in minimizing negative value predictions.

![image](https://github.com/user-attachments/assets/7290440d-cc80-4c09-ad79-7e24e1ecc0ba)

3. The Random Forest Regressor delivered satisfactory results overall, balancing accuracy and handling of negative values effectively. Its performance was competitive, though specific metrics should be reviewed for a comprehensive assessment.

![image](https://github.com/user-attachments/assets/148f0947-2a32-4897-9a8c-1d58da7662a5)

## Results

Develop Power BI dashboards to highlight the impact of oil prices, promotions, and holidays on store sales. The dashboards also include an analysis of sales distribution to provide insights into how these factors influence sales patterns.

1. December recorded the highest sales, with a 21% increase compared to other months. This spike can be attributed to the numerous national, regional, and local holidays during the month. However, establishing a clear relationship between sales and oil prices is challenging, as average oil prices in December are relatively high. Conversely, April, which had the lowest average oil prices, experienced the third-lowest sales.

   ![image](https://github.com/user-attachments/assets/95a4fe18-7d7e-4f29-b6d0-d7c2a232418f)

2. The grocery subdivision, specifically fresh foods, accounted for the largest share of sales, representing 38% of the total. Additionally, sales increased by 19% on weekends, highlighting a significant boost in average sales during these days.

![image](https://github.com/user-attachments/assets/69c08062-3efc-4379-98fe-315471cbdcc7)

3. The predicted sales for August 2017 are significantly lower compared to August 2013, with a reduction of 200% in total overall sales.

![image](https://github.com/user-attachments/assets/5582adc6-56d8-4191-9d31-c6a8ed1cdd92)

   
