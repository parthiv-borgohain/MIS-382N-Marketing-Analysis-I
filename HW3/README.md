# Marketing Analytics -Forecasting Apple Sales Revenue

### Introduction:

This project aims to explore different forecasting methods and models on a time series dataset of a technology product's sales for the first 20 quarters after its launch. The project is divided into three parts, each focusing on a different forecasting approach.

### Part 1: Forecasting with the Bass Diffusion Model

In this section, I ran the Bass Diffusion Model with a 25MM market size, a 20 year forecast period, p as 0.03, and q as 0.4. The model shows that the product adoption peaked around 7-8 years but stagnated around 14 years after its debut on the market, which makes sense in the context of the data. The model helps understand the behavior of early adopters and the influence of marketing efforts on the adoption rate.

### Part 2: Forecasting with 2-period Moving Average

In this section, I computed a 2-period moving average forecast and then used an exponentially smoothed forecast to find the optimal alpha level, which determines the weight of the previous periods on the most recent observation. I then used the Holt-Winters model, which captures the volatility of sales, to forecast the time series.

### Part 3: Forecasting with Holt-Winters Model

In this section, I computed a forecast for one period in the future using a dynamic level, trend, and seasonality model. I initialized the model using the first 8 quarters of data and found the optimal values of alpha, beta, and gamma that minimized the sum of squares using Solver. Once the optimal values were set, I graphed the actual revenues and one-step forecasts from the dynamic level, trend, and seasonality model. Finally, I computed the final forecasts for each period by adding level, trend, and seasonality.

### Conclusion:

This project demonstrates different methods and models for time series forecasting and their applications in understanding the behavior of a product's sales. The Bass Diffusion Model can help understand the influence of early adopters and marketing efforts on adoption rate, while moving average and Holt-Winters models capture the volatility of sales and provide accurate forecasts.
