---
layout: page
title: Market Manipulation Detection System
subtitle: Advanced ML system for financial market surveillance
---

# Market Manipulation Detection System

## Project Overview

This capstone project develops a sophisticated machine learning system to detect market manipulation patterns in high-frequency trading environments. The project integrates real-time market data, order book analysis, and sentiment analysis to identify potentially manipulative trading behaviors across multiple securities.

\![Market Analysis Visualization](/assets/img/eda_analysis.png)

## Key Results & Findings

### Data Quality Metrics
- **Accuracy**: 99.97% price accuracy validated against Yahoo Finance
- **Dataset Scale**: 55,508 minute-level observations across 35 days
- **Securities**: TSLA (41.1%), AAPL (34.5%), MSFT (24.3%)

### Technical Achievements
- **Multi-API Integration**: Alpaca Markets, Interactive Brokers, Alpha Vantage
- **Database Architecture**: PostgreSQL 3NF design with three core tables
- **Real-time Pipeline**: Automated data collection with error handling
- **Feature Engineering**: Manipulation detection algorithms

**Technologies**: Python, PostgreSQL, Alpaca API, IBKR API, Alpha Vantage, VADER
EOF < /dev/null