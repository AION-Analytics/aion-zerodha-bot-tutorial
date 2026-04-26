# Building a Zerodha/Groww Trading Bot Using AION News-to-Signal

This tutorial shows how to use AION Analytics News-to-Signal as a stock picker from news India workflow for broker-linked automation.

Use it to generate news based stock signals NSE traders can map into sector rotation, watchlists, and execution rules.

AION Analytics also works as an AI trading signals India API for developers who want structured signals instead of manual sentiment analysis.

# What this tutorial covers

- Install `aion-news-to-signal` and `kiteconnect`
- Call `from aion import analyze`
- Read `trade_direction_signals`
- Map sector signals to NSE stocks
- Turn a headline into a sample Zerodha/Groww trade idea

# Notebook

- `zerodha_news_signals.ipynb`

# Example outcome

Headline: `RBI hikes repo rate by 25 bps`

- long: `IT`
- short: `Banks`, `NBFC`, `Realty`
- stock mapping: `TCS`, `INFY`, `WIPRO` vs `HDFCBANK`, `ICICIBANK`, `SBIN`

# Why this exists

Most tools stop at positive/negative sentiment. AION Analytics News-to-Signal converts Indian market headlines into sector-level signals you can map to stocks, bots, and dashboards.

# Links

- Main repo: [AION Analytics News-to-Signal](https://github.com/AION-Analytics/aion-news-to-signal)
- Hugging Face model: [AION-Analytics/aion-news-to-signal](https://huggingface.co/AION-Analytics/aion-news-to-signal)
- Live demo: [AION News-to-Signal Space](https://huggingface.co/spaces/AION-Analytics/aion-news-to-signal)
