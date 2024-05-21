# Principal Component Analysis 

## Objective 
Use clustering methods to reduce dimensionality in a large dataset  

## How to run 
```
git clone https://github.com/cbotts/PCA/
jupyter notebook /PCA/Botts_PCA_ALS.ipynb
```

## Data
This dataset contains patient health information. The target feature is ALS diagnosis. 

## Methods 
Redundant variables were removed and the reduced dataset was standardized. A KMeans model was built and silhouette score used to determine the optimal number of clusters. PCA was used to reduce predictive inputs to match the optimal number of clusters. 

## Conclusion 
The steps were effective at reducing the large number of features in the dataset. However, after PCA, there were not distinctive groups. 
