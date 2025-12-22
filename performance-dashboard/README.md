# Performance Dashboard

## Overview
This dashboard provides daily automated analysis of trading performance for five large language models across three trading strategies.

## Folder Structure
performance-dashboard/
├── index.html # Main dashboard page
├── assets/
│ ├── css/
│ │ └── dashboard.css # Custom styles
│ ├── images/ # Images and icons
│ └── icons/ # Icon files
├── data/
│ ├── raw/ # Raw data files
│ └── processed/ # Processed data (JSON)
├── charts/
│ ├── daily/ # Daily charts
│ └── comparison/ # Comparison charts
├── reports/
│ ├── daily/ # Daily reports (Excel)
│ └── weekly/ # Weekly summaries
└── archive/ # Archived historical data

## Files
1. **index.html** - Main dashboard with interactive Plotly table
2. **assets/css/dashboard.css** - Custom styling (white background, dark text)
3. **data/processed/performance_data.json** - Latest performance data
4. **reports/daily/Trading_Performance_Analysis.xlsx** - Daily Excel report
5. **archive/** - Historical Excel files (dated)

## Performance Metrics
- **Annual Return (%)**: Annualized total return
- **Sharpe Ratio**: Risk-adjusted return measure
- **Max Drawdown (%)**: Maximum loss from peak
- **Win Rate (%)**: Percentage of profitable days
- **Return Volatility (%)**: Standard deviation of returns

## Update Information
- **Last Update**: 2025-12-22 22:51:58
- **Update Frequency**: Daily
- **Models**: Extracted from trading files (e.g., deepseek-v3, gemini-3-pro, gpt-5, llama-3.1-405b, qwen-72b)
- **Patterns**: Pure Data, Data+Technical, Data+News

## Access
Dashboard URL: https://666lyc-123.github.io/model-assets-chart/performance-dashboard/

## Technical Details
- Built with Python, Pandas, and Plotly
- Automatically updated daily
- White background with dark text for optimal readability
- Responsive design for all devices

---
© 2024 Large Model Trading Competition
