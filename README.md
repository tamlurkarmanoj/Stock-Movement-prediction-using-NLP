# Stock Price Prediction with Sentiment Analysis and Knowledge Graph

This project predicts the future stock prices of Nestle India (NESTLEIND.NS) using deep learning models (GRU and LSTM) and incorporates sentiment analysis from financial news to enhance prediction accuracy. It also includes a knowledge graph representation of the news sentiment.

## Features

- **Time-Series Prediction:** Utilizes GRU and LSTM models to forecast the next 30 days of stock prices based on historical data.
- **Sentiment Analysis:** Fetches the latest news related to the stock and performs sentiment analysis on the headlines using `TextBlob`.
- **Knowledge Graph:** Builds and visualizes a knowledge graph to represent the relationships between news articles, publishers, topics, and overall sentiment.
- **Performance Comparison:** Compares the performance of the GRU and LSTM models.
- **Interactive Visualization:** Plots the historical and predicted stock prices using `plotly` for an interactive experience.

## Technologies Used

- **Python 3**
- **Jupyter Notebook**
- **Libraries:**
  - `yfinance`: For fetching stock and news data.
  - `pandas`: For data manipulation.
  - `numpy`: For numerical operations.
  - `tensorflow` & `keras`: For building and training the deep learning models.
  - `scikit-learn`: For data scaling.
  - `plotly` & `matplotlib`: For data visualization.
  - `textblob`: For sentiment analysis.
  - `networkx`: For creating the knowledge graph.
  - `tabulate`: For displaying data in tables.
  - `pyvis`: For interactive network visualizations.
  - `mplcursors`: For interactive cursors in matplotlib plots.

## Installation

1.  **Clone the repository (or download the files):**
    ```bash
    git clone <your-repository-url>
    cd <your-repository-name>
    ```

2.  **Install the required libraries:**
    It's recommended to use a virtual environment.
    ```bash
    pip install -r requirements.txt
    ```

## `requirements.txt`

## Usage

1.  Open the `Final_code.ipynb` file in Jupyter Notebook or JupyterLab.
2.  Run the cells sequentially to see the data fetching, model training, prediction, and visualization process.

## Project Structure

The Jupyter Notebook is divided into the following sections:

1.  **Data Fetching:** Fetches historical stock data and news for Nestle India.
2.  **GRU Model Prediction:** A GRU model is trained on the stock's closing prices to predict future trends.
3.  **LSTM Model Prediction:** An LSTM model is also trained for comparison.
4.  **Sentiment Analysis and Event Detection:** News headlines are analyzed to determine sentiment (bullish, bearish, or neutral).
5.  **Knowledge Graph Representation:** A graph is created to visualize the sentiment and relationships in the news data.
6.  **Integrated Model:** A model that combines time-series data with sentiment information for improved predictions.
7.  **Performance Comparison:** A comparison of the predictions from the different models.
