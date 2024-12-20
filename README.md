## Project: Bayesian Analysis and Modeling

### Overview
Estimated parameters for curve fitting a simulated dose response curve and estimated trend in precipitation data with regression using PyMC for Bayesian probabilistic programming. Sampled posterior distributions to plot uncertainty of estimates and/or checked priors.

### Some Details
These notebooks explore various Bayesian statistical methods using pyMC. 

In *pymc_weather.ipynb*...

>I use precipitation data from Sacramento, CA to look at the trend in rainfall between 1970 and 2020. I ask, "Does it rain less than it used to?" Fitting a simple linear regression with pyMC yields a slightly negative estimate for the slope parameter, indicating that perhaps it does rain less now. However, just looking at the amount of noise in the data, and the uncertainty in the estimates, there are clearly multiple factors affecting rainfall over the years.

In *pymc_ec50.ipynb*...

>I fit a logistic curve to simulated data. The data represent hypothetical drug treatment doses and the percent response induced by each dose in a so called 'dose response' curve. I fit the logistic curve via scipy's 'curvefit' as well as with pyMC. For the parameters fit with pyMC, I sample from the posterior distributions to visualize the uncertainty in the parameter estimates.

### Language
Python

### Packages Used
numpy, matplotlib, pymc, scipy

### Models
Linear Regression, Logistic Regression

### Resources
[PyMC documentation](https://www.pymc.io/projects/docs/en/latest/learn.html)

[Arviz documentation](https://python.arviz.org/en/latest/api/index.html)

[NOAA climate data](https://www.ncdc.noaa.gov/cdo-web/search)

