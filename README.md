# Bitcoin EDA and Price Prediction
<img src="https://image.hurimg.com/i/hurriyet/75/0x0/66cedb0b601c04688fba0d68.jpg" alt="Bitcoin Prediction Model" width="600" />
This is the Bitcoin Historical Dataset. The dataset provides information about historical price data for Bitcoin from January 1, 2018, to September 6, 2024.


Bitcoin Dataset: https://www.kaggle.com/datasets/novandraanugrah/bitcoin-historical-datasets-2018-2024

Dataset columns:
* Open time: First hour of 15 min.
* Open price: First price within 15 minutes
* High price: Highest price in 15 min.
* Low price: Lowest price in 15 mins
* Close price: Last price within 15 minutes
* Volume: If a total of $1 billion worth of buying and selling transactions took place in Bitcoin in one day, that is its trading volume.
* Close time: Last hour of 15 min.
* Quote asset volume: It refers to the total purchasing demand at a particular price level.
* Number of trades: It refers to the total number of transactions (buys, sales or transfers) made in a certain time period.
* Taker buy base asset volume: It means buying at the best bid price available at that moment.
* Taker buy quote asset volume: It refers to the total amount of assets that buyers are willing to purchase at a particular price level.
* Ignore: Some transactions or data entries may be "ignored" due to a bug or incompatibility in the Bitcoin software or a wallet application.

You can also review it on my Kaggle account: https://www.kaggle.com/code/hazalgltekin/bitcoin-eda-and-price-prediction

### Steps Taken
I first examined this dataset, then applied the EDA steps. I did feature engineering, and finally, I created a model and made a prediction.

1. Dataset Review
2. EDA(Explorarity Data Analysis)
  * Find missing values
  * Delete of Missing Value
  * Find features with one value
  * Explore the categorical features
  * Find categorical feature distrubition
  * Explore the numerical features
  * Find discrete numerical features
  * Find continuous numerical features
  * Distrubition of continuous numerical features
  * Relation between continuous numerical features and label
  * Find outliers in numerical features
  * Handling Outliers
3. Future Engineering
  * Calculating and visualizing averages of four different price types
  * Visualizing Bitcoin price change percentage distribution
  * Visualizing the density distribution of Bitcoin prices using Kernel Density Estimation (KDE)
4. Modeling
  * Removing categorical variables from the model
  * Split Dataset into Training set and Test set
  * Model Selection
