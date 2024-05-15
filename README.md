# Online-Retail-Customer-Segmentation
![customer segment](https://github.com/Asohail115/Online-Retail-Customer-Segmentation/assets/80779216/b9978ce8-d47f-408f-a6e6-cb9846e05119)
# Problem Description :
In this project, your task is to identify major customer segments on a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.
# Data Description
A transnational data set with transactions occurring between 1st December 2010 and 9th December 2011 for a UK-based online retailer. The company mainly sells unique all-occasion gifts. and Many customers of the company are wholesalers.
# Attribute Information :
- InvoiceNo: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.
- StockCode: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.
- Description: Product (item) name. Nominal.
- Quantity: The quantities of each product (item) per transaction. Numeric.
- InvoiceDate: Invice Date and time. Numeric, the day and time when each transaction was generated.
- UnitPrice: Unit price. Numeric, Product price per unit in sterling.
- CustomerID: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.
- Country: Country name. Nominal, the name of the country where each customer resides.
# Challenges:
- Data cleaning
- RFM analysis
- Deciding optimal number of clusters
# Model Summary :
Built a clustering model using K-means and Agglomerative clustering to identify major customer segments on transactions data for the UK based non-store online retail. Engineered new features to obtain new features such as RFM, busist days, time, month, RFMGroup, and RFMScore for getting more details about the customer. Obtained optimal number of clusters using Silhouette Analysis, Elbow Method and visual inspection of dendogram resulting from Hierarchical Clustering . 
# Conclusion :
### Here are the final number of clusters obtained.
![Screenshot (9)](https://github.com/Asohail115/Online-Retail-Customer-Segmentation/assets/80779216/e35fa751-781d-4ec8-bad5-283d29e4c1bf)
- We got optimal number of clusters=2 with the help of Elbow method, Silhouette score.

