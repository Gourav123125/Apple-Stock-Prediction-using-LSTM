# Apple Stock Price Prediction using LSTM

## Overview
This project uses a Long Short-Term Memory (LSTM) neural network to predict Apple Inc. (AAPL) stock prices based on historical stock data. The dataset includes daily Open, High, Low, Close, Adjusted Close prices, and trading Volume.

## Dataset
The dataset used for training and testing is historical stock data for Apple (AAPL), sourced from publicly available financial datasets. It contains the following columns:
- **Date**: Trading date.
- **Open**: Stock price at market open.
- **High**: Highest price of the day.
- **Low**: Lowest price of the day.
- **Close**: Stock price at market close.
- **Adj Close**: Adjusted closing price considering dividends and splits.
- **Volume**: Number of shares traded.

## Model Architecture
- The model is implemented using **TensorFlow/Keras**.
- It uses an **LSTM** network, which is well-suited for sequential data.
- The dataset is preprocessed by normalizing stock prices.
- Data is split into training and testing sets.
- The model is trained on past stock price trends to predict future stock prices.

## Dependencies
To run this project, install the following dependencies:
```bash
pip install numpy pandas matplotlib scikit-learn tensorflow keras
```

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/Gourav123125/Apple-Stock-Prediction-using-LSTM.git
   cd Apple-Stock-Prediction-using-LSTM
   ```
2. Ensure the dataset (AAPL.csv) is placed in the project directory.
3. Run the script:
   ```bash
   python train.py
   ```
4. The model will train and output predictions along with a plotted graph comparing actual vs. predicted prices.

## Results
- The model predicts future stock prices based on historical trends.
- Performance is evaluated using **Mean Squared Error (MSE)** and visualization.

## Contributions
Feel free to contribute by improving the model or adding new features. Fork the repository and submit a pull request!

## License
This project is open-source and available under the **MIT License**.

