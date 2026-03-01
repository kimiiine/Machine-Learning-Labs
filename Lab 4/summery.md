In this section, we applied normalization, correlation analysis, and Principal Component Analysis (PCA) to the daily internet usage dataset to prepare it for machine learning and dimensionality reduction.

First, we applied Min-Max normalization, which rescales numerical features to a range between 0 and 1. This ensures that all features contribute equally to distance-based algorithms and prevents features with larger values from dominating the model.

Next, we applied Z-Score standardization, which transforms the data so that each feature has a mean of 0 and a standard deviation of 1. This centers the data and makes features comparable, which is especially important for algorithms such as Support Vector Machines and PCA.

After standardizing the data, we performed correlation analysis using a heatmap. This allowed us to examine the linear relationships between internet usage features. Correlation values close to 1 or −1 indicate strong relationships, while values close to 0 indicate weak or no relationship. This step helps determine whether dimensionality reduction techniques like PCA are useful.

Finally, we applied Principal Component Analysis (PCA) to reduce the dimensionality of the dataset. PCA transformed the original internet usage features into new uncorrelated variables called principal components. The first principal component captured the largest amount of variance in the data, while the second captured the next largest amount.
