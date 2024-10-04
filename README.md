# Stock Market Predictor

A **Stock Market Predictor** using `yfinance` to fetch historical stock data and `TensorFlow` to predict future stock prices with a neural network.

## Features
- Fetch historical stock data with `yfinance`.
- Predict future stock prices using a TensorFlow model.
- Plot historical and predicted stock prices.

## Technologies
- **Python 3.x**
- **yfinance**
- **TensorFlow**
- **NumPy**
- **Matplotlib**

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/kushalkumar-shaw/stock-market-predictor.git
   cd stock-market-predictor
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```


## Usage
1. Run the script:
```bash
streamlit run web_stock_price_predictor.py
```

2. The predicted price will display, along with a plot of historical and predicted data.

## Formula
```math

\hat{P}_{t+1} = f(W \cdot X_t + b)

```

Where:
- $`\hat{P}_{t+1}`$: Predicted stock price for the next time step.
- $`f`$: Activation function (e.g., ReLU or sigmoid).
- $`W`$: Weight matrix learned during training.
- $`X_t`$: Historical stock data up to time $`t`$.
- $`b`$: Bias term learned during training.

## License
This project is licensed under the MIT License.
