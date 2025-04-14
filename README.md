# GPT Function Calling – RSI Crypto Trading Assistant

This is a step-by-step demo of OpenAI's function calling feature using Python. It walks you through building a simple crypto trading assistant that analyzes RSI (Relative Strength Index) using real-time OHLC data from Binance. This code is part of the blog post: [Build a Crypto Bot Using OpenAI Function Calling]([http://](https://blog.adnansiddiqi.me/build-a-crypto-bot-using-openai-function-calling/))


## 🚀 Features

- Uses OpenAI's latest chat completions API with `tool_calls`
- Fetches live OHLC data from Binance
- Calculates RSI using `pandas-ta`
- Returns structured JSON responses
- Explains how function calling works internally with `tool_calls` and response linking

---

## 📦 Requirements

- Python 3.8+
- `openai>=1.2.0`
- `pandas`
- `pandas-ta`
- `requests`

Install with:

```bash
pip install openai pandas pandas-ta requests
