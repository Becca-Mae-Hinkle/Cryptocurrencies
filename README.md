# Cryptocurrencies

## Overview

Unsupervised learning model is different from supervised learning in that an unsupervised model provides unlabeled data that the algorithm understands by extracting features and patterns on its own. In a supervised leaning model, the algorithm learns on a labeled dataset, and helps predict outcomes for unforeseen data. In other words, supervised learning is used when we know what we are looking for or what the output should be. Unsupervised learning is used when we don’t know the question we are asking the data.

In this module, we learned what unsupervised learning is used for, how to process data, how to cluster, how to reduce your dimensions, and how to reduce the principle components using PCA. Through the use of this knowledge, we will create an analysis for a client who is preparing to get into the cryptocurrency market.

## Results

We were given data that was not ideal since it was first processed to fit the machine learning modules. There was no know output so we determined that unsupervised learning would be the best option for the output we were wanting. Since we were looking at the different cryptocurrencies, we decided to use a clustering algorithm.

The first visualization we made was through the use of an elbow curve count.

<img width="636" alt="Elbow Curve" src="https://user-images.githubusercontent.com/94575416/160514844-7d8befaf-fd31-4432-92ac-4c1db0e68db6.png">

We combined the data and a 3D-scatter plot was made with the PCA data.

<img width="772" alt="3D Scatter Plot" src="https://user-images.githubusercontent.com/94575416/160515133-57a3680e-75d5-45e0-94ec-6892bbfc8492.png">
The last visulaization is of a hvplot.scatter plot. It was created using x=Total Coins Mined and y=Total Coin Supply

<img width="728" alt="2D Scatter Plot" src="https://user-images.githubusercontent.com/94575416/160515082-01fc37f3-14f2-4976-8e5d-026accd40a04.png">
