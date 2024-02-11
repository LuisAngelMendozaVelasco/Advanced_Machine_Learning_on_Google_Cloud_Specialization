# Designing Adaptable ML Systems

In this module, you learn how to recognize the ways that our model is dependent on our data, make cost-conscious engineering decisions, know when to roll back our models to earlier versions, debug the causes of observed model behavior and implement a pipeline that is immune to one type of dependency.

# Learning Objectives

- Describe how upstream data dependencies can affect your model
- Analyze, debug, and adapt common model dependency issues
- Perform TensorFlow data validation
- Investigate and visualize a dataset using TensorFlow Data Validation
- Serve ML predictions in batch and real time

## Introduction

- [Video - Introduction](https://www.coursera.org/learn/gcp-production-ml-systems/lecture/YA2xz/introduction)

## Adapting to Data

- [Video - Adapting to data](https://www.coursera.org/learn/gcp-production-ml-systems/lecture/JjitO/adapting-to-data)

- [Video - Changing distributions](https://www.coursera.org/learn/gcp-production-ml-systems/lecture/RT93x/changing-distributions)

- [Video - Lab: Adapting to data](https://www.coursera.org/learn/gcp-production-ml-systems/lecture/XYTTC/lab-adapting-to-data)

- [Video - Right and wrong decisions](https://www.coursera.org/learn/gcp-production-ml-systems/lecture/jR8Lg/right-and-wrong-decisions)

- [Video - System failure](https://www.coursera.org/learn/gcp-production-ml-systems/lecture/N4zv7/system-failure)

- [Video - Concept drift](https://www.coursera.org/learn/gcp-production-ml-systems/lecture/kcTDO/concept-drift)

- [Video - Actions to mitigate concept drift](https://www.coursera.org/learn/gcp-production-ml-systems/lecture/vwhR9/actions-to-mitigate-concept-drift)

- [Video - TensorFlow data validation](https://www.coursera.org/learn/gcp-production-ml-systems/lecture/ctPjC/tensorflow-data-validation)

- [Video - Components of TensorFlow data validation](https://www.coursera.org/learn/gcp-production-ml-systems/lecture/BqXPm/components-of-tensorflow-data-validation)

- [Video - Lab Introduction: Introduction to TensorFlow data validation](https://www.coursera.org/learn/gcp-production-ml-systems/lecture/gAsXV/lab-introduction-introduction-to-tensorflow-data-validation)

- [Lab - Introduction to TensorFlow data validation](./Labs/tfdv_basic_spending.ipynb)

- [Video - Lab Introduction: Advanced visualizations with TensorFlow data validation](https://www.coursera.org/learn/gcp-production-ml-systems/lecture/f3cXJ/lab-introduction-advanced-visualizations-with-tensorflow-data-validation)

- [Lab - Advanced visualizations with TensorFlow data validation](./Labs/tfdv_advanced_taxi.ipynb)

## Mitigating Training-Serving Skew

- [Video - Mitigating training-serving skew through design](https://www.coursera.org/learn/gcp-production-ml-systems/lecture/dGKnG/mitigating-training-serving-skew-through-design)

- [Video - Lab Introduction: Serving ML predictions in batch and real-tIme](https://www.coursera.org/learn/gcp-production-ml-systems/lecture/5LUp3/lab-introduction-serving-ml-predictions-in-batch-and-real-time)

- [Lab - Serving ML predictions in batch and realtime](./Labs/serving_ml_prediction.ipynb)

- [Video - Lab Debrief: Serving ML predictions in batch and real-time](https://www.coursera.org/learn/gcp-production-ml-systems/lecture/GL7gj/lab-debrief-serving-ml-predictions-in-batch-and-real-time)

## Debugging a Production Model

- [Video - Diagnosing a production model](https://www.coursera.org/learn/gcp-production-ml-systems/lecture/pF4z4/diagnosing-a-production-model)

- [Reading - Designing adaptable ML systems](https://www.coursera.org/learn/gcp-production-ml-systems/supplement/CeJNS/designing-adaptable-ml-systems)

---

# Designing High-Performance ML Systems

In this module, you identify performance considerations for machine learning models. Machine learning models are not all identical. For some models, you focus on improving I/O performance, and on others, you focus on squeezing out more computational speed.

## Learning Objectives

- Describe the performance considerations when building, training, and serving ML models
- Choose an appropriate ML model infrastructure
- Select an appropriate distribution strategy

## Introduction

- [Video - Introduction](https://www.coursera.org/learn/gcp-production-ml-systems/lecture/u0yCu/introduction)

## Aspects of Performance

- [Video - Training](https://www.coursera.org/learn/gcp-production-ml-systems/lecture/jQoTA/training)

- [Video - Predictions](https://www.coursera.org/learn/gcp-production-ml-systems/lecture/kVDnE/predictions)

## Distributed Training

- [Video - Why distributed training is needed](https://www.coursera.org/learn/gcp-production-ml-systems/lecture/fCqWU/why-distributed-training-is-needed)

- [Video - Distributed training architectures](https://www.coursera.org/learn/gcp-production-ml-systems/lecture/rGbL0/distributed-training-architectures)

- [Video - TensorFlow distributed training strategies](https://www.coursera.org/learn/gcp-production-ml-systems/lecture/AKp6D/tensorflow-distributed-training-strategies)

- [Video - Mirrored strategy](https://www.coursera.org/learn/gcp-production-ml-systems/lecture/ESHhD/mirrored-strategy)

- [Video - Multi-worker mirrored strategy](https://www.coursera.org/learn/gcp-production-ml-systems/lecture/Kphef/multi-worker-mirrored-strategy)

- [Video - TPU strategy](https://www.coursera.org/learn/gcp-production-ml-systems/lecture/9iekp/tpu-strategy)

- [Video - Parameter server strategy](https://www.coursera.org/learn/gcp-production-ml-systems/lecture/uMeFo/parameter-server-strategy)

- [Video - Lab Introduction: Distributed training with Keras](https://www.coursera.org/learn/gcp-production-ml-systems/lecture/xZzCr/lab-introduction-distributed-training-with-keras)

- [Lab - Distributed training with Keras](./Labs/distributed_training_with_TF.ipynb)

- [Video - Lab Introduction: Distributed training using GPUs on Google Cloud’s AI Platform (Multi-Worker)](https://www.coursera.org/learn/gcp-production-ml-systems/lecture/SgeUo/lab-introduction-distributed-training-using-gpus-on-google-clouds-ai-platform)

- [Lab - Distributed training using GPUs on Google Cloud’s AI Platform (Multi-Worker)](./Labs/distributed_training.ipynb)

## Faster Input Pipelines

- [Video - Training on large datasets with tf.data API](https://www.coursera.org/learn/gcp-production-ml-systems/lecture/a1VL7/training-on-large-datasets-with-tf-data-api)

- [Video - Lab introduction: TPU-speed data pipelines](https://www.coursera.org/learn/gcp-production-ml-systems/lecture/nI93k/lab-introduction-tpu-speed-data-pipelines)

- [Lab - TPU-speed data pipelines](./Labs/tpu_speed_data_pipelines.ipynb)

## Inference

- [Video - Inference](https://www.coursera.org/learn/gcp-production-ml-systems/lecture/vYD6q/inference)

- [Reading - Designing high-performance ML systems](https://www.coursera.org/learn/gcp-production-ml-systems/supplement/CirI4/designing-high-performance-ml-systems)