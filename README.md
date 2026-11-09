# kultinz-xauusd-signals
# XAU/USD Signal Bot

A simple Telegram alert bot for XAU/USD (gold) signals using the Twelve Data API.

This is an alert-only starter project. It does not place trades or execute orders.

## Features
- Reads XAU/USD 10-minute candles from Twelve Data
- Generates simple trend-based BUY/SELL/HOLD signals
- Sends Telegram alerts
- Supports environment-based configuration
- Designed for deployment on bot-hosting.net or a similar always-on host

## Setup

1. Create a Telegram bot with BotFather.
2. Get a Twelve Data API key.
3. Copy `.env.example` to `.env` and fill in the values.
4. Install dependencies:

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt