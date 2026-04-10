# Power-System-Optimization

A technical portfolio repository for energy systems modelling and optimization, built around PyPSA examples and custom mathematical analysis.

This project demonstrates capability in power system optimisation, electricity market modelling, unit commitment, AC/DC network coupling, and non-linear power flow methods.

## Why this repository

- Practical implementation of power system optimisation workflows
- Hands-on experience with PyPSA and optimization modelling
- Focus on market design, network constraints, and system planning
- Includes both notebook examples and analytical documentation

## Technical highlights

- **Electricity market modelling**
  - Nodal pricing / locational marginal price (LMP) analysis
  - Bidding zone modelling and congestion impact
  - Negative price behaviour and market dispatch dynamics

- **Unit commitment & dispatch**
  - Thermal unit start-up/shut-down modelling
  - Security-constrained dispatch
  - Rolling horizon optimisation for operational planning

- **Network modelling**
  - AC and DC network coupling
  - Meshed AC/DC systems with converter modelling
  - Linear optimal power flow (LOPF) and non-linear Newton-Raphson power flow

- **Optimization & mathematical analysis**
  - Objective functions, constraints, and mixed-integer formulations
  - Storage and hydro-economic dispatch
  - Ramp rates, reserve requirements, and multi-period optimisation

## Repository contents

- `electricity_mkt_bidding.ipynb` — Electricity market & bidding zone examples
- `unit_commitment.ipynb` — Unit commitment modelling and commitment logic
- `neg_prices_uc.ipynb` — Negative price behaviour in linearized unit commitment
- `meshed_ac_dc_network.ipynb` — AC/DC coupled network optimisation
- `german_example_1day_hourly_dispatch.ipynb` — German system dispatch + non-linear PF validation
- `sc_lopf.ipynb` — Security-constrained linear optimal power flow
- `newton-raphson_pf.ipynb` — Non-linear power flow using Newton-Raphson
- `neg_LMP-congestion.ipynb` — Congestion-driven negative LMP analysis
- `rolling_horizon.ipynb` — Rolling horizon optimisation for operational planning
- `rolling_horizon-water-storage.ipynb` — Seasonal storage valuation and water values
- `Optimization_Math.md` — Consolidated mathematical notes on optimisation methods

## Skills demonstrated

- Python-based energy system modelling
- Power system optimisation with PyPSA
- Mathematical formulation of energy system constraints
- Market and network analysis for power grids
- Energy storage and hydro resource planning

## Notes

This repository is a work in progress and is continuously expanded with new examples, analytical notes, and energy system use cases.