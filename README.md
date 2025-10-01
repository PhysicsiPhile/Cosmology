# Cosmology Parameter Estimation – MCMC & Fisher Matrix

This repository contains my Jupyter notebooks where I explore **parameter estimation in cosmology** using two main approaches:

1. **Markov Chain Monte Carlo (MCMC)** sampling, and
2. **Fisher Matrix forecasting techniques**.

The notebooks document both the **code implementations** and the **underlying concepts** step by step, with explanations, derivations, and analysis. The goal is not just to run the code but to **understand how cosmological parameters are extracted from data** and how uncertainties are quantified.

---

## Contents

* 📓 **Jupyter Notebooks**:

  * Walkthroughs of parameter estimation techniques.
  * Implementation of MCMC algorithms (e.g., Metropolis-Hastings).
  * Example likelihood functions relevant to cosmology.
  * Playing with the Fisher Matrix as a tool for forecasting constraints.

* 🧠 **Conceptual Notes**:

  * How likelihoods are constructed in cosmology.
  * Role of priors in Bayesian inference.
  * Comparison between Fisher Matrix approximations and full MCMC results.
  * Visualization of posteriors, confidence contours, and parameter degeneracies.

---

## Major Ideas

* **MCMC in Cosmology**:

  * Sampling the posterior distribution of cosmological parameters.
  * Estimating uncertainties and correlations.
  * Understanding convergence and mixing of chains.

* **Fisher Matrix**:

  * Using derivatives of the likelihood to estimate expected constraints.
  * Advantages (fast, approximate) and limitations (valid only near Gaussian likelihoods).
  * Exploring how Fisher forecasts compare with MCMC posteriors.

---

## Requirements

The notebooks are written in **Python 3** and make use of common scientific libraries:

* `numpy`
* `scipy`
* `matplotlib`
* `emcee` (for MCMC)

You can install dependencies with:

```bash
pip install -r requirements.txt
```

---

## How to Use

1. Clone the repo:

   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   cd <repo-name>
   ```
2. Launch Jupyter:

   ```bash
   jupyter notebook
   ```
3. Open the notebooks and follow along with the explanations and code cells.

---

## Notes

* These notebooks are **exploratory and educational** — not meant as production-ready pipelines.
* I am still experimenting with **different likelihood forms, samplers, and Fisher matrix toy models**.
* Expect some rough edges, but the main aim is to document the learning process.

---

## Future Directions

* Adding examples with **real cosmological data (CMB / LSS)**.
* Exploring more advanced MCMC samplers (e.g. Hamiltonian Monte Carlo).
* Extending Fisher Matrix analysis to multi-parameter, correlated cases.

---

## License

MIT License – feel free to use, modify, and share with attribution.
