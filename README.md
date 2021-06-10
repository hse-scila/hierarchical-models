# Hierarchical topic models

## Renyi entropy

Lemmatized datasets are stored as `csv` files in `datasets` folder. Phi matrices are stored as `csv` files in `phi` folder.

Jupyter notebooks (`ipynb`) contain Renyi entropy calculation for different models.

## Entropic Approach to Hierarchical Cluster Analysis

Test dataset (`datasets/small_dataset.feather`) contains anonymized data of user-profiles from  Russian online social network Vkontakte (VK).

Jupyter notebook (`Hierarchical_clustering_small_dataset.ipynb`) contains the procedure of hierarchical clustering and calculation of Renyi entropy for different hierarchical levels, i.e., different dendrogram cuts.

Feather file `datasets/small_dataset_matrixZ.feather` contains the results of hierarchical clustering. 
