## 💼 Profile
**Phutthachat Ninnarat**  
_A data-driven analyst building AI-powered pipelines, automation workflows, and interactive business dashboards using Python, Power Platform, and Generative AI._

## 📌 Project: AI Daily Stock Insight

An automated AI-powered stock recommendation system that integrates historical stock data, technical analysis, news headlines, and Gemini-generated insights. The system generates Thai-language Buy/Sell/Hold recommendations with confidence and reasoning.

### 🔍 Features
- Fetches historical stock prices from Yahoo Finance
- Calculates key indicators: SMA20/50/200, RSI14, MACD, 52-week high/low
- Collects top news headlines using Google News RSS
- Uses Gemini 2.5 API to analyze news impact and generate recommendation JSON
- Produces Markdown reports with AI explanations and optional price chart images
- Exports results to Google Sheets (optional)
- YAML config for customizable tickers, timeframes, and output behavior

### 📁 Outputs
- Markdown report with summary table and per-ticker insights
- PNG charts per ticker (line chart + SMA overlay)
- JSON file per ticker (Gemini output)
- Optional export to Google Sheets

> ⚠️ This is for educational and analytical purposes only. Not financial advice.

## 🛠 Tech Stack
- Python, yfinance, feedparser, Gemini API (Generative AI)
- Google Sheets API, GitHub Actions (for automation)
