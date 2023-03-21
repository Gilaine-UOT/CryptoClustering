# CryptoClustering

### Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes


## Data Preparation

To normalise the data from the original CSV file, I used the scikit-learn StandardScaler() module. I then used the scaled data to create a DataFrame.

![](https://github.com/Gilaine-UOT/CryptoClustering/blob/main/Images/Capture1.PNG)


## Finding Value of K 

Using the elbow method, I determined the best value for K by plotting the elbow curve on a line graph with hvplot and visually identifying the optimal k value using the inertia values computed with different values of K.

![](https://github.com/Gilaine-UOT/CryptoClustering/blob/main/Images/Capture2.PNG)


## Finding the Best Value for k Using the PCA Data

![](https://github.com/Gilaine-UOT/CryptoClustering/blob/main/Images/Capture4.PNG)

## Find the Best Value for k Using the PCA Data

![](https://github.com/Gilaine-UOT/CryptoClustering/blob/main/Images/Capture5.PNG)
