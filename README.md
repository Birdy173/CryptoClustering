# Crypto Clustering

This Jupyter notebook performs clustering analysis on cryptocurrency market data. It includes preprocessing steps, feature extraction, data transformation, and visualization to help identify potential clusters among different cryptocurrencies based on price change percentages over various time intervals.

## Project Overview

The main objective of this project is to apply clustering techniques to cryptocurrency data to discover natural groupings. By examining price changes over different time periods, we attempt to identify similarities between cryptocurrencies that may reflect market trends or other factors.

## Features

- **Data Loading & Cleaning**: Load cryptocurrency data and clean it for analysis, including handling missing values and transforming data types as necessary.
- **Feature Engineering**: Generate features based on price change percentages over various time intervals (e.g., 24 hours, 7 days, 30 days, 1 year).
- **Data Transformation**: Apply scaling to normalize the data, which is essential for effective clustering.
- **Clustering**: Implement clustering algorithms, such as K-Means, to group cryptocurrencies based on the chosen features.
- **Visualization**: Display clustering results and analyze the data with interactive visualizations to understand the formed clusters.

## Installation

To run this notebook, you'll need Python and several packages. It is recommended to install packages within a virtual environment.

```bash
# Install dependencies
pip install pandas hvplot scikit-learn
```

## Usage

1. **Data Preparation**: Load your cryptocurrency dataset. This notebook assumes the data includes columns for cryptocurrency price changes over various time intervals.
2. **Running the Notebook**: Open the notebook and execute each cell to process data, apply clustering, and visualize results.
3. **Interpreting Results**: Use the plots to analyze how different cryptocurrencies are clustered based on historical price trends.

## Dependencies

- `pandas`: For data manipulation and analysis.
- `hvplot`: For interactive plotting of data.
- `scikit-learn`: For data scaling and clustering.

## Results and Analysis

The final output includes visualizations of clusters, allowing for interpretation of cryptocurrency groupings. Each cluster may represent cryptocurrencies with similar market behavior over time.

