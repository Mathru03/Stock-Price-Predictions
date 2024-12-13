STOCK PRICE PREDICTION FOR TATA STEEL

Project Overview

This project focuses on predicting the stock prices of Tata Steel using a Long Short-Term Memory (LSTM) model. The model was trained on historical stock price data from 2005 to October 2024 and achieved an accuracy of 85%.

Key Features

Data: Historical stock price data of Tata Steel from 2005 to October 2024.

Model: LSTM (Long Short-Term Memory), a type of recurrent neural network designed for sequence prediction tasks.

Performance: Achieved an accuracy of 85%.

Dataset

Source: Historical stock price data of Tata Steel.

Training Data: Data from 2005 to October 2024.

Preprocessing Steps

Loaded the data and handled missing values.

Normalized the data for better performance of the LSTM model.

Created sequences of past stock prices as input features.

Split the data into training and testing sets.

Model

Architecture: LSTM

Framework: TensorFlow/Keras

Loss Function: Mean Squared Error (MSE)

Optimizer: Adam

Model Training

The model was trained on the preprocessed data using LSTM layers to capture temporal dependencies.

Epochs:  50

Batch Size: 32

Results

The LSTM model achieved an 85% accuracy in predicting stock prices.

Predicted vs Actual stock prices showed strong correlation during validation.

Visualizations

Stock price trends (actual vs predicted) are visualized to evaluate model performance.

Dependencies

Python 3.8+

TensorFlow/Keras

Pandas

NumPy

Matplotlib

Scikit-learn


Conclusion

This project demonstrates the use of LSTM for time-series prediction tasks. By leveraging historical stock price data, the model provides reliable predictions, aiding in better decision-making for stock market analysis.

Future Work

Enhance the model by including additional features such as trading volume, macroeconomic indicators, and sentiment analysis.

Implement other advanced models like Transformer-based architectures for comparison.



