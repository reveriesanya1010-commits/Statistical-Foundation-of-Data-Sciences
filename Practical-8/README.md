# Practical 8: Decision Trees and Its Maxdepth

## Aim
To understand and implement a Decision Tree Classifier using the Pima Indians Diabetes Dataset and study how different maximum depth values affect the complexity and performance of the model.

## Objectives
- Understand the working of a Decision Tree Classifier.
- Separate input features and target variables.
- Split the dataset into training and testing sets.
- Build Decision Tree models with different maximum depth values.
- Compare model accuracy and performance.
- Visualize decision trees.
- Understand Entropy, Information Gain and Gini impurity.
- Identify the root node and understand decision-making.

## Libraries Used
- **Pandas:** Used for data manipulation and analysis.
- **NumPy:** Used for numerical operations.
- **Matplotlib:** Used for data visualization.
- **Scikit-learn:** Used for model training, testing and evaluation.

## Dataset
Pima Indians Diabetes Dataset (diabetes.csv)

## Practical Implementation

### 1. Import Libraries
Import the required libraries for data analysis, visualization and machine learning.

### 2. Load Dataset
Load the diabetes dataset and explore its structure, rows and columns.

### 3. Feature Selection
Separate independent variables (X) and the dependent variable (y). The Outcome column represents whether a person has diabetes.

### 4. Split the Dataset
Divide the dataset into training and testing sets using an 80:20 ratio.

### 5. Build a Decision Tree with Lower Depth
Train a Decision Tree Classifier using Entropy and a maximum depth of 4.

### 6. Evaluate the Model
Make predictions and calculate accuracy and classification report.

### 7. Visualize the Decision Tree
Plot the decision tree to understand its structure and decision-making process.

### 8. Build a Decision Tree with Greater Depth
Train another Decision Tree Classifier using a maximum depth of 20 and compare its performance.

### 9. Compare Decision Tree Models
Compare the accuracy of both models to understand how depth affects performance and complexity.

### 10. Calculate Information Gain and Gini
Analyze feature importance using Entropy and Gini impurity.

### 11. Identify Root Node
Find the feature and threshold used at the root node of the decision tree.

## Technologies Used
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## Conclusion
This practical helped in understanding Decision Tree classification, feature selection, Entropy, Information Gain, Gini impurity and the effect of maximum depth on model performance. Two decision trees with different depths were trained and compared.
