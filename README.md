# Surcher Stock: NEXUS Trading (TradingView-style clone)

![React](https://img.shields.io/badge/React-18-61DAFB?logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-Express-339933?logo=node.js&logoColor=white)

An attempt at a TradingView-style charting app with real-time prices, drawing tools and AI analysis.

The source code is in [`tradingview-clone.zip`](./tradingview-clone.zip).

## Features (as described in the project)

- Candlestick, bar and area charts with 1m to 1W timeframes
- SMA 20/50, Bollinger Bands and an RSI panel
- Drawing tools: trendline, horizontal/vertical lines, rectangle, Fibonacci, arrow, text
- WebSocket price streaming and price alerts
- AI analysis panel (needs your own API key)

## Built with

- **Frontend:** React 18, [lightweight-charts](https://github.com/tradingview/lightweight-charts), Zustand, Axios, Create React App
- **Backend:** Node.js, Express, ws (WebSocket), better-sqlite3, node-cron, helmet, express-rate-limit, Winston, dotenv

## Getting started

```bash
unzip tradingview-clone.zip && cd tradingview-clone
cd backend && npm install && cp .env.example .env && npm run dev
# in a second terminal
cd frontend && npm install && npm start
```

Then open http://localhost:3000.
