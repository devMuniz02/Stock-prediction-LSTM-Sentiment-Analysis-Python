# Stock Prediction with LSTM and Sentiment Analysis

This project aims to predict stock prices for the next day using a Long Short-Term Memory (LSTM) model in Python, supplemented by sentiment analysis of news. The approach combines:
- **Deep Learning**: Using LSTM for time-series stock price prediction.
- **Natural Language Processing**: Analyzing market-related news sentiment.

---

## Project Overview

### Files in the Repository

1. **`LSTM.ipynb`**
   - Contains the main workflow for training and testing the LSTM model with stock price data.
   - Below are sample results from the notebook:

     **Full Data Prediction**  
     ![Full Data Prediction](https://github.com/user-attachments/assets/ca0f8a97-3fe3-4739-a173-67ce0b438451)

     **Test Predictions**  
     ![Test Predictions](https://github.com/user-attachments/assets/1127e88a-b1d8-405e-a88e-5a512d38faf2)

2. **`SaveSentiment.ipynb`**
   - Saves the sentiment data extracted from news articles using sentiment analysis techniques.
   - This notebook gathers news sentiments relevant to specific stocks or markets.

3. **`LSTMdef.ipynb`**
   - Uses the sentiment data saved by `SaveSentiment.ipynb` and integrates it with stock data to train and evaluate the LSTM model.
   - Combines stock data and sentiment data for improved predictive performance.

4. **`README.md`**
   - Provides an overview of the project, the files, and their roles in the workflow.

---

## Features

- **Stock Price Prediction**: Time-series forecasting with LSTM for accurate trend analysis.
- **Sentiment Analysis**: Evaluates market sentiment from general news and stock-specific articles to inform predictions.

---

## Getting Started

### Prerequisites
To run the project, ensure you have the following installed:
- Python 3.8 or later
- Required Python libraries: `tensorflow`, `pandas`, `numpy`, `sklearn`, `matplotlib`, `nltk`, `yfinance`, and `fredapi`.

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/Stock-prediction-LSTM-Sentiment-Analysis.git
   cd Stock-prediction-LSTM-Sentiment-Analysis
