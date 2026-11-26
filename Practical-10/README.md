# Practical 10: Principal Component Analysis (PCA)

## Aim
To understand and implement Principal Component Analysis (PCA) using the Wine dataset and reduce the dimensionality of data while retaining maximum possible information.

## Objectives
- Understand the concept and importance of PCA.
- Explore the Wine dataset using descriptive statistics.
- Visualize data using boxplots and scatterplots.
- Calculate and understand the covariance matrix.
- Standardize the dataset using StandardScaler.
- Apply PCA to reduce the number of features.
- Understand principal components and explained variance.
- Visualize wine classes using principal components.

## Libraries Used
- **Pandas:** Used for data manipulation and analysis.
- **NumPy:** Used for numerical operations.
- **Matplotlib:** Used for data visualization.
- **Seaborn:** Used for statistical visualization.
- **Scikit-learn:** Used for dataset loading, scaling and PCA implementation.

## Dataset
Wine Dataset

## Practical Implementation

### 1. Import Libraries
Import the required libraries for data analysis, visualization and PCA.

### 2. Load the Wine Dataset
Load the Wine dataset and convert it into a Pandas DataFrame.

### 3. Display Descriptive Statistics
Use the `describe()` function to understand the statistical properties of the dataset.

### 4. Visualize Wine Classes
Create boxplots to compare feature distributions across different wine classes.

### 5. Explore Relationships Between Features
Create scatterplots to visualize relationships between selected features.

### 6. Calculate Covariance Matrix
Calculate the covariance matrix to understand how numerical features vary together.

### 7. Standardize the Dataset
Apply StandardScaler to bring features to a common scale.

### 8. Apply PCA
Apply Principal Component Analysis to reduce the dimensionality of the standardized dataset.

### 9. Analyze Explained Variance
Examine the explained variance and cumulative explained variance of the principal components.

### 10. Visualize Principal Components
Visualize the wine classes using the reduced principal component representation.

## Technologies Used
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Conclusion
This practical helped in understanding Principal Component Analysis and dimensionality reduction. The Wine dataset was explored, standardized and transformed into principal components to retain important information while reducing the number of dimensions.
