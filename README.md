# AlphaCouncil
# AlphaCouncil
A browser-native AI agent system that simulates a consensus council of 35 legendary financial experts to analyze tickers.

## How it works
AlphaCouncil is a client-side web application. It uses the Gemini API via direct browser requests, eliminating the need for a server. 

## Features
- **Serverless Architecture**: All processing happens in the browser.
- **Agent Consensus**: 35 unique personas analyze tickers in parallel.
- **Structured Output**: Uses Gemini's `responseSchema` to guarantee clean JSON data.

## How to run
1. Clone this repo.
2. Open `index.html` in any modern web browser.
3. Paste your [Google Gemini API Key](https://aistudio.google.com/apikey) into the settings panel.
4. Enter a ticker (e.g., AAPL) and click "Run Council".
