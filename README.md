# Sales-Forecasting-Using-LSTMs---SARIMA-Hybrid-Model

The goal is to predict the future sales of a certain product(s) based on historical sales data and
other relevant factors such as marketing efforts, economic conditions and consumer behavior in
order to assist in making informed business decisions, using this, businesses can better manage
their inventory levels, ensuring that they have the right products in stock at the right time that is
planning for future demand by identifying patterns and trends in sales data. 

To capture the underlying patterns and seasonality of the data, fit a SARIMA model to the time
series data. Use the residual errors from the SARIMA model as input to the LSTM model. To
identify any remaining patterns or relationships in the data that the SARIMA model missed, train
the LSTM model on the residual errors. Combine the predictions from the SARIMA model with
the predictions from the LSTM model to make the final forecast. The combination of these two
models can provide more accurate forecasting than either model alone
