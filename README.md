# Market Lab — Paper Trading Simulator

A responsive 2D stock-market practice dashboard built with HTML, CSS, JavaScript and Canvas 2D. No build step or framework is required.

## Features

- Local sign-up/sign-in flow with a salted PBKDF2 password hash.
- $100,000 in virtual starting capital for each local practice account.
- Generated illustrative price movements for nine instruments (not live exchange quotes).
- Canvas line and candlestick charts with selectable chart windows.
- Simulated market buy/sell orders, quantity checks, configurable commission and holdings with average cost basis.
- Portfolio equity, cash, invested value, unrealized profit/loss, allocation chart and order history.
- Watchlist, ticker search, CSV/JSON export, preferences and educational notes.
- Responsive dashboard for desktop and mobile.

## Run locally

Open `index.html` in a modern browser with JavaScript enabled. For account password hashing through Web Crypto, use HTTPS or localhost; GitHub Pages provides HTTPS automatically.

## Publish with GitHub Pages

1. Open **Settings → Pages** in the repository.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Choose branch **main** and folder **/(root)**, then click **Save**.
4. Once deployment is ready, the expected URL is `https://phucdepzai2012.github.io/netscary/`.

## Important limitations

This is a client-side educational prototype, not a production financial platform. Quotes are randomly generated in the browser; they are not real-time market prices. No real-money orders are sent. Account credentials, user data and portfolios are stored in local browser storage on the current device only, with no server-side authentication, recovery or cloud sync. Do not reuse an important password here.
