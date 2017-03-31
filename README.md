# Udacity-MLND-Project-3
Unsupervised machine learning models for segmenting distributor customers.

## Purpose
The purpose of this project was to gain hands-on familiarity with unsupervised learning technniques, such as PCA and clustering. This project is part of the Udacity Machine Learning Engineer Nanodegree. The data source was product spending data collected for customers of a wholesale distributor in Lisbon, Portugal, used for identifying customer segments hidden in the data. 

## Project Overview
I explored the data by selecting a small subset to sample and determined if any product categories highly correlated with one another. I preprocessed the data by scaling each product category and then identifying (and removing) unwanted outliers. With the good, clean customer spending data, I applied PCA transformations to the data and implemented clustering algorithms to segment the transformed customer data. I compared the segmentation found with an additional labeling and considered ways this information could assist the wholesale distributor with future service changes. Specificially, this wholesaler appears to have two distinct types of customers, with different purchasing habits and needs. This information can be used to inform delivery and logistical considerations.

## Technical Highlights
This project was designed to give a hands-on experience with unsupervised learning and work towards developing conclusions for a potential client on a real-world dataset. Many companies today collect vast amounts of data on customers and clientele, and have a strong desire to understand the meaningful relationships hidden in their customer base. Being equipped with this information can assist a company engineer future products and services that best satisfy the demands or needs of their customers.

Technical skills learned during this project:

* How to apply preprocessing techniques such as feature scaling and outlier detection.
* How to interpret data points that have been scaled, transformed, or reduced from PCA.
* How to analyze PCA dimensions and construct a new feature space.
* How to optimally cluster a set of data to find hidden patterns in a dataset.
* How to assess information given by cluster data and use it in a meaningful way.

## Additional Documents

* customer_segments-Fox.ipynb: Jupyter notebook file containing the code and analyses for this project. In order to run, type:
`jupyter notebook customer_segments-Fox.ipynb`

* customer_segments-Fox.html: Static HTML version of the Jupyter notebook analysis. In order to view, open the file using any browser (via 'File' - 'Open File' and selecting the customer_segments-Fox.html file)
