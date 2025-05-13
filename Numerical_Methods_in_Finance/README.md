# 📈 Numerical Methods in Computational Finance

This repository contains Python implementations of key numerical methods widely used in **quantitative finance** and **algorithmic trading**. These scripts are referenced in my personal paper titled *"The Analysis of Numerical Methods in Computational Finance"* — available on my [LinkedIn](https://www.linkedin.com/in/wilsonewilliams/).

## 🧠 Overview

The codebase serves as both an educational review and practical demonstration of foundational tools used in pricing derivatives, estimating implied volatility, and modeling stochastic processes. These methods are commonly encountered in:

- Option pricing models  
- Risk-neutral valuation  
- Quantitative trading research  
- Derivative analytics  

## 📂 Contents

| Module | Description |
|--------|-------------|
| `black_scholes.py` | Closed-form pricing of European options using the Black-Scholes formula |
| `monte_carlo_pricing.py` | Simulation-based option pricing using geometric Brownian motion |
| `binomial_tree.py` | Recombining binomial tree method for American and European options |
| `implied_volatility.py` | Newton-Raphson and bisection methods to solve for implied volatility |
| `greeks.py` *(optional)* | Sensitivity measures (Delta, Gamma, Vega, etc.) using finite differences |
| `utils.py` | Common functions for normal distribution, logging, and formatting |

## 📘 Key Concepts

- **Black-Scholes Model**: Analytical pricing using PDE solutions under log-normal assumptions  
- **Monte Carlo Simulation**: Empirical estimation of expected payoff under risk-neutral measure  
- **Binomial Tree Method**: Lattice-based pricing useful for American-style options  
- **Implied Volatility**: Root-finding to invert pricing models  
- **Finite Difference Methods** *(planned/experimental)*: Numerical PDE solutions for more complex payoffs  

## 🔧 Requirements

- Python 3.8+  
- NumPy  
- SciPy  
- Matplotlib