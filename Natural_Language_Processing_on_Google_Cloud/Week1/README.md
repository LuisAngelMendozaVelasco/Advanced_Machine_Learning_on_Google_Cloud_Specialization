# Working with Sequences

In this module, you’ll learn what a sequence is, see how you can prepare sequence data for modeling, and be introduced to some classical approaches to sequence modeling and practice applying them.

## Learning Objectives

- Define what a sequence is
- Prepare sequence data for modeling
- Apply classical approaches to sequence modeling using linear models, DNNs and CNNs

## Course Overview

- [Video - Course Introduction](https://www.coursera.org/learn/sequence-models-tensorflow-gcp/lecture/qiH8z/course-introduction)

- [Video - Getting Started with Google Cloud Platform and Qwiklabs](https://www.coursera.org/learn/sequence-models-tensorflow-gcp/lecture/ZdMD1/getting-started-with-google-cloud-platform-and-qwiklabs)

- [Reading - How to send course feedback](https://www.coursera.org/learn/sequence-models-tensorflow-gcp/supplement/EXVe9/how-to-send-course-feedback)

## Working with Sequences

- [Video - Sequence data and models](https://www.coursera.org/learn/sequence-models-tensorflow-gcp/lecture/RWXUp/sequence-data-and-models)

- [Video - From sequences to inputs](https://www.coursera.org/learn/sequence-models-tensorflow-gcp/lecture/XBmlr/from-sequences-to-inputs)

## Modeling Sequences with Linear Models

- [Video - Modeling sequences with linear models](https://www.coursera.org/learn/sequence-models-tensorflow-gcp/lecture/qMN2U/modeling-sequences-with-linear-models)

- [Video - Lab intro: using linear models for sequences](https://www.coursera.org/learn/sequence-models-tensorflow-gcp/lecture/WbE7P/lab-intro-using-linear-models-for-sequences)

- [Lab - Using linear models for sequences](./Labs/sinewaves.ipynb)

- [Video - Lab solution: using linear models for sequences](https://www.coursera.org/learn/sequence-models-tensorflow-gcp/lecture/5jdJd/lab-solution-using-linear-models-for-sequences)

## Modeling Sequences with DNNs

- [Video - Modeling sequences with DNNs](https://www.coursera.org/learn/sequence-models-tensorflow-gcp/lecture/q7wNZ/modeling-sequences-with-dnns)

- [Video - Lab intro: using DNNs for sequences](https://www.coursera.org/learn/sequence-models-tensorflow-gcp/lecture/bJnFZ/lab-intro-using-dnns-for-sequences)

- [Lab - Using DNNs for sequences](./Labs/sinewaves.ipynb)

- [Video - Lab solution: using DNNs for sequences](https://www.coursera.org/learn/sequence-models-tensorflow-gcp/lecture/U2DrT/lab-solution-using-dnns-for-sequences)

## Modeling Sequences with CNNs

- [Video - Modeling sequences with CNNs](https://www.coursera.org/learn/sequence-models-tensorflow-gcp/lecture/fYanV/modeling-sequences-with-cnns)

- [Video - Lab intro: using CNNs for sequences](https://www.coursera.org/learn/sequence-models-tensorflow-gcp/lecture/xfrk9/lab-intro-using-cnns-for-sequences)

- [Lab - Using CNNs for sequences](./Labs/sinewaves.ipynb)

- [Video - Lab solution: using CNNs for sequences](https://www.coursera.org/learn/sequence-models-tensorflow-gcp/lecture/Q9b9c/lab-solution-using-cnns-for-sequences)

## The variable-length problem

- [Video - The variable-length problem](https://www.coursera.org/learn/sequence-models-tensorflow-gcp/lecture/qHt8k/the-variable-length-problem)

---

# Recurrent Neural Networks

In this module, we introduce recurrent neural nets, explain how they address the variable-length sequence problem, explain how our traditional optimization procedure applies to RNNs, and review the limits of what RNNs can and can’t represent.

## Learning Objectives

- Understand how RNNs address the variable-length problem
- Understand how RNNs learn a compact representation of the past
- Learn how backpropagation through time works
- Understand the limits of what RNNs can and can't represent
- Understand how LSTM and GRU models work and address the vanishing gradient problem
- Build and train single and multi-layer LSTMs and GRUs in TensorFlow

## Recurrent Neural Networks

- [Video - Introducing Recurrent Neural Networks](https://www.coursera.org/learn/sequence-models-tensorflow-gcp/lecture/83UlE/introducing-recurrent-neural-networks)

- [Video - How RNNs represent the past](https://www.coursera.org/learn/sequence-models-tensorflow-gcp/lecture/lWypj/how-rnns-represent-the-past)

- [Video - The limits of what RNNs can represent](https://www.coursera.org/learn/sequence-models-tensorflow-gcp/lecture/si97a/the-limits-of-what-rnns-can-represent)

- [Video - The vanishing gradient problem](https://www.coursera.org/learn/sequence-models-tensorflow-gcp/lecture/GQdLR/the-vanishing-gradient-problem)

---

# Dealing with Longer Sequences

In this module we dive deeper into RNNs. We’ll talk about LSTMs, Deep RNNs, working with real world data, and more.

## Learning Objectives

- Identify the shortcomings of typical RNNs
- Review the architecture of an RNN cell compared to at LSTM cell
- Create RNN models with TensorFlow

## LSTMs, GRUs, and RNNs in TensorFlow

- [Video - Introduction](https://www.coursera.org/learn/sequence-models-tensorflow-gcp/lecture/pZoWA/introduction)

- [Video - LSTMs and GRUs](https://www.coursera.org/learn/sequence-models-tensorflow-gcp/lecture/KtzRG/lstms-and-grus)

- [Video - RNNs in TensorFlow](https://www.coursera.org/learn/sequence-models-tensorflow-gcp/lecture/0Yk3c/rnns-in-tensorflow)

- [Video - Lab Intro: Time series prediction: end-to-end (rnn)](https://www.coursera.org/learn/sequence-models-tensorflow-gcp/lecture/wj27x/lab-intro-time-series-prediction-end-to-end-rnn)

- [Lab - Time series prediction: end-to-end (rnn)](./Labs/sinewaves.ipynb)

- [Video - Lab Solution: Time series prediction: end-to-end (rnn)](https://www.coursera.org/learn/sequence-models-tensorflow-gcp/lecture/ztHaR/lab-solution-time-series-prediction-end-to-end-rnn)

## Deep RNNs

- [Video - Deep RNNs](https://www.coursera.org/learn/sequence-models-tensorflow-gcp/lecture/hE0dz/deep-rnns)

- [Video - Lab Intro: Time series prediction: end-to-end (rnn2)](https://www.coursera.org/learn/sequence-models-tensorflow-gcp/lecture/pPJd8/lab-intro-time-series-prediction-end-to-end-rnn2)

- [Lab - Time series prediction: end-to-end (rnn2)](./Labs/sinewaves.ipynb)

- [Video - Lab Solution: Time series prediction: end-to-end (rnn2)](https://www.coursera.org/learn/sequence-models-tensorflow-gcp/lecture/Wmfup/lab-solution-time-series-prediction-end-to-end-rnn2)

## Improving our Loss Function

- [Video - Improving our Loss Function](https://www.coursera.org/learn/sequence-models-tensorflow-gcp/lecture/TflyC/improving-our-loss-function)

- [Video - Demo: Time series prediction: end-to-end (rnnN)](https://www.coursera.org/learn/sequence-models-tensorflow-gcp/lecture/KVi2V/demo-time-series-prediction-end-to-end-rnnn)

- [Video - Working with Real Data](https://www.coursera.org/learn/sequence-models-tensorflow-gcp/lecture/Kbvxi/working-with-real-data)

- [Video - Lab Intro: Time Series Prediction - Temperature from Weather Data](https://www.coursera.org/learn/sequence-models-tensorflow-gcp/lecture/lZPc6/lab-intro-time-series-prediction-temperature-from-weather-data)

- [Lab - Time Series Prediction - Temperature from Weather](./Labs/temperatures.ipynb)

- [Video - Lab Solution: Time Series Prediction - Temperature from Weather Data](https://www.coursera.org/learn/sequence-models-tensorflow-gcp/lecture/Y4GKi/lab-solution-time-series-prediction-temperature-from-weather-data)

## Summary

- [Video - Summary](https://www.coursera.org/learn/sequence-models-tensorflow-gcp/lecture/3naBe/summary)