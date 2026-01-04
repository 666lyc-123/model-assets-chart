# Performance Dashboard
## Overview
Simplified dashboard showing trading performance analysis for large language models across trading strategies.
## Features
- Clean, minimal design with only essential information
- White background with dark text for optimal readability
- Centered title and responsive table
- Dynamic trading days calculation based on actual file count
## Files
1. **index.html** - Main dashboard page (complete with chart)
2. **plotly_chart.html** - Standalone Plotly visualization
3. **data/processed/performance_data.json** - Performance data
4. **reports/daily/Trading_Performance_Analysis.xlsx** - Daily Excel report
5. **archive/** - Historical performance data
## Performance Metrics
- **Annual Return (%)**: Annualized total return based on actual trading days
- **Sharpe Ratio**: Risk-adjusted return measure
- **Max Drawdown (%)**: Maximum loss from peak
- **Win Rate (%)**: Percentage of profitable days
- **Annualized Volatility (%)**: Annualized standard deviation of daily returns (×√252)
- **Trading Days**: Actual number of trading days (from file count)
## Technical Details
- Built with Python, Pandas, and Plotly
- Automatically updated daily
- Minimal design: Centered title + Table only
- No download links or footer information
- Responsive design for all devices
---
© 2024 Large Model Trading Competition | Automated Dashboard v3.1
