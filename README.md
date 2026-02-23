# Power-System-Optimization
This repository is my personal platform for learning power systems modelling. It includes operational, coupling, and planning examples from PyPSA documentation, my own additions on the math of these optimization methods/examples, and beyond. 

## Topics covered (to be added)
1. Electricity Markets and Bidding Zones
2. Unit Commitment
3. Newton-Raphson Power Flow


## Files (from [PyPSA documentation](https://docs.pypsa.org/latest/examples/examples/):)
* electricity_mkt_bidding.ipynb: Electricity markets
* unit_commitment.ipynb: Unit Commitment models
* neg_prices_uc.ipynb: Negative Prices in Linearized Unit Commitment
* meshed_ac_dc_network.ipynb: This example demonstrates how to optimise meshed AC-DC networks in PyPSA. The example has a 3-node AC network coupled via AC-DC converters to a 3-node DC network.
* german_example_1day_hourly_dispatch.ipynb: In this example, the dispatch of generators is optimised using the linear optimisation, then a non-linear power flow is run on the resulting dispatch. This example covers the German power system (roughly in the mid 2010s) for a single day at hourly resolution.