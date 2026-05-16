Stock Prediction Using LSTM Neural Networks

This project implements a Long Short-Term Memory (LSTM) deep learning model to predict Microsoft stock closing prices using historical stock market data. The model was built using TensorFlow/Keras and trained on time-series stock price data to identify sequential patterns and forecast future closing prices.

The project includes multiple stages of data preprocessing and exploratory data analysis (EDA), including correlation analysis, volume trend visualization, and feature scaling using StandardScaler. A sliding window approach was applied to transform historical stock prices into sequential training data suitable for LSTM modeling.

The neural network architecture consists of stacked LSTM layers, dense layers with ReLU activation, and dropout regularization to reduce overfitting. The model was trained using the Adam optimizer with Mean Absolute Error (MAE) loss and Root Mean Squared Error (RMSE) evaluation metrics.

Prediction results, visualizations, and model outputs are automatically saved into an output directory for further analysis and presentation. The final visualization compares actual and predicted stock closing prices over time.
