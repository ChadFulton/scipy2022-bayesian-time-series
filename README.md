# Bayesian Estimation and Forecasting of Time Series in Statsmodels

[``Statsmodels``](https://www.statsmodels.org/), a Python library for statistical and econometric analysis,
has traditionally focused on frequentist inference, including in its
models for time series data. This paper and Poster illustrates the powerful
features for Bayesian inference of time series models that exist in
``statsmodels``, with applications to model fitting, forecasting, time series
decomposition, data simulation, and impulse response functions.

*Suggestions for reading and using this Poster*

Our suggestion for using this Poster is as follows.

1. The most accessible place to start is the [paper](https://github.com/ChadFulton/scipy2022-bayesian-time-series/blob/main/Bayesian%20Estimation%20and%20Forecasting%20of%20Time%20Series%20in%20statsmodels.pdf). It is relatively short, and
   guides the reader through the main concepts and key code segments.
2. The poster itself is a Jupyter notebook, [`Poster.ipynb`](https://github.com/ChadFulton/scipy2022-bayesian-time-series/blob/main/Poster.ipynb), and it can be (a)
   run to reproduce the analysis and figures in the paper, and (b) copied and
   modified to apply these tools and concepts to whatever project the reader
   wishes!
3. For readers who wish to go further, additional resources on Bayesian analysis
   of time series models in Statsmodels are listed below.

More details about each of these follow:

*1. Paper*

Included in this repository is a draft of the paper
[`Bayesian Estimation and Forecasting of Time Series in Statsmodels.pdf`](https://github.com/ChadFulton/scipy2022-bayesian-time-series/blob/main/Bayesian%20Estimation%20and%20Forecasting%20of%20Time%20Series%20in%20statsmodels.pdf) that is
forthcoming in the Proceedings of the 21st Python in Science Conference (SciPy
2022). This paper introduces the time series models included in Statsmodels and
shows how to estimate their parameters using Bayesian methods. It also briefly
describes the relationship to other popular Python libraries for Bayesian
inference, including [PyMC](https://www.pymc.io/projects/docs/en/stable/learn.html), [PyStan](https://pystan.readthedocs.io/en/latest/), and [ArviZ](https://www.arviz.org/en/latest/).

*2. Poster*

The paper also provides code samples for several applications that include
parameter estimation, forecasting, and causal inference. To keep the paper
readable, the code included inline is only brief, but the Poster included in
this repostory, [`Poster.ipynb`](https://github.com/ChadFulton/scipy2022-bayesian-time-series/blob/main/Poster.ipynb), is a Jupyter notebook that contains the complete
code for performing the Bayesian analysis in the paper.

*3. Additional resources for Bayesian analysis of time series models in Statsmodels*


- [Autoregressive moving average (ARMA) model](https://www.chadfulton.com/topics/arma11_cpi_inflation.html).
  This Jupyter notebook shows how to estimate the parameters of an `SARIMAX`
  model (which is already built-in to Statsmodels) using Bayesian methods.
- [Stochastic volatility model](https://www.chadfulton.com/topics/stochastic_volatility_mcmc.html).
  This Jupyter notebook shows (a) how to create a custom state space model that
  represents a stochastic volatility process, (b) how to apply it to an exchange
  rate time series, and (c) how to then estimate the parameters using
  Bayesian methods.
- [Time-Varying Parameter Vector Autoregression (TVP-VAR) model](https://www.chadfulton.com/topics/statespace_tvpvar_mcmc_cfa.html).
  This Jupyter notebook shows (a) how to create a custom state space model that
  represents a TVP-VAR model, and (b) how to then estimate the parameters using
  Bayesian methods.
- [Dynamic stochastic general equilibrium (DSGE) economic model](https://www.chadfulton.com/topics/simple_rbc.html).
  This Jupyter notebook shows how to set up and solve a simple Real Business
  Cycle economic model, and how to estimate its structural parameters using
  Bayesian methods.
