# Practical 11: Monte Carlo and Markov Chain Monte Carlo (MCMC)

## Aim
To understand and implement Monte Carlo simulation and Markov Chain Monte Carlo techniques for modeling sunspot data and estimating parameters of a Gamma distribution.

## Objectives
- Understand Monte Carlo simulation.
- Understand Markov Chain Monte Carlo techniques.
- Analyze historical sunspot data.
- Fit a Gamma distribution to positive sunspot observations.
- Generate random samples using Monte Carlo simulation.
- Implement the Metropolis-Hastings algorithm.
- Visualize trace plots and histograms.
- Estimate Gamma distribution parameters using MCMC.

## Libraries Used
- **Pandas:** Used for data manipulation and analysis.
- **NumPy:** Used for numerical computations.
- **Matplotlib:** Used for visualization.
- **Seaborn:** Used for statistical visualization.
- **SciPy:** Used for Gamma distribution functions and statistical calculations.

## Dataset
Monthly Sunspot Dataset

## Practical Implementation

### 1. Import Libraries
Import the required Python libraries for data analysis, simulation and visualization.

### 2. Load and Preprocess Sunspot Data
Load the monthly sunspot dataset, select the required historical period and remove missing observations.

### 3. Visualize Sunspot Activity
Create a time-series plot to understand changes in sunspot activity over time.

### 4. Fit a Gamma Distribution
Fit a Gamma distribution to positive sunspot observations and estimate its shape and scale parameters.

### 5. Visualize Gamma Distribution
Create a histogram of sunspot counts and compare it with the fitted Gamma probability density curve.

### 6. Perform Monte Carlo Simulation
Generate 1,000 random samples from a Gamma distribution using shape parameter a = 4 and scale parameter b = 10.

### 7. Visualize Monte Carlo Samples
Plot histograms of the first 50 samples, all samples and the last 50 samples.

### 8. Implement Metropolis-Hastings Algorithm
Implement the Metropolis-Hastings algorithm to estimate the shape and scale parameters of the Gamma distribution.

### 9. Visualize MCMC Results
Create trace plots and histograms of the sampled parameters after removing burn-in samples.

### 10. Estimate Parameters
Calculate the mean, median and 95% credible intervals for the estimated shape and scale parameters.

## Technologies Used
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy

## Conclusion
This practical helped in understanding Monte Carlo simulation and Markov Chain Monte Carlo techniques. Historical sunspot data was analyzed using a Gamma distribution, random samples were generated through Monte Carlo simulation, and the Metropolis-Hastings algorithm was implemented to estimate distribution parameters.
