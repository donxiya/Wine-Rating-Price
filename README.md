# Wine-Rating-Price

# Project Goal

The primary goal of this project is to build an intelligent wine recommendation system that assists consumers in discovering wines aligned with their taste preferences. Whether a user provides a favorite wine or simply specifies filters like price range, rating, and wine type, the system utilizes unsupervised machine learning techniques to identify wines that are similar in character and appeal.

To this end, we employed K-Means Clustering and Gaussian Mixture Models (GMM) to group wines based on features such as price, rating, and production year. This approach enables a user-friendly, data-driven wine discovery experience.

# Identify an Unsupervised Learning Problem

This project aims to help consumers find wines similar to ones they like by applying unsupervised learning. Since the dataset lacks labeled categories, we use clustering methods to group wines based on features like price, rating, and year.

We explored three main algorithms:

## K-Means Clustering: Quickly groups wines into clusters by minimizing distance to cluster centers. It’s simple but assumes equal-sized, spherical clusters.

## Hierarchical Clustering: Builds a tree of clusters without needing to predefine the number. It helps visualize how wines group together at different levels of similarity.

## Gaussian Mixture Model (GMM): A flexible model that assigns probabilities to clusters, allowing for overlapping and elliptical groupings. It captures more subtle patterns than K-Means.

These methods let us segment wines and support a recommendation system based on feature similarity.
