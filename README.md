# *Crypto Analysis Application*

In this application, i create a Jupyter notebook that clusters cryptocurrencies by their performance in different time periods. I then plot the results so that I can visually show the performance to the board.
I've created this application by using the following steps:
I Import the Data from a csv file onto my Jupyter notebook. I then prepare the data, and attempt to find the optimal value for k using the elbow curve. I use this data to cluster the different Cryptocurrencies with K-means.
In the second part of the application, I use PCA data to create my elbow curve which allows me to visualize the optimal value for k. Using this data, i again cluster the different Cryptocurrncies and visualize and compare the results.

Let me break down these steps. To start, I must find the optimal value for k. To do this, I code the elbow method algorithm to find the best value for k. I use a range from 1 to 11. I then plot a line chart with all the inertia values computed with the different values of k to visually identify the optimal value for k.
The next step is clustering the Cryptocurrencies with K-means. I initialize the K-means model with four clusters by using the best value for k, and fit the K-means model using the original data. I predict the clusters to group the cryptocurrencies using the original data, and view the resulting array of cluster values. I complete this step by using hplot to visualize the data.

I repeat this process by using PCA data in an attempt to visualize the differences when clustering the Cryptocurrencies using all the data from the dataframe, or just the 89% o the PCA data. With hvplot, it makes it easy to see the discrepencies.

---

## Technologies

This project leverages Python 3.7.

---

## Installation Guide

Before running this application, Python must be installed.

---

## Usage

Simply run the code to view the two different plots i have created. The plots are labeled to discern between the original data, and the PCA data.

---

## Contributors

Just me, and a little bit of help from module 10

## License

No license, feel free to copy the code any time.

