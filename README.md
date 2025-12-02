# **seq2seq For Crypto Price Prediction**  
_Transformer model for forecasting the closing price of seven major cryptocurrencies using recent temporal windows._

---

## **Overview**  
This project showcases the implementation of a **Transformer** deep learning model designed to predict short-term cryptocurrency closing prices. The model uses: 
- Historical 95-hour windows of closing prices,
- To forecast the next 5 hours,
- Across seven cryptocurrencies simultaneously.

The project demonstrates the use of recurrent neural networks with attention mechanisms for multivariate time-series forecasting.

---

## **Key Features**  
- Transformer architecture with multi-head attention.
- Multi-asset forecasting (BTC, ETH, BNB, XRP, ADA, SOL, DOT).
- Automatic data retrieval from Yahoo Finance.
- Preprocessing pipeline including scaling and NaN handling.
- Visual evaluation of prediction performance. 

---

## **Requirements**  
- Python >= 3.8  
- Libraries:  
  - `yfinance`
  - `pandas`
  - `numpy`
  - `tensorflow`
  - `scikit-learn`  
  - `matplotlib`  

---

## **Setup and Installation**  
Follow these steps to set up and run the project:  

1. Clone the repository:  
   ```bash
   git clone https://github.com/angelmdezhdez/transformer-for-cryptos.git