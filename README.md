# Investment Portfolio Optimization Using Markowitz Modern Portfolio Theory (MPT)

This project demonstrates how to **optimize an investment portfolio** using **Markowitz’s Modern Portfolio Theory (MPT)**. The primary objective is to construct a portfolio that maximizes return for a given level of risk or minimizes risk for a given return, using historical data.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Key Features](#key-features)
3. [Setup Instructions](#setup-instructions)
4. [Dependencies](#dependencies)
5. [Usage](#usage)
6. [Project Structure](#project-structure)
7. [Results](#results)
8. [Future Work](#future-work)

## Project Overview
Markowitz's Modern Portfolio Theory (MPT) is a mathematical framework that aims to assemble a portfolio of assets to maximize expected return based on a given level of market risk. This project leverages MPT to optimize a portfolio by determining the **efficient frontier**—a set of optimal portfolios offering the maximum possible expected return for a given level of risk.

The key components of the project include:
- **Portfolio Construction**: Using historical stock price data to create an investment portfolio.
- **Efficient Frontier**: Identifying portfolios along the efficient frontier, which offer the best trade-off between risk and return.
- **Risk and Return Analysis**: Calculating key metrics like expected returns, portfolio variance, and Sharpe ratio.

## Key Features
- **Portfolio Optimization**: Optimizes a portfolio using Markowitz’s theory, focusing on minimizing risk for a given return or maximizing return for a given level of risk.
- **Efficient Frontier Visualization**: Plots the efficient frontier, showing the trade-off between risk and return for different portfolios.
- **Risk Management**: Implements risk-adjusted performance metrics such as the Sharpe ratio.
- **Stock Data Fetching**: Automatically fetches historical stock data for analysis using the `yfinance` library.
- **Visualization**: Plots the performance of portfolios, including individual asset risks and returns.

## Setup Instructions
To run this project on your local machine, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/aaryamanz/Investment-Portfolio-Optimization-Using-Markowitz-Modern-Portfolio-Theory.git
   cd Investment-Portfolio-Optimization-Using-Markowitz-Modern-Portfolio-Theory
   ```

2. **Install the required dependencies**:
   Ensure you have Python installed, then install the dependencies using:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Jupyter Notebook**:
   Open the notebook in Jupyter to explore the portfolio optimization process:
   ```bash
   jupyter notebook Portfolio_Optimization_using_MPT.ipynb
   ```

## Dependencies
The project requires the following Python libraries:
- `numpy`
- `pandas`
- `matplotlib`
- `yfinance`
- `scipy`

Install all dependencies by running:
```bash
pip install -r requirements.txt
```

## Usage
1. **Open the notebook** `Portfolio_Optimization_using_MPT.ipynb`.
2. **Follow the instructions** inside the notebook to load the stock data, calculate the optimal portfolio weights, and visualize the efficient frontier.
3. **Modify the asset tickers** and time periods to explore portfolio optimization with different sets of assets.

## Project Structure
```
Investment-Portfolio-Optimization-Using-Markowitz-Modern-Portfolio-Theory/
│
├── Portfolio_Optimization_using_MPT.ipynb  # Main Jupyter Notebook
├── README.md                               # Project documentation
├── requirements.txt                        # Python dependencies
└── data/                                   # Folder for data (if applicable)
```

## Results
The notebook provides the following outputs:
- **Efficient Frontier Plot**: Displays the risk-return trade-offs for different portfolios.
- **Optimal Portfolio Weights**: Lists the optimal allocation for each asset to achieve desired risk or return.
- **Performance Metrics**: Includes risk (standard deviation), expected return, and the Sharpe ratio for the optimized portfolio.

By following the notebook, you can construct and visualize an optimized portfolio using historical stock data.

## Future Work
Potential improvements for future iterations include:
- Adding more sophisticated models for expected returns, such as CAPM or factor models.
- Implementing real-time portfolio rebalancing.
- Expanding the analysis to include more asset classes like bonds, commodities, or cryptocurrencies.
- Exploring machine learning techniques for asset return forecasting.
