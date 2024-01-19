# CryptoClustering
## Cryptocurrency Market Analysis

## Description
This repository contains code and analyses for clustering cryptocurrency market data. The project involves normalizing the data, performing K-means clustering, and applying Principal Component Analysis (PCA) to reduce dimensionality and optimize clustering. The goal is to group cryptocurrencies based on their market behavior over different time periods and to understand the underlying patterns in the data.

## Files
- `crypto_market_data.csv`: The dataset containing cryptocurrency market data.
- `crypto_analysis.ipynb`: Jupyter Notebook with the analysis code and visualizations.

## Technologies
- Python
- Pandas: For data manipulation and analysis.
- Scikit-learn: For applying K-means clustering and PCA.
- Matplotlib: For creating visualizations.

## Setup and Installation
1. Ensure Python is installed on your machine.
2. Install required Python packages:
   ```
   pip install pandas scikit-learn matplotlib
   ```
3. Clone the repository:
   ```
   git clone https://github.com/juanlavieri/CryptoClustering.git
   ```
4. Navigate to the repository directory and open the Jupyter Notebook:
   ```
   jupyter notebook crypto_analysis.ipynb
   ```

## Usage
Run the Jupyter Notebook `crypto_analysis.ipynb` to see the analysis process, from data loading and preprocessing to clustering and PCA. The notebook contains comments and markdown cells explaining each step.

## Analysis Overview
- **Data Preparation:** Data is loaded and normalized using `StandardScaler`.
- **K-Means Clustering:** Applied to the normalized data to group cryptocurrencies.
- **Elbow Method:** Used to determine the optimal number of clusters (k).
- **PCA:** Reduces the dimensionality of the data and optimizes clustering.
- **Cluster Visualization:** Scatter plots to visualize clusters in original and PCA-transformed data.
- **Feature Influence:** Analysis of the influence of each feature on the principal components.

## Results
The analysis clusters cryptocurrencies based on market behavior, revealing patterns and groupings that might not be immediately apparent. PCA further aids in understanding the most influential features and simplifies the data for better visualization and interpretation.

## Contributing
Contributions, issues, and feature requests are welcome. 
