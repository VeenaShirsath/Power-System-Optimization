# Power-System-Optimization
The purpose of this repository is to learn power systems modelling, mainly dispatch models and battery optimization.

## Topics covered
1. Time series forecasting 
2. Deterministic dispatch & merit order
3. Small LP dispach
4. Monte Carlo & Markov scenario generation
5. Battery fundamentals and SOC model
6. Multi‑period battery optimization
7. Energy risk modelling

## Projects description
### Project A (Production cost & stochastic dispatch)
	• Scope: Build a dispatch optimizer (Pyomo) for a small system (thermal + renewable). Generate demand/price scenarios using Monte Carlo and Markov chains to model renewable availability or generator outages.
	• Experiments: Compute expected production cost, cost distribution, reliability metrics, and show how stochastic modelling changes dispatch vs deterministic.

### Project B (Battery storage optimization)
	• Scope: Formulate battery operation as a multi‑period optimization (arbitrage or co‑optimizing with dispatch). Explore sizing and risk‑aware operation (e.g., CVaR objective).
	• Experiments: Profit vs size curves, sensitivity to price volatility, effect of including risk constraints.
