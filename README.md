# Cryptocurrencies
## Purpose

This project aimed to utilize unsupervised machine learning to group cryptocurrencies using a clustering algorithm and reduce the dimension and principal component analysis (PCA). The analysis created a report that included the trading market for cryptocurrencies and how they could be regrouped into a classification system for investments. The generated information would be offered to customers interested in a new cryptocurrency investment portfolio. 
 
## Results
- Dataset was cleaned and formatted into a working clustering algorithm set plus standardized the data with StandardScaler. 

Data Visualization is listed below:

### Elbow Curve
- The elbow curve justifies four clusters are needed for the dataset.

![elbow Curve](https://user-images.githubusercontent.com/96746207/174707958-34886407-4167-44ed-8ced-073c9b225ea7.png)

### 3D Scatter Plot with Three PCA Data and Clusters

![3D scatter](https://user-images.githubusercontent.com/96746207/174707967-574f636b-e420-4ad1-8557-66ef5a33b81b.png)

### Table with Tradable Cryptocurrencies
- Table confirms 532 tradable cryptocurrencies.

![table](https://user-images.githubusercontent.com/96746207/174707970-9c789b19-d3d5-4c08-b29a-ecae01c0e753.png)

### 2D Hvplot Scatter Plot
- Created a scatter plot with x= “TotalCoinsMined”, y= ”TotalCoinSupply”, and by= ”Class”. The scatter plot will show the coin name when hovering over the data point. 

![hvplot](https://user-images.githubusercontent.com/96746207/174707976-2957a377-fecc-49bc-afdf-d55fda78911e.png)
   
## Summary
- 532 tradeable cryptocurrencies are available, and a customer portfolio will be attainable.  
- Majority of the tradeable cryptocurrencies are grouped tighter near low coin supply and low coins mined.
- Turtle Coin, class 3, has a very high coin supply with a low coin mined and bit torrent, class 2, has both a high coin supply and high coin mined.   
 







