# Dividend Core

A modern dividend analytics dashboard for tracking portfolio income, dividend growth, yield performance, and passive cashflow projections.

## Overview

Dividend Core is a lightweight web-based dashboard focused on dividend investing analytics. It provides a clean interface for monitoring portfolio performance, analyzing dividend income, and visualizing long-term passive income growth.

The project is designed for investors who want a fast, minimal, and data-driven overview of their dividend portfolio.

---

## Features

* 📈 Dividend portfolio analytics
* 💰 Annual / monthly dividend income projections
* 📊 Portfolio yield overview
* 🧮 Dividend growth analysis
* 📅 Upcoming dividend calendar
* 🌍 Sector diversification insights
* ⚡ Fast and responsive dashboard UI
* 🌙 Modern dark-mode inspired design
* 📱 Responsive layout for desktop and mobile
* 🔄 Real-time or configurable market data updates

---

## Dashboard Highlights

### Portfolio Overview

Track your complete dividend portfolio in one place:

* Total portfolio value
* Dividend yield
* Annual passive income
* Monthly cashflow estimation
* Top dividend contributors

### Analytics & Insights

Visualize important metrics including:

* Dividend growth trends
* Yield distribution
* Sector allocation
* Performance comparison
* Income forecasting

### Dividend Calendar

Stay ahead of upcoming payments with:

* Ex-dividend dates
* Payment dates
* Expected payouts
* Monthly income breakdowns

---

## Tech Stack

This project is built using modern frontend technologies:

* HTML5
* CSS3
* JavaScript (ES6+)
* Chart.js
* GitHub Pages

Depending on future development:

* API integrations for market data
* Local storage / persistence
* Portfolio import/export support

---

## Live Demo

🔗 [https://looped83.github.io/dividend-core/](https://looped83.github.io/dividend-core/)

---

## Installation

Clone the repository:

```bash
git clone https://github.com/looped83/dividend-core.git
```

Navigate into the project:

```bash
cd dividend-core
```

Start a local server:

### Python

```bash
python -m http.server 8000
```

### Node.js

```bash
npx serve
```

Open in browser:

```text
http://localhost:8000
```

---

## Project Structure

```text
dividend-core/
├── assets/
├── css/
├── js/
├── data/
├── index.html
├── README.md
└── config.js
```

---

## Configuration

Portfolio assets and dashboard settings can be customized inside the configuration files.

Example:

```js
const portfolio = [
  'AAPL',
  'MSFT',
  'O',
  'JNJ'
]
```

Customize:

* Portfolio tickers
* Currency
* Refresh interval
* Theme settings
* Chart colors
* Dividend projection logic

---

## Roadmap

Planned features:

* [ ] Multi-portfolio support
* [ ] Dividend reinvestment simulation (DRIP)
* [ ] Historical performance tracking
* [ ] Export to CSV / Excel
* [ ] Authentication system
* [ ] API integrations
* [ ] Tax estimation tools
* [ ] Watchlist support
* [ ] AI-powered dividend insights

---

## Screenshots

Add screenshots of the dashboard here.

```text
/docs/screenshots/dashboard-overview.png
/docs/screenshots/dividend-analytics.png
```

---

## Deployment

The project can easily be deployed via GitHub Pages.

### GitHub Pages

1. Push repository to GitHub
2. Open repository settings
3. Navigate to Pages
4. Select:

   * Branch: `main`
   * Folder: `/root`
5. Save changes

Your dashboard will be available at:

```text
https://your-username.github.io/dividend-core/
```

---

## Disclaimer

This project is for educational and informational purposes only.

It does not constitute financial advice, investment guidance, or tax consultation.

Always conduct your own research before making investment decisions.

---

## Contributing

Contributions, ideas, and feature requests are welcome.

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Open a pull request

---

## License

MIT License

---

## Author

Created by Looped83

GitHub: [https://github.com/looped83](https://github.com/looped83)
