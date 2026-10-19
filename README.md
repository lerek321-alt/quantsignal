# QuantSignal

Stock-research chatbot prototype using quantitative indicators and publicly disclosed insider transactions.

## Online demo

GitHub Pages serves a synthetic-data demo. It calculates BUY, SHORT and WATCH research signals and answers supported questions with a deterministic quant engine. It does not call a live AI model or market-data provider. No orders are placed. Scores are unvalidated heuristics, not probabilities of profit.

## Full application

Download and extract [QuantSignal-source.zip](QuantSignal-source.zip) for the editable React/Vinext project, backend API routes, six quant tests and setup instructions. Use Node.js 22+, then `npm ci` and `npm run dev`. Set `ALPHA_VANTAGE_API_KEY` and optional `OPENAI_API_KEY` only on the server. Never add secrets to GitHub Pages or commit them. A backend host is required for live market-data and AI calls.

The source archive includes the original project's documentation. Any statement there that publication is blocked describes the earlier Sites attempt. This repository separately publishes the demo and source archive.

Public insider disclosures may be delayed. Only explicit P/S codes affect scoring. No backtested investment performance is claimed.
