# Section 3: Statistical Distributions and Hypothesis Testing

This section introduces statistical distributions, hypothesis testing, p-values, and confidence intervals in Python using **NumPy** and **SciPy**.

The first notebook summarises the main methods available in `scipy.stats`. The remaining notebooks apply these methods to detailed hypothesis-testing examples.

## Topics Covered

* Working with statistical distributions in `scipy.stats`
* Probability density and probability mass functions
* Cumulative distribution functions
* Quantile functions
* Generating random samples
* Normal, Student's t, chi-square, F, binomial, and Poisson distributions
* Continuous and discrete distribution parameters
* One-sided and two-sided hypothesis tests
* Calculating and interpreting p-values
* Constructing confidence intervals
* Comparing conclusions obtained from critical values, p-values, and confidence intervals
* Comparing two sample variances with an F-test

## Notebooks

### 3.1 Summary of SciPy Methods for Statistical Distributions

[`Section_3_1_Summary_of_SciPy_Methods_for_Statistical_Distributions.ipynb`](Section_3_1_Summary_of_SciPy_Methods_for_Statistical_Distributions.ipynb)

This notebook introduces the unified interface used by distributions in `scipy.stats`.

It demonstrates the following methods:

* `pdf()` — probability density function for continuous distributions;
* `pmf()` — probability mass function for discrete distributions;
* `cdf()` — cumulative distribution function;
* `ppf()` — quantile or inverse cumulative distribution function;
* `rvs()` — random-variable generation.

The notebook also introduces the general principles of hypothesis testing for two-sided, left-sided, and right-sided alternatives. It explains how to calculate critical values, p-values, and confidence intervals.

### 3.2.1 Testing a Mean Against a Theoretical Value

[`Section_3_2_1_Detailed_Examples.ipynb`](Section_3_2_1_Detailed_Examples.ipynb)

This notebook presents a one-sample hypothesis test for a population mean when the population variance is unknown.

It demonstrates how to:

* calculate the sample mean and sample standard deviation;
* formulate a two-sided hypothesis test;
* calculate the Student's t-test statistic;
* determine the critical value;
* calculate the corresponding p-value;
* construct a 95% confidence interval;
* compare the conclusions from the critical-value, p-value, and confidence-interval approaches.

### 3.2.2 Comparing Two Sample Variances

[`Section_3_2_2_Detailed_Examples.ipynb`](Section_3_2_2_Detailed_Examples.ipynb)

This notebook compares the variability of product-quality measurements obtained using two drying options.

It demonstrates how to:

* calculate unbiased sample variances;
* formulate a one-sided test for two population variances;
* construct an F-test statistic;
* determine the appropriate degrees of freedom;
* calculate the corresponding p-value;
* interpret the result in the context of process selection.

## Running the Notebooks

The notebooks are designed to run in **Google Colab**.

Open each notebook in Colab and execute the cells in order. No additional data files or local Python installation are required.
