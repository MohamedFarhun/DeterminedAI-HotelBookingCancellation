# DeterminedAI-HotelBookingCancellation

## Inspiration
"HotelBookingCancellation with Determined AI" - This code demonstrates how the Determined AI platform can split up the training process across multiple GPUs, making deep neural network training on huge datasets like HotelBookingcancellation faster and more effective.

Distributed training with determined AI:- You may quickly distribute model training across your cluster to enable more effective experimentation and model building at an earlier stage. With significant performance improvements over competing solutions, Determined uses synchronous, data-parallel distributed training.Determined automatically starts a new process for each GPU being utilised for training when performing dispersed training. Care should be made to make sure that concurrent data downloads do not interfere with one another since each process makes an attempt to download training and/or validation data.

## What it does
The code explains how to utilise Distributed Training with Determined AI to train a deep neural network on the dataset. The training function distributes the training across many GPUs using the Determined AI library and the TensorFlow backend.

## Advantages of determined ai

Cluster management: Using your own environment that scales automatically for your on-demand workloads, you can automatically manage accelerators (such as GPUs) on-premise or in cloud VMs. Depending on your needs, Determined can run in either AWS or GCP, so switching is simple. 

Containerization: Develop and train models in customizable containers, which enable simple and consistent dependency management throughout the model development lifecycle. 

Cluster-backed notebooks: Experiment directly in a cluster-backed colab notebook, so you may exploit your shared cluster accelerators in a more versatile notebook environment. 

Experiment cooperation: Automatically track the configuration and environment for each of your experiments, promoting repeatability and collaboration among teams.

## How we built it

We used determinedAI platform and colab notebook to cluster our project.We used python for coding and some machine learning and deep learning algorithms to train and test our project.

## Problem statement and solutions

The management team of the hotel determined that the problem of anticipating and managing reservation cancellations necessitates an urgent remedy. Booking cancellations have an impact on the hotel's revenue as well as its ability to operate efficiently. This project's objectives are to conduct an exploratory data analysis to identify the characteristics of consumers who cancel and to identify a pattern in cancelled bookings using DeterminedAI.Developed a classification machine learning model with an accuracy score of 0.75 to 0.9 to forecast cancellation with the help of determinedAI

## Challenges we ran into
At first,it was difficult to understand the documentation of determinedAI.After clear understanding of the documentation we started our project and we finished our project successfully.

## Accomplishments that we're proud of

The code achieved high accuracy on the validation set and demonstrated the efficacy of the Determined AI platform for optimising hyperparameters and managing the training process. We are proud of the scalability and efficiency of the code, which can be applied to other datasets and models with little modification. We are proud that we successfully trained a deep neural network on the  dataset using distributed training with Determined AI.

## What we learned

Building this code taught us how crucial effective distributed training is for massive machine learning workloads. We also got expertise managing experiments, optimising hyperparameters, and tracking training progress using the Determined AI platform and accompanying tools. We learnt how to work with TensorFlow as a backend for distributed training, and how to balance memory and computation requirements while working with huge datasets. Overall, we learned a lot about the difficulties and possibilities of deep learning at scale.

## What's next for HotelBookingCancellation-DeterminedAI

The platform could be further optimised for distributed training on larger clusters, new features could be added to support more advanced model development and deployment workflows, and training a deep neural network and hyperparameter search strategies to improve performance would be the next steps for Determined AI.
