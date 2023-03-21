# CryptoClustering

#### Answer the following question: 

**Question:** What is the best value for `k`?

**Answer:** 
k=4 is the best choice. This, because:
* with k=4 we get a significant inertia reduction from 123 in k=3 to 79 in k=4. After that, reductions do not improve in more than 16 inertia units.  
* Graphically, the elbow on k=4 is also noticeable, because after k=4 the inertia start decreasing in a close to linear fashion.

#### Answer the following question: 

**Question:** What is the total explained variance of the three principal components?

**Answer:** 90%

We can see that 89.50% is the total variance explained by the three first principal components. That means that if we drop the other 4 components, we would be just losing a 10% of the variance in the data.

#### Answer the following questions: 

* **Question:** What is the best value for `k` when using the PCA data?

**Answer:** The reasons to choose again k=4 are similar than the ones to choose k=4 for the scalar original data:

* with k=4 we get a significant inertia reduction from 94 in k=3 to 50 in k=4. After that, reductions do not improve in more than 11 inertia units.  
* Graphically, the elbow on k=4 is also noticeable, because after k=4 the inertia start decreasing in a close to linear fashion.

* **Question:** Does it differ from the best k value found using the original data?

**Answer:** The difference from the original data is the Inertia itself at that point, which is 79 with k=4 with the standarized data, and only 50 using 3 PCA. Definetily a significant improvement. Not even with k=6 we got a level of 50 for the inertia with the standarized regular data. 

#### Answer the following question: 

  * **Question:** After visually analyzing the cluster analysis results, what is the impact of using fewer features to cluster the data using K-Means?

**Answer:** 

* Using a fewer amount of features reduces the amount of inertia. This happens because the reduction of dimensionality implies a reduction in the variance of the clustered data.  

* The original clusters and the pca clusters exactly match. That supports the use of dimentionality reduction. We dramatically reduced dimentions from seven to three, and still we got the same results. An impact of using fewer features is the benefit in reducing the resources needed to manage large amounts of data, without compromising optimal results.
