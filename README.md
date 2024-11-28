# 📈 AI-Powered Stock Analysis with Multi-Agent RAG 🚀

This repository provides an AI-driven framework to analyze **Nifty 50** or other indices by leveraging **LangChain**, **LangGraph**, and multi-agent systems. It periodically downloads the latest stock details from the NSE website, extracts key metrics, performs technical and fundamental analysis, and generates actionable insights.

---

## 🌟 Key Features
- **📄 PDF Parsing**: Extract the latest Nifty 50 stock details directly from NSE reports.
- **🔍 Multi-Timeframe Analysis**: Perform daily, weekly, and monthly analyses of stock performance.
- **🤖 AI Insights**: Generate insights using custom AI agents and advanced prompting.
- **📊 Sector Aggregation**: Group stocks by sectors and calculate metrics like average market cap.
- **📅 Periodic Updates**: Automate updates for EOD, weekly, and monthly reports.

---

## 🔄 Workflow

1. **Download Data**:
   - Fetch the Nifty 50 list in PDF format from a given URL stored in a `.env` file.
2. **Extract Stock Details**:
   - Parse the PDF to extract stock names, market capitalization, and sector details.
3. **Fetch Market Data**:
   - Use `yfinance` to retrieve historical data for each stock.
4. **Perform Analysis**:
   - Conduct multi-timeframe technical analysis (e.g., RSI, moving averages).
5. **Generate Insights**:
   - Use AI agents for sector-specific and macroeconomic insights.
6. **Report Creation**:
   - Generate periodic reports in text or PDF format summarizing findings.

---

## 🚀 How to Start

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/ai-stock-analysis.git
cd ai-stock-analysis
