# Crypto_Cluster
The purpose behind the project was to test my financial python programming as well as my understanding of machine learning concepts.

This project was completed using jupyter lab and the following libraries.

## Libraries
The libraries used for this challenge are:
- pandas 
- hvplot 
- pathlib
- PCA
- KMeans
- StandardScaler


## Steps
1. I started the challenge by importing our csv data, we then generated the summary statistics, followed by plotting our dataframe to get a better understanding of the data.
2. I then prepared the data using StandardScaler and cleaned it using pandas
3. After cleaning the data I created an elbow curve in order to find the optimal value for our model.
4. Once the best value for K has been found, we start clustering the data using the KMeans method, followed by plotting the data in a scatter plot.
5. Next I optimized the data with the PCA method in order to find the best value for K, I then plotted the data into an elbow curve in order to better understand the data.
6. I then clustered the data from the PCA method using the KMeans method and plotted a scatter plot in order to better understand the data. 
7. Then I plotted both elbow curves next to each other using a composite plot and analyzed which elbow curve was better for analyzing the data.
8. Finally I plotted both the scatter plots next to each other using a composite plot and analyzed with scatter plot gave me more detailed information. 
