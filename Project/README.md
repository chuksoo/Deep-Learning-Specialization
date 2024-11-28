# Welcome to the LSTM Neural Network for Bitcoin Price Prediction!

### Project Overview

Hello readers! Are you interested in diving into the world of cryptocurrency forecasting? This project is designed just for you. We will be using a Long Short-Term Memory (LSTM) neural network to predict Bitcoin prices. LSTMs are a special type of recurrent neural network (RNN) that can handle time series data remarkably well. They are particularly good at capturing long-term dependencies and patterns, making them perfect for financial market predictions.

By analyzing historical Bitcoin data, our model will help uncover hidden relationships and trends, which can be applied to many time series forecasting needs. Whether you’re a beginner or have some experience in machine learning, this project will be a great addition to your skill set.

### Key Features

•	LSTM Neural Network: Learn how to build and train an LSTM model to capture long-term dependencies in time series data.
•	Technical Indicators: Incorporate a variety of technical indicators like SMA, EMA, RSI, MACD, Bollinger Bands, ATR, and more to enhance our predictions.
•	Cross-Validation: Use 5-fold cross-validation and rolling origin cross-validation to ensure our model’s performance is robust and reliable.
•	Performance Metrics: Evaluate the model using key metrics such as RMSE (Root Mean Squared Error) and MAPE (Mean Absolute Percentage Error).

### Requirements

Before we get started, make sure you have the following libraries installed:
```bash
pip install numpy pandas matplotlib scikit-learn tensorflow talib requests
```

### Workflow

1. Data Retrieval: We’ll fetch historical Bitcoin data from CryptoCompare’s API. It's completely free and there's a link in the notebook to get your own key!
2. Data Preprocessing: We’ll add technical indicators to our data, scale it properly, and prepare it for the LSTM model.
3. Model Building: Together, we’ll define and train an LSTM model with carefully selected layers and dropout to prevent overfitting.
4. Model Evaluation: We’ll assess our model’s performance using RMSE and MAPE to see how well our predictions match the actual prices.
5. Cross-Validation: To ensure our model is robust, we’ll implement 5-fold cross-validation and rolling origin cross-validation.
6. Visualization: Finally, we’ll visualize the actual vs predicted prices to see our model in action!

### Conclusion

By the end of this project, you’ll have a powerful tool for time series forecasting. You’ll understand how to leverage historical data and technical indicators to uncover trends and dependencies. Using cross-validation techniques, you’ll ensure your model is robust and reliable, providing valuable insights for trading decisions.

Ready to get started? Let’s dive right in!
