# 📈 TradingRSI Notifier – Telegram Bot for Bitcoin Alerts

> ⚠️ This repository is **private** and intended for **demonstration purposes only**. Please do not redistribute or reuse without prior permission.

## 🔍 Overview

TradingRSI Notifier is a custom-built Telegram bot designed to notify users when Bitcoin (BTC) hits **oversold RSI levels** or **drops significantly below its all-time high**, using real-time data from the Binance API.

This project was created as a personal solution for automated monitoring of long-term entry opportunities in BTC, based on two key indicators:

- **RSI (Relative Strength Index) Weekly < 20**
- **Price drop ≥ 50% from ATH**

## ⚙️ Key Features

- 📲 **Telegram notifications** to registered users
- 🔄 **Automated weekly RSI and price checks** using Binance data
- 📉 **Configurable RSI thresholds and ATH price levels**
- ✅ Uses `asyncio` for efficient bot operations
- 🔐 Manual access control via `usuarios.json`

## 🧠 How It Works

1. The bot fetches weekly BTC/EUR candle data via Binance API.
2. It calculates RSI values and compares the current price to the ATH threshold.
3. If any condition is met (RSI < 20 or price < -50%), it sends an alert via Telegram to the registered users.
4. Users must be pre-registered manually or via a secure `/start` access system.

## 🛠 Tech Stack

- Python 3.11+
- Binance API (via `python-binance`)
- Telegram Bot API (via `python-telegram-bot`)
- Pandas for data analysis
- Asyncio for async task management

## 🔐 Access & Usage

This repository contains proprietary code and logic and is **not open-source**. It is shared **only for technical evaluation and project demonstration**.

If you'd like to learn more about the implementation or see a live demo:
- 📩 Contact me directly for temporary access.
- 🎥 Or request a recorded video showing the bot in action.

## 📌 Motivation

This bot was born from a personal need to monitor ideal buying conditions for long-term BTC investments. It aims to reduce emotional decision-making by using strict, data-driven alerts.

## 📎 License & Permissions

📫 **For inquiries or to request a private demo**, feel free to contact me via LinkedIn or email.
