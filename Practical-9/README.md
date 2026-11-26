# Practical 9: K-Nearest Neighbors (KNN)

## Aim
To implement the K-Nearest Neighbors classification algorithm using the Iris dataset and study how different values of K affect classification performance.

## Objectives
- Understand the working of the K-Nearest Neighbors algorithm.
- Perform exploratory data analysis.
- Separate independent features and target variables.
- Split the dataset into training and testing sets.
- Apply feature scaling using StandardScaler.
- Train a KNN classifier and predict flower species.
- Evaluate the model using a confusion matrix and classification report.
- Compare error rates for different K values.
- Visualize actual and predicted classes using PCA.

## Libraries Used
- **Pandas:** Used for data manipulation and analysis.
- **NumPy:** Used for numerical calculations.
- **Matplotlib:** Used for visualization.
- **Seaborn:** Used for statistical visualization.
- **Scikit-learn:** Used for classification, scaling and evaluation.

## Dataset
Iris Dataset

## Practical Implementation

### 1. Import Libraries
Import the necessary libraries for data analysis, visualization and machine learning.

### 2. Load the Iris Dataset
Load the Iris dataset and convert it into a Pandas DataFrame.

### 3. Exploratory Data Analysis
Display the first five rows, statistical descriptions and average feature values grouped by species.

### 4. Split the Dataset and Apply Feature Scaling
Separate the input features and target variable, divide the data into training and testing sets, and standardize the features using StandardScaler.

### 5. Train the KNN Model
Train a KNN classifier using K = 5 and make predictions on the test data.

### 6. Evaluate the Model
Calculate the accuracy score and create a confusion matrix to compare actual and predicted classes.

### 7. Generate Classification Report
Calculate precision, recall, F1-score and support for each flower species.

### 8. Compare Error Rates for Different K Values
Calculate error rates for K values ranging from 1 to 20.

### 9. Visualize Error Rates
Plot a graph of K values against error rates to understand model performance.

### 10. Find the Best K
Identify the K value with the minimum error rate and train the final KNN model.

### 11. Visualize Classification Results
Use PCA to reduce the test data to two dimensions and visualize actual and predicted flower classes.

## Technologies Used
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Conclusion
This practical helped in understanding the K-Nearest Neighbors classification algorithm. Feature scaling, model evaluation, confusion matrices and classification reports were used to analyze the performance of the model. Different K values were compared to identify the best K, and PCA was used to visualize the classification results.
