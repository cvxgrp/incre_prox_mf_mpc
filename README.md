# incre_prox_mf_mpc
This repo accompanies the paper [*Incremental Proximal Multi-Forecast Model Predictive Control*](https://web.stanford.edu/~boyd/papers/ip_mf_mpc.html).

To run the experiment, please install 
* [cvxpy](https://github.com/cvxgrp/cvxpy) >= 1.1.0a4
* [strat_models](https://github.com/cvxgrp/strat_models)
* [networkx](https://networkx.org/)

Please first run the notebook `energy_price_forecast_and_sample_generation.ipynb` to generate the forecasts and the samples.

Then run the notebook `energy_storage_multi_forecast_mpc.ipynb`, which contains code for single-forecast MPC, multi-forecast MPC, and incremental proximal multi-forecast MPC.

