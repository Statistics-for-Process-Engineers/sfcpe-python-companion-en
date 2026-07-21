# Section 4: Regression Analysis and Factorial Design

This section introduces linear regression, weighted linear regression, nonlinear regression, regression diagnostics, and factorial experimental design in Python using **NumPy**, **SciPy**, and **Matplotlib**.

The first notebook summarises the principal regression formulas and their Python implementations. The remaining notebooks apply these methods to worked examples involving parameter estimation, model evaluation, nonlinear optimisation, and factorial design.

## Topics Covered

* Linear regression in matrix form
* Weighted linear regression
* Nonlinear least-squares regression
* Estimating model parameters with NumPy and SciPy
* Calculating fitted values and residuals
* Model variance and standard deviation
* Fisher information and parameter covariance matrices
* Confidence intervals for model parameters
* Confidence and prediction intervals for model outputs
* Regression, error, and total sums of squares
* Calculating (R^2) and adjusted (R^2)
* Assessing overall model significance with an F-test
* Checking regression assumptions using residual diagnostics
* Identifying and removing potential outliers
* Numerical optimisation with `scipy.optimize.minimize`
* Nonlinear fitting with `scipy.optimize.curve_fit`
* Constructing factorial-design regression matrices
* Estimating main effects and interaction effects
* Selecting significant model terms using normal probability plots and F-tests

## Notebooks

### 4.1.1 Regression Formulae

[`Section 4.1.1_ MATLAB Formulae Regression.ipynb`](Section%204.1.1_%20MATLAB%20Formulae%20Regression.ipynb)

This notebook summarises the mathematical formulas and corresponding NumPy and SciPy methods used for:

* ordinary linear regression;
* weighted linear regression;
* nonlinear regression;
* parameter confidence intervals;
* mean-response and prediction intervals;
* sums of squares;
* F-tests;
* (R^2) and adjusted (R^2).

For nonlinear regression, the notebook also introduces the use of numerical optimisation and Jacobian matrices for estimating parameter uncertainty.

### 4.2.1 Linear Regression

[`Section 4.2.1_ Linear Regression.ipynb`](Section%204.2.1_%20Linear%20Regression.ipynb)

This notebook applies linear regression to the estimation of two virial parameters from experimental osmotic-pressure data.

It demonstrates how to:

* rewrite a theoretical relationship in linear matrix form;
* construct a regression design matrix;
* estimate parameters using the normal equations;
* calculate residuals and model standard deviation;
* construct confidence intervals for the estimated parameters;
* calculate SSR, SSE, TSS, and (R^2);
* assess overall model significance with an F-test;
* examine residual normality and residual patterns;
* remove a potential outlier and refit the model.

### 4.2.2 Nonlinear Regression

[`Section 4.2.2_ Nonlinear Regression.ipynb`](Section%204.2.2_%20Nonlinear%20Regression.ipynb)

This notebook estimates the parameters of a nonlinear relationship between osmotic pressure and the ratio of equilibrium to isotonic cell volume.

It demonstrates two approaches to nonlinear least squares:

1. minimising the sum of squared residuals with `scipy.optimize.minimize` and the Nelder–Mead method;
2. fitting the model directly with `scipy.optimize.curve_fit`.

The notebook also demonstrates how to:

* define a nonlinear model and objective function;
* select initial parameter estimates;
* calculate analytical parameter derivatives;
* construct a Jacobian matrix;
* calculate residuals and model standard deviation;
* approximate the parameter covariance matrix;
* construct confidence intervals for nonlinear-model parameters.

### 4.2.3 Factorial Design Example

[`Section 4.2.3_ Factorial Design Example.ipynb`](Section%204.2.3_%20Factorial%20Design%20Example.ipynb)

This notebook analyses a (2^4) factorial experiment for a distillation column.

The four investigated factors are:

* reboiler duty;
* feed temperature;
* reflux ratio;
* feed location.

The response is the purity of the overhead product.

The notebook demonstrates how to:

* represent experimental factor levels in coded form;
* construct a full factorial regression matrix;
* include main effects and two-, three-, and four-factor interactions;
* estimate all regression coefficients;
* use a normal probability plot to identify important effects;
* construct a reduced regression model;
* calculate the contribution of individual model terms;
* use F-tests to determine which coefficients are statistically significant.

## Running the Notebooks

The notebooks are designed to run in **Google Colab**.

Open each notebook in Colab and execute the cells in order. No additional data files or local Python installation are required.
