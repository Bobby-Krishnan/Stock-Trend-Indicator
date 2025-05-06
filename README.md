# Stock Trend Indicator

An interactive web app for visualizing and analyzing historical stock price trends using moving averages and deep learning-based predictions.

---

## Features

- Fetches real-time historical stock data using Stooq via `pandas_datareader`.
- Visualizes price trends with 100-day and 200-day moving averages.
- Predicts future trends using a pre-trained Keras LSTM model.
- Provides a clean, interactive interface via Streamlit.

---

## Technologies Used

- **Python** – Core language.
- **Streamlit** – Web UI framework for Python.
- **pandas** & **NumPy** – Data handling and numerical operations.
- **matplotlib** – For charting price trends.
- **pandas_datareader** – To fetch stock data.
- **Keras** (with TensorFlow backend) – For loading and using the LSTM model.

---

## How to Run

1. **Clone the repo:**

   ```bash
   git clone https://github.com/Bobby-Krishnan/Stock-Trend-Indicator.git
   cd Stock-Trend-Indicator
   ```

2. **Install required packages**

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the app**

   ```bash
   streamlit run app.py
   ```
