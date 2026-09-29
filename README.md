🇷🇺 [Читать на русском](README_RU.md)

A sandboxed algorithmic execution engine engineered for simulating cryptocurrency trading strategies, order book fulfillment, and real-time portfolio management.

### Key Architectural Highlights:
* **Deterministic Paper Engine:** Real-time simulation of spot orders, account equity tracking, and dynamic PnL calculations with zero capital exposure.
* **Live Market Feeds:** Synchronous retrieval of cryptocurrency price action and technical candlestick charting.
* **Strategy Extensibility:** Modular execution pipeline allowing plug-and-play integration for algorithmic entry and exit rules.
* **Web3 Ready Architecture:** Built-in data schema accommodating non-custodial crypto wallet assignment for fund routing.

### Tech Stack:
* Python 3.12
* Asyncio / Aiohttp (Non-blocking I/O)
* Matplotlib (Technical chart generation)
* python-dotenv (Environment security)

### Quick Start:
```bash
pip install -r requirements.txt
python main14.py
