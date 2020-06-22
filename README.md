# Customer Segmentation for a Wholesale Dealer

## Introduction
Market/customer segmentation is a unsupervised learning task which has a lot of applications. It helps business and company owners to employ targetted marketing and customer retention campaigns.

In this project, we are trying to segment the customers of a wholesale distributor.

## Data Description
The dataset includes the annual spending of the customers across different product categories. It also provides information on the region the customer belongs to and their channel (there are 2 channels, 1. Hotel/Restaurant/Cafe and 2. Retail).

The dataset contains records of 440 customers and contains 8 features.

![DF](https://github.com/muhammedsalihk/Customer-Segmentation-for-a-Wholesale-Dealer/blob/master/Images/Initial%20DF.png)

## Methodology
Before going ahead with the clustering exercise, a detailed exploratory analysis was perfomed on the data so that the variation of sales across the different regions and channels could be captured.

![EDA Sample](https://github.com/muhammedsalihk/Customer-Segmentation-for-a-Wholesale-Dealer/blob/master/Images/Image%202.png)

The channel and region features are not very relevant in the clustering exercise and hence were not considered. We used k-means clustering for the analysis.  The ideal number of clusters was determined using the elbow method.

![Elbow Method](https://github.com/muhammedsalihk/Customer-Segmentation-for-a-Wholesale-Dealer/blob/master/Images/Image%203.png)

Although there is no clear elbow, 5 clusters seemed to be a good choice.

## Results
The dataset was then scaled using the StandardScaler class in sklearn and then clustered. A summary of the resultant clusters is provided below.

![Results 1](https://github.com/muhammedsalihk/Customer-Segmentation-for-a-Wholesale-Dealer/blob/master/Images/Results%201.png)

![Results 2](https://github.com/muhammedsalihk/Customer-Segmentation-for-a-Wholesale-Dealer/blob/master/Images/Results%202.png)
