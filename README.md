# 📈 Stock Market Alert System

## Overview
This Python-based script tracks **Tesla (TSLA) stock price movements** and sends **news updates** if significant changes occur. It integrates **Alpha Vantage, NewsAPI, and Twilio** to automate stock monitoring and alerts.

## Features
- Fetches **daily stock data** from Alpha Vantage.
- Calculates **percentage change** in stock price.
- If the change is **greater than 1%**, fetches the **latest 3 news articles** about Tesla.
- Sends **real-time SMS alerts** with stock updates and news headlines.

## Technologies Used
- 🐍 **Python**
- 🔗 **Requests (API calls)**
- 📰 **NewsAPI (for news updates)**
- 📊 **Alpha Vantage (for stock data)**
- 📲 **Twilio (for SMS notifications)**

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/stock-alert-system.git
Install dependencies:
bash
Copy
Edit
pip install requests twilio
Get API keys from:
Alpha Vantage
NewsAPI
Twilio
Replace the placeholder API keys in the script:
python
Copy
Edit
STOCK_API_KEY = "your_alpha_vantage_api_key"
NEWS_API_KEY = "your_newsapi_api_key"
TWILIO_SID = "your_twilio_sid"
TWILIO_AUTH_TOKEN = "your_twilio_auth_token"
Run the script:
bash
Copy
Edit
python stock_alert.py
Output Example
vbnet
Copy
Edit
TSLA: 🔺2%
Headline: Tesla announces new product.
Brief: Tesla is launching a new AI-powered product next month...
License
This project is open-source under the MIT License.
