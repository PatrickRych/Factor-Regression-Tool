# Factor-Regression-Tool

## Market Regression Engine: Beta & Correlation Framework 

![RegressionAnalysis](https://github.com/user-attachments/assets/d0c6c802-794b-4ffc-aa1f-628652c97dc5)

Built a dynamic regression model that was inspired by Kris Abdelmessih. Kris emphased the importance of analyzing assets response to each other - we can quantify these relations by using statistical relationships like beta, correlation, and R². This tool quantifies systematic risk vs idiosyncratic alpha—a critical step in building hedged or relative-value trades.

Kris emphasized the importance of Beta (i.e. rolling period 21d) to capture both the strength and the scale of how the asset moves relative to the reference. 

**Core Features:**
Beta Decomposition: Measures asset sensitivity (e.g., VXX vs SPY) using β = Correlation × Volatility Ratio

- Rolling Beta & Correlation: Detects structural regime shifts in relationships over time

- Statistical Output: Includes p-values, t-stats, and standard errors for signal confidence

- Risk Modeling: Quantifies how much of an asset's movement is hedgeable and what remains as alpha opportunity

**Use Cases:**
- Hedge sizing with: Hedge Notional = β × Position

- Dispersion trades (e.g., short QQQ / long SPY beta-neutral pairs)

- Regime detection via decaying R² and correlation breakdowns


## Project Archive 

| <a href="https://github.com/PatrickRych/Project">LandingPage </a>
| <a href="https://github.com/PatrickRych/Portfolio-Manager">Project Archive </a>
****
