# Section 2: Descriptive Statistics and Visualisation

This section introduces descriptive statistics and data visualisation in Python using **NumPy**, **SciPy**, **pandas**, and **Matplotlib**.

The first notebook provides a summary of commonly used statistical functions and plotting methods, including their MATLAB equivalents. The second notebook applies these methods to an experimental dataset containing Reynolds number and friction factor measurements.

## Topics Covered

* Calculating descriptive statistics with NumPy and SciPy
* Mean, median, standard deviation, variance, range, quantiles, skewness, and median absolute deviation
* Matching MATLAB conventions, including sample variance and standard deviation
* Handling missing values represented by `NaN`
* Creating reproducible synthetic datasets
* Creating figures and subplots with Matplotlib
* Adding titles, axis labels, legends, and grids
* Creating bar charts, histograms, pie charts, line plots, boxplots, and scatterplots
* Creating heatmaps, logarithmic plots, 3D plots, and polar plots
* Creating normal probability plots with `scipy.stats.probplot`
* Loading experimental data from an Excel file with pandas
* Processing multi-level column headers
* Calculating statistics for individual experimental runs
* Comparing measured friction factors with a theoretical relationship

## Notebooks

### 2.1 Summary of Descriptive Statistics and Visualisation

[`Section_2_1_Summary_for_Descriptive_Statistics_and_Visualisation.ipynb`](Section_2_1_Summary_for_Descriptive_Statistics_and_Visualisation.ipynb)

This notebook summarises the main Python functions used for descriptive statistics and demonstrates a range of basic and advanced visualisation methods using reproducible synthetic data.

### 2.2 Example of Descriptive Statistics and Visualisation

[`Section_2_2_Example_for_Visualisation.ipynb`](Section_2_2_Example_for_Visualisation.ipynb)

This notebook applies the statistical and visualisation workflow to Reynolds number and friction factor measurements from several experimental runs.

## Running the Notebooks

The notebooks are designed to run in **Google Colab**.

Open each notebook in Colab and execute the cells in order. When running the second notebook, make sure that `FrictionFactorData.xlsx` is available in the Colab session.

No local Python installation is required.
