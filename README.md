# StockFolio 📈 • Zerodha Kite Dark Theme + Live Quotes

A sleek, mobile-first **Stock Portfolio Tracker** inspired by **Zerodha Kite's** dark-mode mobile UI with **Live NSE/BSE stock price fetching** directly from Yahoo Finance without requiring an API key. Built with pure HTML, CSS, and vanilla JavaScript with client-side persistence in `localStorage`.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

---

## ✨ Features

- 🟢 **Live NSE & BSE Price Fetching**:
  - Fetches the latest `regularMarketPrice` and `previousClose` from Yahoo Finance's quote/chart endpoint (`.NS` for NSE and `.BO` for BSE) with **zero API keys required**.
  - Multi-tier public CORS proxy fallback (`allorigins.win`, `codetabs`, direct) with automatic per-request timeouts.
  - Automatically updates each holding's **LTP**, **Today's P&L**, **Total P&L**, and recalculates the **allocation donut chart**.
  - Gracefully preserves existing prices if offline or if any symbol fails.
  - Shows real-time **Last updated** timestamp and pulsing status indicator.
- 🏛️ **Exchange Selector**:
  - Choose between **NSE** (`.NS`) and **BSE** (`.BO`) when adding or editing holdings (defaults to NSE).
  - Displays distinct exchange tags (`NSE • CNC` / `BSE • CNC`) on each holding row and inside the drawer.
- 📱 **Authentic Zerodha Kite Dark UI**:
  - Deep matte black palette (`#121212`, `#191919`, `#202020`).
  - Signature Kite typography, instrument tags (`CNC`), and color-coded P&L (Kite green `#4caf50` and red `#df514c`).
  - Mobile bottom-sheet action drawer for holding details, live LTP fetching, manual price updates, and deletion.
- 🍩 **Interactive Portfolio Allocation Donut Chart**:
  - Real-time SVG donut visualization of portfolio weight by stock.
  - Hover / tap slices or legend items to inspect percentage weight, current market value, and stock details.
  - Dynamic center gauge with interactive stock highlighting.
- 💼 **Preloaded Holdings**:
  - **HDFCBANK** (NSE): Qty: 1 | Avg: ₹720.55 | CMP: ₹806.60
  - **NIFTYBEES** (NSE): Qty: 1 | Avg: ₹272.52 | CMP: ₹286.46
  - **ONGC** (NSE): Qty: 1 | Avg: ₹234.19 | CMP: ₹235.00
- 💾 **100% Client-Side Persistence**: Saves all your additions, edits, exchange preferences, and price updates in `localStorage`.

---

## 🚀 Getting Started

Simply open `index.html` in any modern web browser or serve locally:

```bash
python -m http.server 3000
```

Open `http://localhost:3000` to track your portfolio with live NSE/BSE quotes.
