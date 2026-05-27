# Nansen Stablecoin Exchange Flows Dashboard

A self-contained HTML dashboard that visualizes USDT and USDC exchange flows across all chains using the [Nansen Token God Mode API](https://docs.nansen.ai/api/token-god-mode/flows).

## Usage

1. Open `index.html` in your browser
2. Enter your Nansen API key when prompted (stored in localStorage for future visits)

## Charts

- 📈 **Inflows vs Outflows Over Time** — daily line chart for USDT and USDC
- 📊 **Net Flow by Chain** — 7-day cumulative net flow per chain
- 🍩 **Top Chains by Volume** — doughnut chart by absolute volume
- 🏦 **CEX vs DEX Breakdown** — stacked breakdown of exchange flow types

## Coverage

16 chain/token pairs: Ethereum, Arbitrum, Base, Polygon, BNB, Optimism, Avalanche, Solana, Tron

## Requirements

No build step. Just open `index.html` in a browser. Uses Chart.js 4.x from CDN.
