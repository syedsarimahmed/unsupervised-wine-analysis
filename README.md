# Unsupervised Wine Analysis

**View the full live report here:** https://syedsarimahmed.github.io/unsupervised-wine-analysis/

## Project Overview
This project applies unsupervised statistical machine learning techniques to the UCI Wine dataset to explore whether wines can be grouped based solely on their chemical characteristics. 

## Methodology
The analysis pipeline includes:
* **Exploratory Data Analysis (EDA):** Visualizing distributions and correlations.
* **Data Standardization:** Scaling features to ensure equitable contribution to the model.
* **Principal Component Analysis (PCA):** Reducing dimensionality to visualize groupings.
* **Clustering:** Utilizing K-Means and Hierarchical Clustering to identify cultivar groupings.

## Key Findings
* Both clustering models successfully recovered the underlying three-group structure of the wine cultivars.
* Hierarchical clustering provided a cleaner separation between types compared to K-means.
