This project simulates stock price movements using Geometric Brownian Motion (GBM). 
Monte Carlo simulations are commonly used in quantitative finance for pricing derivatives, risk management, and forecasting.

## Methods
- Geometric Brownian Motion model:
  S(t+1) = S(t) * exp((mu - 0.5*sigma^2)*dt + sigma*sqrt(dt)*Z)
- 1,000 simulations of 252 trading days (1 year horizon)
- Parameters: 
  - Initial Price = $150
  - Drift (mu) = 5%
  - Volatility (sigma) = 20%
  - Risk-free rate (r) = 3% (for option pricing)

## Results
- Simulated stock paths show a distribution of possible outcomes.
- Expected stock price after 1 year: X (fill with your result).
- Probability stock > $160: Y%.
- European Call Option (K=160) Monte Carlo Price: Z.

## Next Steps
- Extend to other derivatives (put options, barrier options).
- Test different parameters (volatility, drift).
- Apply to real stock data (e.g., AAPL, TSLA).
