# StockFolio 📈 • Zerodha Kite Dark Theme

A sleek, mobile-first **Stock Portfolio Tracker** inspired by **Zerodha Kite's** dark-mode mobile UI. Built with vanilla HTML, CSS, and JavaScript with client-side persistence in `localStorage`.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

---

## ✨ Features

- 📱 **Authentic Zerodha Kite Dark UI**:
  - Deep matte black palette (`#121212`, `#191919`, `#202020`).
  - Signature Kite typography, instrument tags (`CNC`), and color-coded P&L (Kite green `#4caf50` and red `#df514c`).
  - Mobile bottom-sheet action drawer for holding details, quick LTP updates, and deletions.
- 🍩 **Interactive Portfolio Allocation Donut Chart**:
  - Real-time SVG donut visualization of portfolio weight by stock.
  - Hover / tap slices or legend items to inspect percentage weight, current market value, and stock details.
  - Responsive center gauge with dynamic stock highlighting.
- 💼 **Preloaded Holdings**:
  - **HDFCBANK**: Qty: 1, Avg: ₹720.55, CMP: ₹806.60
  - **NIFTYBEES**: Qty: 1, Avg: ₹272.52, CMP: ₹286.46
  - **ONGC**: Qty: 1, Avg: ₹234.19, CMP: ₹235.00
- 📊 **Kite Portfolio Summary**:
  - Total Investment & Current Portfolio Value in INR (₹).
  - Total Profit & Loss amount and percentage.
  - Today's P&L tracking.
- ⚡ **Real-Time Market Tick Simulation**: Test dynamic price adjustments with the simulation button.
- 💾 **100% Client-Side Persistence**: Saves all your additions, edits, and price updates in `localStorage`.

---

## 🚀 Getting Started

Simply open `index.html` in any mobile or desktop web browser, or serve locally:

```bash
python -m http.server 3000
```

Open `http://localhost:3000` to track your portfolio.
