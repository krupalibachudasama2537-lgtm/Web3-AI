# ArbiLearn – Web3 Explorer

A 4-page educational website built for the **Arbitrum Builder Pods** assignment. The theme is **Arbitrum / Layer 2 Overview**.

## Pages

| Page | File | Description |
|------|------|-------------|
| Home / Landing | `index.html` | Hero, chain visual, feature cards, L2 explanation |
| Concepts | `concepts.html` | Side-by-side Web3 concept comparison cards |
| Live Prices | `prices.html` | Real-time ETH/BTC/SOL/POL/ARB from CoinGecko API |
| Block Simulator | `simulator.html` | Interactive SHA-256 mining simulator showing immutability |

## How to Run Locally

1. Clone the repo
2. Open `index.html` in any modern browser
3. No build step required — pure HTML/CSS/JavaScript

> **Note:** The Live Prices page fetches from `api.binance.com` (free, no API key). If rate-limited, wait 60 seconds and click Refresh.

## Tech Stack

- HTML5 / CSS3 / Vanilla JavaScript
- Web Binance API for the Block Simulator
- Binance public API for live prices
- Google Fonts (Space Grotesk + Inter)

## Known Issues / Future Improvements

- Binance free tier has rate limits — a backend proxy would improve reliability
- The mining simulator uses a "00" prefix difficulty — real Bitcoin uses 19+ leading zeros
- Could add more coins and a price history chart on the Prices page

## Batch

Arbitrum Builder Pods · 2025
