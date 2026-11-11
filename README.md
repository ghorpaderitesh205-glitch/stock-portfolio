# StockFolio 📈

A sleek, modern dark-mode **Stock Portfolio Tracker** built with pure HTML, CSS, and vanilla JavaScript. Designed specifically for Indian Equities (INR / ₹) with client-side persistence in `localStorage`.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

---

## ✨ Features

- 🌓 **Sleek Dark Dashboard**: Modern glassmorphic cards with glowing accents and responsive design.
- 💰 **Summary Overview**:
  - **Current Portfolio Value** (₹)
  - **Total Invested Capital** (₹)
  - **Total Profit / Loss** (₹ amount & percentage)
  - **Today's P&L** (₹ amount & percentage vs previous close)
- 📊 **Holdings Management**:
  - Add new stocks (Symbol, Name, Quantity, Buy Price, CMP, Previous Close).
  - Quick-edit CMP (Current Market Price) inline or through modal.
  - Delete holdings with instant confirmation.
  - Interactive column sorting (Stock, Qty, Invested, CMP, Day P&L, Total P&L).
  - Live search filter by symbol or company name.
- ⚡ **Market Simulation**: Built-in "Live Sim" button to simulate intraday price fluctuations.
- 💾 **Persistent Storage**: All portfolio entries and price updates are automatically saved locally in browser `localStorage`.
- 🇮🇳 **Indian Numbering Format**: Currency formatting using standard Indian numbering system (`₹1,25,000.00`).

---

## 🚀 Getting Started

Simply open `index.html` in any modern web browser or serve it via a static file server:

```bash
# Using python
python -m http.server 3000

# Using Node / npx
npx serve .
```

Navigate to `http://localhost:3000` to track your portfolio.
