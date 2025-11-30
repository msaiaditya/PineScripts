# PineScripts

A collection of TradingView Pine Script indicators and strategies for technical analysis and automated trading.

## Overview

This repository contains custom Pine Script code for TradingView, including:

- **Indicators** - Technical analysis tools for chart visualization
- **Strategies** - Backtestable trading systems with entry/exit logic
- **Libraries** - Reusable functions and utilities

## Repository Structure

```
PineScripts/
├── indicators/          # Custom indicators
├── strategies/          # Trading strategies
├── libraries/           # Reusable Pine Script libraries
└── README.md
```

## Getting Started

### Prerequisites

- [TradingView](https://www.tradingview.com/) account (free or paid)
- Basic understanding of Pine Script syntax

### Using Scripts

1. Open TradingView and navigate to the chart
2. Click on "Pine Editor" at the bottom of the screen
3. Copy and paste the desired script
4. Click "Add to Chart" to apply

### Pine Script Version

Scripts in this repository use **Pine Script v5** unless otherwise noted in the file header.

## Development Guidelines

### File Naming Convention

- Indicators: `indicator_name.pine`
- Strategies: `strategy_name.pine`
- Libraries: `lib_name.pine`

### Code Standards

- Include version declaration: `//@version=5`
- Add descriptive comments for complex logic
- Use meaningful variable names
- Group related functions together

### Script Header Template

```pine
//@version=5
indicator("Script Name", overlay=true)
// Description: Brief description of what this script does
// Author: Your Name
// Version: 1.0.0
// Last Updated: YYYY-MM-DD
```

## Contributing

1. Create a new branch for your changes
2. Test scripts thoroughly on TradingView
3. Document any input parameters
4. Submit a pull request with description of changes

## Resources

- [Pine Script Documentation](https://www.tradingview.com/pine-script-docs/)
- [Pine Script Reference Manual](https://www.tradingview.com/pine-script-reference/)
- [TradingView Public Library](https://www.tradingview.com/scripts/)

## License

This project is for personal and educational use. Please respect TradingView's terms of service when using these scripts.

## Disclaimer

These scripts are provided for educational and informational purposes only. They do not constitute financial advice. Trading involves substantial risk of loss. Always perform your own analysis and risk management before making trading decisions.
