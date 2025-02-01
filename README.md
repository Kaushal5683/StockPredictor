# Stock Market Prediction and Forecasting Using Stacked LSTM

## 📊 Overview

This project focuses on predicting and forecasting stock market trends using a Stacked Long Short-Term Memory (LSTM) neural network. It leverages historical stock data and deep learning techniques to make accurate predictions.

## 🚀 Features

- Utilizes Stacked LSTM architecture for better predictive performance.
- Fetches real-time stock data using Tiingo API.
- Visualizes data trends and prediction results.

## 🛠️ Technologies Used

- **Python**
- **TensorFlow (>2.0)**
- **Keras**
- **Pandas**
- **Matplotlib**
- **Pandas DataReader**

## ⚙️ Installation

1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```
2. **Install dependencies:**
   ```bash
   pip install tensorflow pandas matplotlib pandas_datareader
   ```

## 🔑 Tiingo API Setup

1. Sign up at [Tiingo](https://www.tiingo.com/).
2. Navigate to the API section and generate your API key.
3. Replace `key="apikey"` in the notebook with your actual API key:
   ```python
   key = "your_actual_api_key"
   ```

## 📈 Usage

1. Open the notebook:
   ```bash
   jupyter notebook Stock.ipynb
   ```
2. Run the cells sequentially to:
   - Collect stock data
   - Preprocess data
   - Train the Stacked LSTM model
   - Visualize predictions

## 📊 Sample Code

```python
import pandas_datareader as pdr
key = "your_actual_api_key"
df = pdr.get_data_tiingo('AAPL', api_key=key)
```

## 📂 Project Structure

```
├── Stock.ipynb
└── README.md
```

## 📋 License

This project is licensed under the MIT License.

## 🙋‍♂️ Author

- **Kaushal Gujarathi**

Feel free to contribute, raise issues, or suggest improvements!

