# Cryptocurrencies

###Description

In this challenge we are tasked with using unsupervised machine learning to create a report that classifies cryptocurrencies that are being traded in the market in groups that can be marketed as new investment oportunities to clients.

### *Deliverable #1*

 - Keep all the cryptocurrencies that are being traded.
 - Drop the IsTrading column.
 - Remove rows that have at least one null value.
 - Filter the crypto_df DataFrame so it only has rows where coins have been mined.
 - Create a new DataFrame that holds only the cryptocurrency names, and use the crypto_df DataFrame index as the index for this new DataFrame.
 - Remove the CoinName column from the crypto_df DataFrame since it's not going to be used on the clustering algorithm.


![image](https://user-images.githubusercontent.com/104601282/200095007-08a84a66-4f59-449b-8079-ed4a339edf6a.png)



![image](https://user-images.githubusercontent.com/104601282/200095113-be95bb82-fa05-45f3-946e-7ff5be0f1b87.png)


![image](https://user-images.githubusercontent.com/104601282/200095129-a8002e7b-7ce9-4f3b-a714-e7601050f2fa.png)


![image](https://user-images.githubusercontent.com/104601282/200095182-c92be5f1-be36-4590-9cef-24bf36788066.png)



### *Deliverable #2* 

 - The PCA algorithm reduces the dimensions of the X DataFrame down to three principal components (10 pt)
 - The pcs_df DataFrame is created and has the following three columns, PC 1, PC 2, and PC 3, and has the index from the crypto_df DataFrame (10 pt)



![image](https://user-images.githubusercontent.com/104601282/200095230-18b00516-0bbb-4853-a87d-d8474b8b8fab.png)


![image](https://user-images.githubusercontent.com/104601282/200095250-c1b1cbb2-0212-40b2-af7f-506288a376cb.png)



### *Deliverable #3*

 - The K-means algorithm is used to cluster the cryptocurrencies using the PCA data, where the following steps have been completed:
 - An elbow curve is created using hvPlot to find the best value for K (10 pt)
 - Predictions are made on the K clusters of the cryptocurrencies’ data (5 pt)
 - A new DataFrame is created with the same index as the crypto_df DataFrame and has the following columns: Algorithm, ProofType, TotalCoinsMined, TotalCoinSupply, PC    1, PC 2, PC 3, CoinName, and Class (5 pt)

![image](https://user-images.githubusercontent.com/104601282/200095317-9c56a95d-c35d-4031-a0a7-d6e5b69fac3b.png)


![image](https://user-images.githubusercontent.com/104601282/200095331-b64ceca0-522b-4f41-aa35-f539c24cc2aa.png)


![image](https://user-images.githubusercontent.com/104601282/200095348-9fc04e0c-298d-4bd1-b0fe-da6a0cc87f9c.png)


