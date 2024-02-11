# Welcome to Image Understanding with TensorFlow on GCP

In this introductory module you will learn about the rapid growth in high-resolution image data available and the types of applications that it can be applied to. We’ll also cover image data as inputs to your model.

## Learning Objectives

- Recognize the applications for modern image classification models
- Breakdown images as visual data (height, width, and depth)
- Understand the limitations of comparing image data with traditional methods

## Welcome to the course

- [Video - Course Introduction](https://www.coursera.org/learn/image-understanding-tensorflow-gcp/lecture/gpAsA/course-introduction)

- [Video - Getting Started with Google Cloud Platform and Qwiklabs](https://www.coursera.org/learn/image-understanding-tensorflow-gcp/lecture/omPx6/getting-started-with-google-cloud-platform-and-qwiklabs)

## Images as Visual Data

- [Video - Images as Visual Data](https://www.coursera.org/learn/image-understanding-tensorflow-gcp/lecture/XrEK4/images-as-visual-data)

- [Video - Structured vs Unstructured Data](https://www.coursera.org/learn/image-understanding-tensorflow-gcp/lecture/8OxFN/structured-vs-unstructured-data)

## Course Feedback

- [Reading - How to Send Feedback](https://www.coursera.org/learn/image-understanding-tensorflow-gcp/supplement/Quo3m/how-to-send-feedback)

---

# Linear and DNN Models

We’ll start with a brief introduction where we’ll cover the image dataset you will be using for part of this course. Then we’ll tackle an image classification problem with a linear model in TensorFlow. After that we’ll move onto tackling the same problem using a Deep Neural Network. Lastly, we’ll close with a discussion and application of dropout which is a regularization technique for neural networks to help prevent them from memorizing our training dataset.

## Learning Objectives

- Understand how image data is represented as floating point numbers that can be flattened
- Compare functions for model confidence in image classification (Softmax)
- Train and evaluate a Linear model for image classification using TensorFlow
- Train and evaluate a Deep Neural Network (DNN) model for image classification using TensorFlow
- Understand how to apply dropout as a regularization technique for DNNs

## Linear Models for Image Classification

- [Video - Introduction](https://www.coursera.org/learn/image-understanding-tensorflow-gcp/lecture/9YwSb/introduction)

- [Video - Linear Models](https://www.coursera.org/learn/image-understanding-tensorflow-gcp/lecture/Iaws8/linear-models)

- [Video - Lab Intro: Linear Models for Image Classification](https://www.coursera.org/learn/image-understanding-tensorflow-gcp/lecture/GA2qB/lab-intro-linear-models-for-image-classification)

- [Lab - Linear Models for Image Classification](./Labs/mnist_linear.ipynb)

- [Video - Lab Solution: Linear Models for Image Classification](https://www.coursera.org/learn/image-understanding-tensorflow-gcp/lecture/7mZHq/lab-solution-linear-models-for-image-classification)

## DNNs for Image Classification

- [Video - DNN Models Review](https://www.coursera.org/learn/image-understanding-tensorflow-gcp/lecture/bdVMo/dnn-models-review)

- [Video - Lab Intro: DNN Models for Image Classification](https://www.coursera.org/learn/image-understanding-tensorflow-gcp/lecture/XCzlY/lab-intro-dnn-models-for-image-classification)

- [Lab - DNN Models for Image Classification](./Labs/mnist_models.ipynb)

- [Video - Lab Solution: DNN Models for Image Classification](https://www.coursera.org/learn/image-understanding-tensorflow-gcp/lecture/0hPvo/lab-solution-dnn-models-for-image-classification)

## DNNs with Dropout for Image Classification

- [Video - Review: What is Dropout?](https://www.coursera.org/learn/image-understanding-tensorflow-gcp/lecture/BG0TN/review-what-is-dropout)

- [Video - Lab Intro: DNNs with Dropout Layer for Image Classification](https://www.coursera.org/learn/image-understanding-tensorflow-gcp/lecture/WbRHH/lab-intro-dnns-with-dropout-layer-for-image-classification)

- [Lab - DNN with Dropout for Image Classification](./Labs/mnist_models.ipynb)

- [Video - Lab Solution: DNNs with Dropout Layer for Image Classification](https://www.coursera.org/learn/image-understanding-tensorflow-gcp/lecture/ny95j/lab-solution-dnns-with-dropout-layer-for-image-classification)

---

# Convolutional Neural Networks (CNNs)

This module will introduce Convolutional Neural Networks or CNNs for short, and get you started with implementing CNNs using TensorFlow. Since 2012, CNN based systems achieved unparalleled performance on tasks like image recognition and even at playing the ancient board game of Go against the top human champions.

## Learning Objectives

- Understand the history and use of CNNs for Image Classification
- Analyze how convolving kernals over an image creates a filter layer inside of a CNN
- Create convolutional and pooling laters in a CNN with TensorFlow

## Introducing CNNs

- [Video - Introduction](https://www.coursera.org/learn/image-understanding-tensorflow-gcp/lecture/hkAU1/introduction)

- [Video - Understanding Convolutions](https://www.coursera.org/learn/image-understanding-tensorflow-gcp/lecture/jRggH/understanding-convolutions)

- [Video - CNN Model Parameters](https://www.coursera.org/learn/image-understanding-tensorflow-gcp/lecture/xoTEB/cnn-model-parameters)

- [Video - Working with Pooling Layers](https://www.coursera.org/learn/image-understanding-tensorflow-gcp/lecture/Bqq9O/working-with-pooling-layers)

- [Video - Implementing CNNs with TensorFlow](https://www.coursera.org/learn/image-understanding-tensorflow-gcp/lecture/yTYCb/implementing-cnns-with-tensorflow)

- [Video - Lab Intro: Creating an Image Classifier with a Convolutional Neural Network](https://www.coursera.org/learn/image-understanding-tensorflow-gcp/lecture/M9pZq/lab-intro-creating-an-image-classifier-with-a-convolutional-neural-network)

- [Lab - CNNs for Image Classification](./Labs/mnist_models.ipynb)

- [Video - Lab Solution: Creating an Image Classifier with a Convolutional Neural Network](https://www.coursera.org/learn/image-understanding-tensorflow-gcp/lecture/GVHF0/lab-solution-creating-an-image-classifier-with-a-convolutional-neural-network)