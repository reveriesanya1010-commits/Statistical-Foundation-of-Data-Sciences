# Practical 12: Metropolis Algorithm and Deterministic Model

## Aim
To implement the Metropolis algorithm using the Markov Chain Monte Carlo technique and develop a deterministic population growth model using Python.

## Objectives
- Understand the Metropolis algorithm.
- Generate samples from a probability distribution using MCMC.
- Calculate acceptance rates.
- Visualize generated samples using trace plots and histograms.
- Calculate mean, variance and standard deviation.
- Understand deterministic mathematical models.
- Implement an exponential population growth model.
- Visualize population growth over time.

## Libraries Used
- **NumPy:** Used for numerical computations and sample generation.
- **Matplotlib:** Used for graphical visualization.
- **Seaborn:** Used for statistical visualization.
- **Pandas:** Used for data manipulation and population data representation.

## Practical Implementation

### Part A: Implementation of Metropolis Algorithm

### 1. Import Libraries
Import NumPy, Matplotlib and Seaborn for sampling and visualization.

### 2. Implement Metropolis Algorithm
Create a function that generates proposed values, calculates acceptance probabilities and accepts or rejects proposed samples.

### 3. Generate Samples
Generate 10,000 samples using the Metropolis algorithm with an initial value and proposal standard deviation.

### 4. Visualize the Samples
Create a trace plot to examine the movement of samples across iterations.

### 5. Compare Sample Distribution
Create a histogram of the generated samples and compare it with the standard normal distribution.

### 6. Calculate Statistical Measures
Calculate the mean, variance, standard deviation and acceptance rate of the generated samples.

### Part B: Deterministic Model

### 7. Define the Deterministic Population Growth Model
Define the initial population, growth rate and time period using an exponential population growth equation.

### 8. Calculate Population
Calculate population values over a period of 50 years and store the results in a DataFrame.

### 9. Visualize Population Growth
Create a line graph showing population growth over time.

### 10. Calculate Population Statistics
Calculate the initial population, growth rate, final population and maximum population.

### 11. Compare Population at Different Time Intervals
Display population values at selected time intervals to understand the growth pattern.

## Technologies Used
- Python
- Google Colab
- NumPy
- Pandas
- Matplotlib
- Seaborn

## Conclusion
This practical helped in understanding the Metropolis algorithm and deterministic modeling. The Metropolis algorithm was used to generate samples from a standard normal distribution, while an exponential deterministic model was used to calculate and visualize population growth over time.
