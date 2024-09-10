# Principal Component Analysis (PCA) on Iris Dataset

## Overview
This project demonstrates how to apply **Principal Component Analysis (PCA)** to the popular Iris dataset. PCA is a dimensionality reduction technique that helps simplify data while retaining most of the original variance. The repository showcases steps including scaling the data, applying PCA, and visualizing the explained variance.

## Dataset
The Iris dataset contains 150 samples of iris flowers, categorized into three species: *Setosa*, *Versicolour*, and *Virginica*. Each sample includes four features:
- Sepal length
- Sepal width
- Petal length
- Petal width

## Key Steps
1. **Data Preprocessing:**
   - Load and explore the Iris dataset.
   - Standardize the data using `StandardScaler`.

2. **Applying PCA:**
   - Perform PCA on the scaled data.
   - Analyze the principal components and the explained variance.

3. **Visualization:**
   - Plot a scree plot to show the explained variance ratio of each principal component.
   - Create a bar plot to visualize the variance covered by the principal components.

## Visualization
The scree plot helps determine the number of significant principal components by displaying the proportion of explained variance. A bar chart offers a visual breakdown of the variance for each component.

## Conclusion
From the PCA results, we observe that the first two principal components capture the majority of the variance (approximately 96%). Thus, we can reduce the dataset dimensions from 4 to 2 while retaining most of the information, making PCA a useful tool for visualization and simplification.
