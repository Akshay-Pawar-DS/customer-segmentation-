# customer-segmentation-

## Introduction :

This project applies customer segmentation to the customer data from a company and derives conclusions and data driven ideas based on it.

## Dataset :

Invoice No:

Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.

StockCode

Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.

Description

Product (item) name. Nominal.

Quantity

The quantities of each product (item) per transaction. Numeric.

InvoiceDate

Invice Date and time. Numeric, the day and time when each transaction was generated.

UnitPrice

Unit price. Numeric, Product price per unit in sterling.

CustomerID

Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.

Country

Country name. Nominal, the name of the country where each customer resides.


## Approach :

The differences in customers' behaviour, demographics, geographies, etc. help in classifying them in groups. Learning about different groups in the customer can help with following:

Target Marketing Client understanding Optimal product placement Searching for new customers Revenue growth

#### Recency-Frequency-Monetary (RFM) model to determine customer value:

The RFM model is quite useful model in retail customer segmentation where only the data of customer transaction is available. RFM stands for the three dimensions:

Recency – How recently did the customer purchase? 

Frequency – How often do they purchase? 

Monetary Value – How much do they spend? 

A combination of these three attributes can be defined to assign a quantitative value to customers. e.g. A customer who recently bought high value products and transacts regularly is a high value customer.

Initially, the data is subject to important stages in an analytics pipeline: exploratory analysis, preprocessing, feature engineering and standardizaton. Then, the unsupervised classification technique, K-means clustering algorithm and hierachical clustering is used to determine the ideal segments of customers. Silhouette analysis and related cluster visualizations are leveraged to deduce the optimum value of "K" (number of clusters) in the algorithm. The observations from the results are elaborately discussed before reaching the conclusion from the business perspective.


## Conclusion :

- The Dataset was large enough summing around 5.4 lakh samples with most of the
samples from UK.

- High sales volume can be observed for November also most revenue generating
months are October , November and December.

- For the segmentation we used RMF Technique to create working table as it is most
common segmentation technique.

- Using elbow method, we have generated optimal number of clusters.

- By using K-Means and Hierarchical clustering we formed appropriate clusters for the
customer data.
