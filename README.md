**Stock Trend Indicator**

A simple and interactive web app for visualizing and analyzing historical stock price trends using moving averages and deep learning-based predictions.

**Features**

Fetches real-time historical stock data using Stooq via pandas_datareader.

Visualizes price trends with 100-day and 200-day moving averages.

Predicts future trends using a pre-trained Keras LSTM model.

Provides a clean, interactive interface via Streamlit.

**Technologies Used**

Python: Core language.

Streamlit: Web UI framework for Python.

pandas & NumPy: Data handling and numerical operations.

matplotlib: For charting price trends.

pandas_datareader: To fetch stock data.

Keras (TensorFlow backend): For loading the LSTM model and making predictions.

How to Run
Clone the repo:

bash
Copy
Edit
git clone https://github.com/Bobby-Krishnan/Stock-Trend-Indicator.git
cd Stock-Trend-Indicator
Install required packages:

bash
Copy
Edit
pip install -r requirements.txt
Run the app:

bash
Copy
Edit
streamlit run app.py

