# 🧠 TradingRSI Notifier

A Telegram bot that sends smart, data-driven alerts about Bitcoin market conditions based on weekly RSI and price drop signals. Built in Python, connected to the Binance API.

## 📊 Project Overview

This bot monitors the **weekly RSI (Relative Strength Index)** of Bitcoin and its **current price in EUR** compared to its **all-time high**, sending real-time alerts to subscribed Telegram users when strategic buying opportunities arise:

- ✅ Sends alerts when **RSI is below 20** (oversold zone).
- ✅ Notifies when **BTC drops more than 50%** from its all-time high.
- ✅ Designed for long-term investors using **DCA (Dollar Cost Averaging)** strategies.

## 💡 Key Features

- 📈 Uses **Binance API** to retrieve historical candlestick data.
- 🤖 Sends messages via **Telegram Bot API** using `python-telegram-bot`.
- 🔧 Modular config with external `.json` files for easy threshold tuning and user management.
- 🧪 Can run on a scheduler (e.g., every 5 minutes via Task Scheduler or Cron).
- 🔐 Includes access control and `/start` listener for future user validation/payment flow.

## 🛠️ Technologies Used

- Python 3.10+
- pandas
- python-binance
- python-telegram-bot (HTTPXRequest)
- asyncio
- JSON for config and user data

## 📦 Project Structure

📁 TradingRSI_Bot

├── main_telegram.py # Main script that runs the alerts

├── listener_start.py # Optional: Listens for /start command from Telegram

├── configbtc.json # Configuration for RSI/price thresholds

├── usuarios.json # List of allowed Telegram user IDs

├── log.txt # Log file with all messages and errors

## 🚀 Potential Use Cases

- Personal Bitcoin investment tracking
- Alert tool for crypto traders
- Integration with premium access or paid memberships (Stripe-compatible)

## ⚠️ Disclaimer

This project is for educational and personal use. It is not financial advice. Use at your own discretion and always verify trading signals manually.

---

If you're interested in seeing the code or testing the bot, feel free to contact me.
