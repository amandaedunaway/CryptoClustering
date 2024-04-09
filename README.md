# CryptoClustering
Module 19 Challenge

### Outline
The purpose of the Crypto_Clustering.ipynb file is to apply unsupervised learning techniques to pricing data and compare the results to determine which model better fits the data. The analysis utilizes Pandas, HVPlot, and SKLearn. 

First, the csv file, which contains pricing information for different cryptocurrencies at different points in time, is imported from the Resources folder, and the data is scaled. Next, a for loop is used to to find the value of inertia that correponds to each value of `k`, and the resulting elbow curve is plotted to determine the optimal value of `k`. This value of `k` is then used to place each data point into a cluster, and the data is plotted by clusters.

Next, a PCA model with three components is created. The same steps are performed for the PCA data to determine the optimal value for `k` and plot the clusters. 

Finally, a composite plot of the elbow curves and a composite plot of the clusters are utilized to visually compare the results.


### Resources
To create the composite plot, I used the [documentation page](https://holoviz.org/tutorial/Composing_Plots.html) provided in the challenge instructions.