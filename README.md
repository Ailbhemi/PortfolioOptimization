# PortfolioOptimization
A portfolio optimization project using a non-convex formulation to maximize the Sharpe ratio, with Monte Carlo simulations to analyze the portfolio performance.

This repository contains a Jupyter notebook that demonstrates the use of a non-convex optimization formulation to optimize the Sharpe ratio in a portfolio. The notebook applies Monte Carlo simulations to generate a distribution of potential returns, and visualizes the outcomes.

## Project Overview

The goal of this project is to optimize a portfolio's Sharpe ratio by solving a non-convex optimization problem. This project also considers and compares convex approximations. The notebook includes the following key steps:

1. **Non-Convex Optimization**: Using a non-convex formulation to maximize the Sharpe ratio of the portfolio.
2. **Monte Carlo Simulation**: Running simulations to generate potential portfolio returns.
3. **Visualization**: Plotting the distribution of returns and providing key statistics (mean return, confidence intervals, etc.).
4. **Risk Analysis**: Analyzing the distribution of returns, with special attention to the downside risk indicated by a fat left tail in the distribution.