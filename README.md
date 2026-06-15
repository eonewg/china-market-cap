# China Market Cap Ranking

Real-time market cap ranking for Chinese listed companies across A-shares, Hong Kong, and US markets.

## Features

- **Multi-market tabs**: A-shares, Hong Kong, US-listed Chinese stocks, and combined ranking
- **Real-time exchange rates**: Fetches live USD/CNY and HKD/CNY rates for accurate cross-market comparison
- **Currency toggle**: Switch between CNY and USD display in combined ranking mode
- **Auto-refresh**: Updates every 30 seconds
- **Market status indicators**: Shows whether each market is currently open or closed
- **Cross-market deduplication**: Companies listed on multiple exchanges appear only once in combined mode

## Data Sources

- A-shares: East Money push2 API (clist + ulist.np)
- Hong Kong stocks: East Money ulist.np API with Tencent Finance fallback
- US stocks: Tencent Finance qt.gtimg.cn API
- Exchange rates: open.er-api.com

## Usage

Open `index.html` in any modern browser. No server required - all data is fetched client-side via JSONP.
