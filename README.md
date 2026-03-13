⚡ CryptoPulse: Real-Time Crypto Monitoring & Alert Engine
CryptoPulse is a lightweight, high-performance monitoring tool designed for traders and enthusiasts who need instant notifications on market volatility. Built with a modular Python architecture, it tracks live price action via the CoinGecko API and pushes critical alerts directly to your mobile via Telegram.

🚀 Key Features
Real-Time Tracking: Fetches live price data for Bitcoin, Ethereum, and 500+ other assets.

Volatility Alerts: Get notified instantly when a coin moves beyond your custom percentage threshold (e.g., a 2% jump in 5 minutes).

Telegram Integration: No need to stay glued to a dashboard—alerts come straight to your pocket.

Modular Architecture: Clean, decoupled code for API handling, alerting logic, and data processing.

Low Footprint: Optimized to run 24/7 on a Raspberry Pi, local machine, or a cloud VPS.

🛠️ Tech Stack
Language: Python 3.12+

API Service: CoinGecko V3 (REST)

Communication: Telegram Bot API (Webhooks/Polling)

Libraries: requests, python-dotenv, json
