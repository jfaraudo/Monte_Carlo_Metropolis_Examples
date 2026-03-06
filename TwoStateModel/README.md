# Two State Model

Monte Carlo simulation of an ideal two state model (no interaction between the N particles or atoms):
- Ground state (label s=-1) with energy 0
- Excited state (label s=+1) with energy $$\epsilon$$

The units are dimensionless, being $$k_BT/\epsilon$$ the reduced (dimensionless) temperature

The analytical solution of the model can be found elsewhere for example [here](https://farside.ph.utexas.edu/teaching/355/Surveyhtml/node234.html)

There are two (main) versions of the code:

- The files "two_states_snapshots" (both the .py and the google collab) execute the simulation for a given T
- The files two_states and two_states_several_T execute explore a full rage of temperature (both in the .py and notebook version). There is one version with interactive plots and one version that only plots the results at the end.

