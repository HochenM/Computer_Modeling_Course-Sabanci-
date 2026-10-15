# Week 2: Monte Carlo Sampling, Equilibration & Diagnostics

Implementation and analysis of the Metropolis algorithm on a 1D double-well potential ($U(x) = (x^2 - 1)^2$). 

### Key Topics Covered
* **Equilibration & Burn-in:** Discarding initial transient data and tracking convergence.
* **Metropolis Algorithm & Detailed Balance:** Enforcing $p_T(x) \propto \exp[-U(x)/k_BT]$.
* **Sampling Efficiency & Autocorrelation:** Analyzing trial move size ($\Delta x$) vs. decorrelation time.
* **Observables & Diagnostics:** Calculating $\langle x^2 \rangle$, running basin probabilities $P(x > 0)$, and validating histograms against target Boltzmann distributions.
