# Time Series Data Science Learning Project

## Overview

This repository contains my learning journey through time series analysis and data science fundamentals. As part of my AI and data science education, I've created a series of Jupyter notebooks that progressively build from basic pandas operations to implementing financial backtesting strategies.

## Learning Objectives

- Master pandas Series operations and time series manipulation
- Understand financial data analysis and visualization techniques
- Learn multi-asset portfolio analysis and returns calculation
- Implement and evaluate trading strategy backtesting frameworks
- Gain hands-on experience with data science libraries and workflows

## Project Structure

```
time-series/
├── Notebook_01.ipynb    # Basic Series Operations
├── Notebook_02.ipynb    # Financial Data Analysis
├── Notebook_03.ipynb    # Multi-Asset Returns
├── Notebook_04.ipynb    # Backtesting Framework
├── AAPL.csv            # Apple stock data for analysis
└── README.md           # This file
```

## Notebooks Description

### 📊 Notebook 01: Series Operations
**Focus**: Basic pandas Series and time series fundamentals
- Creating date ranges and time series data
- Computing rolling moving averages
- Understanding pandas datetime indexing
- Basic time series transformations

### 📈 Notebook 02: Financial Data Analysis
**Focus**: Real-world financial data processing and visualization
- Loading and processing AAPL stock data from CSV
- Interactive financial charts using Plotly
- OHLCV (Open, High, Low, Close, Volume) data analysis
- Data cleaning and missing value handling

### 💼 Notebook 03: Multi-Asset Returns
**Focus**: Portfolio analysis and returns calculation
- Multi-asset data structure using MultiIndex
- Generating synthetic market data for multiple tickers (AAPL, FB, GE, AMZN, DAI)
- Computing daily returns across multiple assets
- Data pivoting and restructuring techniques

### ⚡ Notebook 04: Backtesting Framework
**Focus**: Trading strategy implementation and evaluation
- Building a simple backtesting engine
- Implementing random long-only trading strategy
- Strategy performance comparison (random vs buy-and-hold)
- PnL calculation and visualization
- Performance metrics and strategy evaluation

## Installation & Setup

### Prerequisites
- Python 3.7+
- Jupyter Notebook or JupyterLab

### Required Libraries

Install the required dependencies using pip:

```bash
pip install pandas numpy matplotlib plotly jupyter
```

Or using conda:

```bash
conda install pandas numpy matplotlib plotly jupyter
```

### Alternative: Using requirements.txt

If you prefer to use a requirements file:

```bash
# Create requirements.txt with:
pandas>=1.3.0
numpy>=1.21.0
matplotlib>=3.4.0
plotly>=5.0.0
jupyter>=1.0.0

# Then install:
pip install -r requirements.txt
```

## Getting Started

1. **Clone or download this repository**
   ```bash
   git clone <repository-url>
   cd time-series
   ```

2. **Install dependencies**
   ```bash
   pip install pandas numpy matplotlib plotly jupyter
   ```

3. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

4. **Start with Notebook_01.ipynb and progress sequentially**

## Data Sources

- **AAPL.csv**: Historical Apple Inc. stock price data used for financial analysis exercises
- **Synthetic Data**: Randomly generated market data for multi-asset portfolio analysis

## Key Learning Outcomes

After completing this project, I've gained experience in:

- **Data Manipulation**: Advanced pandas operations for time series data
- **Financial Analysis**: Processing and analyzing real stock market data
- **Visualization**: Creating both static (matplotlib) and interactive (plotly) charts
- **Strategy Development**: Building and testing simple trading algorithms
- **Performance Evaluation**: Measuring and comparing strategy effectiveness

## Technologies Used

- **Python**: Primary programming language
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computing and array operations
- **Matplotlib**: Static data visualization
- **Plotly**: Interactive financial charts
- **Jupyter**: Interactive development environment

## Future Enhancements

As I continue learning, I plan to expand this project with:

- [ ] More sophisticated trading strategies
- [ ] Risk management and portfolio optimization
- [ ] Machine learning models for price prediction
- [ ] Real-time data integration
- [ ] Advanced statistical analysis
- [ ] Performance attribution analysis

## Learning Resources

This project was developed as part of my data science learning journey. Key concepts explored include:

- Time series analysis fundamentals
- Financial data processing workflows
- Quantitative trading strategy development
- Data visualization best practices
- Python for finance applications

---

*This is a learning project focused on building practical data science skills through hands-on financial data analysis and strategy development.*
