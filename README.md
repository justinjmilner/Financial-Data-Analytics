# Financial-Data-Analytics
Deep learning approach to predict stock price movements using recurrent neural networks. Implements LSTM architecture with comprehensive performance evaluation including directional accuracy analysis and simulated trading strategy. Achieves 1.95% prediction error and demonstrates quantitative finance modeling techniques.

## Overview
This project implements a Long Short-Term Memory (LSTM) neural network to predict stock price movements using historical Dow Jones data. The model focuses on both price prediction accuracy and directional movement prediction for potential trading applications.

## Key Features
- LSTM-based time series prediction with dropout regularization
- Comprehensive evaluation including directional accuracy analysis
- Trading strategy simulation with profit tracking
- Multiple visualization techniques for model performance assessment
- Custom sequence generation for time series data

## Model Architecture
- Sequential LSTM model with 50 units per layer
- Dropout layers (20%) for overfitting prevention
- Sequence length of 4 time steps for prediction
- MinMax scaling for data normalization

## Results
- Mean Absolute Error: 1.95%
- Directional Accuracy: 52%
- Simulated Trading Profit: 4,434 points
- Model converged successfully over 100 training epochs

## Technologies Used
- Python, Keras/TensorFlow
- Pandas, NumPy for data processing
- Matplotlib for visualization
- Scikit-learn for preprocessing
