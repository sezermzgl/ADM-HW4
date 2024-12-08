# Homework 4 - ADM Project

## Overview

This project is part of the "Algorithmic Methods for Data Mining" course and addresses the tasks outlined in Homework 4. The focus of the project is on clustering techniques, evaluating clustering performance, and generating insights from the results. The notebook `main-2.ipynb` implements the solutions for the required tasks.

## Objectives

- Implement clustering algorithms to group data points.
- Evaluate clustering performance using metrics like silhouette scores and Davies-Bouldin index.
- Generate visualizations to interpret clustering results.

## File Structure

- `main-2.ipynb`: The primary notebook containing the implementation of clustering algorithms and performance evaluations.
- `dbi_scores.csv`: Stores Davies-Bouldin Index (DBI) values for different clustering configurations.
- `silhouette_scores.csv`: Contains silhouette scores for the evaluated clustering models.
- `README.md`: This file, explaining the project structure and details.

## Methodology

1. **Data Preprocessing**:
   - Load and clean data to ensure compatibility with clustering methods.

2. **Clustering Implementation**:
   - Applied various clustering algorithms (e.g., k-means, hierarchical clustering) to group data points.
   - Experimented with different parameters, such as the number of clusters.

3. **Evaluation Metrics**:
   - Calculated silhouette scores to assess how well each cluster is defined.
   - Computed the Davies-Bouldin Index to measure cluster separation and compactness.

4. **Visualizations**:
   - Generated plots to visualize the clustering results and evaluate the quality of clusters.

## Results

- **Silhouette Analysis**: Demonstrated the compactness and separation of clusters for each configuration.
- **DBI Scores**: Provided insights into which clustering configurations perform best under the Davies-Bouldin metric.
- The results indicate optimal cluster configurations for the dataset.

## How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/sezermzgl/ADM-HW4.git
   ```
2. Navigate to the project directory:
   ```bash
   cd ADM-HW4
   ```
3. Open `main-2.ipynb` in a Jupyter Notebook environment.
4. Run the notebook cells sequentially to execute the code.

## Dependencies

- Python 3.8+
- Jupyter Notebook
- NumPy
- pandas
- scikit-learn
- matplotlib
- seaborn
