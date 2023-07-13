# Taxi Order Forecasting

## Stack Used:

- Python
- Pandas
- Seaborn
- LightGBM

## Objectives:

This project focuses on forecasting taxi orders for "Best Taxi" using historical data collected from airport taxi bookings. The goal is to predict the number of taxi orders for the next hour to effectively allocate drivers during peak demand. The project utilizes time series analysis and machine learning techniques to develop a predictive model.

## Findings

- The developed model achieved an RMSE of 43.16 on the test set, indicating good predictive performance. 
- The analysis revealed that the hour of submission and lag with a period of 1 and 2 were the most important features, accounting for a significant portion of the model's weight.

These findings can be used by "Best Taxi" to effectively allocate drivers during peak hours and improve customer satisfaction. By leveraging the predictive model, the company can anticipate the demand for taxis and optimize its operations accordingly.

For detailed analysis and code implementation, please refer to the [Jupyter Notebook](https://github.com/Shurgalivan/Portfolio/blob/main/Taxi%20Order%20Forecasting/orders_taxi_prediction.ipynb) provided in this repository.
