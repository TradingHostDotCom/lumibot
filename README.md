# TradingHost + Lumibot

Build and deploy trading bots using the [Lumibot](https://lumibot.lumiwealth.com) framework on [TradingHost](https://tradinghost.com).

## What is this?

This repository is an AI-powered development scaffold. Use it as a template (click "Use this template" on GitHub), open your new repo in your AI coding tool (Cursor, Claude, Codex), and tell the AI what you want to build. The rules in `.cursor/rules/` teach the AI everything it needs to know about Lumibot and TradingHost to help you create a production-quality trading bot.

Lumibot is a beginner-friendly Python trading framework that supports multiple brokers — Alpaca, Interactive Brokers, and Tradier — with built-in backtesting against Yahoo Finance data. Perfect for your first algo trading project.

## Getting Started

1. **Click "Use this template"** → Create a new repository (you can make it private)
2. **Open in Cursor** (or your preferred AI coding tool)
3. **Tell the AI what to build** — e.g. "Build me a momentum strategy that buys the top 5 performing stocks each week"
4. **Set credentials** — add your broker API credentials as TradingHost strategy secrets (e.g. `ALPACA_API_KEY`, `ALPACA_API_SECRET`); edit non-secret tunables (paper, broker) in `config.json`. Secrets are environment variables, never committed to git.
5. **Deploy on TradingHost** — link this repo as a strategy, create a deployment, and you're live

## Supported Brokers

- **Alpaca** — easiest to start with, free paper trading, no account minimum
- **Interactive Brokers** — stocks, options, futures, forex — the most complete broker
- **Tradier** — commission-free stock and options trading

## TradingHost Deployment

1. Create an account at [tradinghost.com](https://tradinghost.com)
2. Link this GitHub repository as a strategy
3. Create a deployment (choose region: London, New York, or Tokyo)
4. Your bot runs 24/7 with persistent storage, monitoring, and real-time logs

## Documentation

- [TradingHost Docs](https://tradinghost.com/docs)
- [Lumibot Documentation](https://lumibot.lumiwealth.com)
- [Alpaca API Docs](https://docs.alpaca.markets)

## Risk Warning

Trading stocks and other securities involves significant risk of loss. This software is provided as-is with no guarantees. Always test with paper trading before using real funds.
