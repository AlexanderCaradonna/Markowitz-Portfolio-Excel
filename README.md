# 📈 Portfolio Optimization & CAPM Analysis of Canadian Stocks

This project was completed as part of a **Finance course at Concordia University**. It demonstrates portfolio optimization using the Markowitz model and evaluates the CAPM for a selection of Canadian stocks using Excel.

---

## 🎯 Project Objectives

- 📊 Build an optimal portfolio of five Canadian stocks based on weekly returns (Feb 19, 2024 – Feb 10, 2025).
- 📉 Calculate risk (covariance matrix) and expected returns.
- ⚖️ Determine portfolio weights including a risk-free asset for a risk-averse investor.
- 📈 Compute portfolio performance metrics such as expected return and Sharpe ratio.
- 📉 Estimate stock betas against the S&P/TSX Composite Index (market portfolio).
- 🔍 Test the Capital Asset Pricing Model (CAPM) validity using regression analysis.

---

## 🛠️ Tools & Data

- **Data Source:** Yahoo Finance for historical stock prices and market index.
- **Timeframe:** Weekly adjusted close prices, one year.
- **Software:** Microsoft Excel with Analysis ToolPak enabled for regressions.

---

## 📁 Project Structure

- Sheet `1-A`: Weekly returns calculation and covariance matrix of the selected stocks.
- Sheet `1-B`: Application of the Markowitz model to find optimal portfolio weights.
- Sheet `1-C`: Calculation of expected return and Sharpe ratio of the complete portfolio.
- Sheet `1-D`: Contains calculations for the optimal weight of the risky portfolio within the complete portfolio, as well as the weight of each individual security within the risky portfolio.
- Sheet `1-E`: Analysis of an equal-weight portfolio and comparison with the optimized portfolio.
- Sheet `2`: Performed regression analysis to estimate each stock's beta using the S&P/TSX index as the market portfolio. Then ran a second regression of mean returns vs. betas to test the validity of CAPM.



---

## 📌 Assumptions

- Risk-free rate assumed at 2.8% annually.
- Investor’s coefficient of risk aversion assumed to be 3

---

## 🔍 Methodology

### Part 1: Portfolio Optimization

- Selected 5 Canadian stocks.
- Calculated weekly returns, mean returns, and covariance matrix.
- Applied Markowitz portfolio theory with risk aversion coefficient.
- Included a risk-free asset (annual rate: 2.8%).
- Calculated expected return and Sharpe ratio for the optimal portfolio.
- Compared with an equally weighted portfolio.

### Part 2: Beta Estimation & CAPM Testing

- Used S&P/TSX Composite Index as the market portfolio.
- Performed regressions of stock returns on market returns to estimate beta.
- Tested CAPM by regressing average returns against betas.
- Analyzed regression results (R-squared, intercept, slope) for model validity.

---

💾 Data Source

Weekly adjusted closing prices for each stock and the market index (S&P/TSX) were obtained from Yahoo Finance for the period February 19, 2024 – February 10, 2025. This data was used to calculate returns, estimate betas, and test CAPM.

---
