## Optimal Powr Flow problems

## Unit Commitment problems

## Economic dispath problems (Linear solved as an LP)

#### Decision variables
$n$ generators *g*
#### Parameters:
1. Generator maximum capacities: $0 \leq p_g \leq \bar{P}_g$
2. Load $D$ MW

**Objective function:** $$\min_{p_g} = \sum_g c_g p_g$$

**Constraints:**
(a) Power Balance (energy conservation): dual gives the market clearing price $$\sum_g p_g = D$$

(b) Generator capcity limits: For each generator $0 \leq p_g \leq \bar{P}_g$.

(c) *(If network-constrained economic dispatch)* Generator dispatch: For each generator *g* at bus *i*: $$p_{g,i} \geq 0$$

(d) *(If network-constrained economic dispatch)* Transmission flow: For each link *l* in the network, $$f_l \in [-\bar{F}_l, \bar{F}_l]$$



#### How the optimizer reasons: (merit order principle)