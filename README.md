# CryptoClustering

=====================

The code for this assignment is  in the file `crypto_clustering.py`. The  code is follows KMean modeling and PCA technique for dimensionality reduction.

**Question:** What is the total explained variance of the three principal components?

**Answer:** PCA1 : 0.3719856, PCA2: 0.34700813, PCA3: 0.17603793

* **Question:** What is the best value for `k` when using the PCA data?

  * **Answer:** best value for k is 5 when using the PCA data

* **Question:** Does it differ from the best k value found using the original data?

  * **Answer:** No,  the best value for k is the same (5) when using the original data and the PCA data

* **Question:** Which features have the strongest positive or negative influence on each component? 
 
* **Answer:** 
    - For PCA1, price_change_percentage_1y and price_change_percentage_200d has positive influence
    - For  PCA2, price_change_percentage_30d and price_change_percentage_60d has positive influence

