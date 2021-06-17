# Applying K-Means on Call-of-Duty Player Information Dataset
This project applies the clustering algorithm (K-Means) on the Call-of-Duty players' info dataset. 
<br/>
Link to the Kaggle Post: https://www.kaggle.com/pouyashiri/cod-player-clustering
<br/>
Link to the Kaggle Dataset used: https://www.kaggle.com/aishahakami/call-of-duty-players
<br/>

Steps:
<br/>
* At the beginning, the columns are modified.
* There are two pipelines considered: preprocessing and clustering. The preprocessing includes standardization and applying PCA for dimension reduction. 
* The optimum number of clusters (K in K-Means) and the number of PCA components are found. 
* Finally, the discovered clusters are labeld based on the current level of the players.

# Requirements
scikit-learn, pandas, matplotlib, seaborn, numpy
