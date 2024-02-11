# Recommendation Systems Overview

In this module, we review the scope and plan for the course, define what recommendation systems are, review the different types of recommendation systems and discuss common problems that arise when developing recommendation systems.

## Learning Objectives

- Compare the various types of recommendation systems.
- Anticipate the problems that can arise when building a recommendation system.
- Recognize common use cases for recommendation systems.

## Course Overview

- [Video - Introduction](https://www.coursera.org/learn/recommendation-models-gcp/lecture/cTBH0/introduction)

- [Video - Getting Started with Google Cloud Platform and Qwiklabs](https://www.coursera.org/learn/recommendation-models-gcp/lecture/4Zi8R/getting-started-with-google-cloud-platform-and-qwiklabs)

- [Reading - How to Send Feedback](https://www.coursera.org/learn/recommendation-models-gcp/supplement/Quo3m/how-to-send-feedback)

## Recommendation Systems Overview

- [Video - Introduction](https://www.coursera.org/learn/recommendation-models-gcp/lecture/vNFsS/introduction)

- [Video - Types of Recommendation Systems](https://www.coursera.org/learn/recommendation-models-gcp/lecture/i2S4t/types-of-recommendation-systems)

- [Video - Content-Based or Collaborative](https://www.coursera.org/learn/recommendation-models-gcp/lecture/Z62uc/content-based-or-collaborative)

- [Video - Recommendation System Pitfalls](https://www.coursera.org/learn/recommendation-models-gcp/lecture/qqdus/recommendation-system-pitfalls)

- [Video - Discussion](https://www.coursera.org/learn/recommendation-models-gcp/lecture/kmcri/discussion)

---

# Content-Based Recommendation Systems

In this module, we demonstrate how to build a recommendation system using characteristics of the users and items.

## Learning Objectives

- Measure the similarity of elements in an embedding space.
- Discuss the mechanics of content-based recommendation systems.
- Build a content-based recommendation system.

## Building a Simple Vector-Based Model

- [Video - Content-Based Recommendation Systems](https://www.coursera.org/learn/recommendation-models-gcp/lecture/oGF9N/content-based-recommendation-systems)

- [Video - Similarity Measures](https://www.coursera.org/learn/recommendation-models-gcp/lecture/r9E1l/similarity-measures)

- [Video - Building a User Vector](https://www.coursera.org/learn/recommendation-models-gcp/lecture/h9DM8/building-a-user-vector)

- [Video - Making Recommendations Using a User Vector](https://www.coursera.org/learn/recommendation-models-gcp/lecture/aaduY/making-recommendations-using-a-user-vector)

- [Video - Making Recommendations for Many Users](https://www.coursera.org/learn/recommendation-models-gcp/lecture/aK9EK/making-recommendations-for-many-users)

- [Video - Lab intro: Create a Content-Based Recommendation System](https://www.coursera.org/learn/recommendation-models-gcp/lecture/sYvEa/lab-intro-create-a-content-based-recommendation-system)

- [Lab - Create a Content-Based Recommendation System](./Labs/content_based_by_hand.ipynb)

- [Video - Lab Solution: Create a Content-Based Recommendation System](https://www.coursera.org/learn/recommendation-models-gcp/lecture/NfhNj/lab-solution-create-a-content-based-recommendation-system)

## Building a Content-Based Recommendation System with a Neural Network

- [Video - Using Neural Networks for Content-Based Recommendation Systems](https://www.coursera.org/learn/recommendation-models-gcp/lecture/KZJvd/using-neural-networks-for-content-based-recommendation-systems)

- [Video - Lab Intro: Create a Content-Based Recommendation System Using a Neural Network](https://www.coursera.org/learn/recommendation-models-gcp/lecture/wXPN0/lab-intro-create-a-content-based-recommendation-system-using-a-neural-network)

- [Lab - Create datasets for the Content-based Filter](./Labs/content_based_preproc.ipynb)

- [Lab - Create a Content-Based Recommendation System Using Neural Networks](./Labs/content_based_using_neural_networks.ipynb)

- [Video - Lab Solution: Create a Content-Based Recommendation System Using a Neural Network](https://www.coursera.org/learn/recommendation-models-gcp/lecture/tWx6t/lab-solution-create-a-content-based-recommendation-system-using-a-neural-network)

---

# COLLABORATIVE FILTERING RECOMMENDATION SYSTEMS

In this module, we show how the data of the interactions between users and items from many different users can be combined to improve the quality of predictions.

## Learning Objectives

- Identify why user interaction data can lead to novel and high quality recommendations.
- Recognize what matrix factorization is, why it's important, and the tradeoffs of various approaches.
- Explain how the ALS factorization algorithm works (Alternative Least Squares vs. Item).

## ALS, a Matrix Factorization Algorithm For Collaborative Filtering

- [Video - Types of User Feedback Data](https://www.coursera.org/learn/recommendation-models-gcp/lecture/nz2IO/types-of-user-feedback-data)

- [Video - Embedding Users and Items](https://www.coursera.org/learn/recommendation-models-gcp/lecture/gyzRs/embedding-users-and-items)

- [Video - Factorization Approaches](https://www.coursera.org/learn/recommendation-models-gcp/lecture/qqIv5/factorization-approaches)

- [Video - The ALS Algorithm](https://www.coursera.org/learn/recommendation-models-gcp/lecture/rIWHH/the-als-algorithm)

- [Video - Preparing Input Data for ALS](https://www.coursera.org/learn/recommendation-models-gcp/lecture/W4lq0/preparing-input-data-for-als)

## Implementing ALS in TensorFlow

- [Video - Creating Sparse Tensors For Efficient WALS Input](https://www.coursera.org/learn/recommendation-models-gcp/lecture/aZH4F/creating-sparse-tensors-for-efficient-wals-input)

- [Video - Instantiating a WALS Estimator: From Input to Estimator](https://www.coursera.org/learn/recommendation-models-gcp/lecture/jijRZ/instantiating-a-wals-estimator-from-input-to-estimator)

- [Video - Instantiating a WAL Estimator: Decoding TFRecords](https://www.coursera.org/learn/recommendation-models-gcp/lecture/rF8z7/instantiating-a-wal-estimator-decoding-tfrecords)

- [Video - Instantiating a WALS Estimator: Recovering Keys](https://www.coursera.org/learn/recommendation-models-gcp/lecture/RVlVp/instantiating-a-wals-estimator-recovering-keys)

- [Video - Instantiating a WALS Estimator: Training and Prediction](https://www.coursera.org/learn/recommendation-models-gcp/lecture/0nfWU/instantiating-a-wals-estimator-training-and-prediction)

- [Video - Lab Intro: Collaborative Filtering with Google Analytics Data](https://www.coursera.org/learn/recommendation-models-gcp/lecture/UqtvA/lab-intro-collaborative-filtering-with-google-analytics-data)

- [Lab - Collaborative filtering on Google Analytics Data](./Labs/wals.ipynb)

- [Video - Lab Solution: Collaborative Filtering with Google Analytics Data](https://www.coursera.org/learn/recommendation-models-gcp/lecture/JZiO0/lab-solution-collaborative-filtering-with-google-analytics-data)

- [Video - Issues with Collaborative Filtering](https://www.coursera.org/learn/recommendation-models-gcp/lecture/SZgwP/issues-with-collaborative-filtering)

- [Video - Productionized WALS Demo](https://www.coursera.org/learn/recommendation-models-gcp/lecture/XiFBO/productionized-wals-demo)

- [Video - Cold Starts](https://www.coursera.org/learn/recommendation-models-gcp/lecture/KmRBf/cold-starts)