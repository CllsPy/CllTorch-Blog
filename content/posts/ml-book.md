---
title: "Machine Learning with Pytorch and Scikit-Learn"
draft: false
ShowToc: true
date: 2024-03-01
tags: ["books", "ml"]
---

# Giving Computers the Ability to Learn from Data

Machine Learning is a sub-field of AI, consisting of algorithms capable of learning from data. This allows us humans not to have to explicitly tell the computer/machine what to do.

## Types of ML

### Supervised
- Labeled data
- Direct feedback
- Predict future

### Unsupervised
- No Labels/targets
- No feedback
- Find hidden structure

### Reinforcement
- Decision process
- Reward system
- Learn series of actions

## Supervised

We use data with labels, for example, a dataset with a column containing records made by humans to indicate whether a message is spam or not.

**Classification** is a type of Supervised learning and consists of obtaining an output that can be binary (yes/no or spam/not-spam) or multi-class (winter, summer, autumn).

**Regression** consists of obtaining a numerical result at the output: temperature, age, or property value.

## Reinforcement

In reinforcement learning, a model is trained to improve its performance through interaction with the environment.

An example is the game of Chess.

## Unsupervised Learning

In supervised learning, we know the correct answer; in unsupervised learning, we do not.

**Clustering** is a technique that allows finding patterns in data (sub-groups).

**Dimensionality reduction** condenses information from the dataset and eliminates what is not relevant.

## Cross-Validation

Cross-Validation helps in verifying the effectiveness of a model without having to use the test set.

## Hyperparameter Optimization

Hyperparameter optimization exists because, by default, the model parameters may not be ideal for our specific problem.

# Training Simple Machine Learning Algorithms for Classification

The **Perceptron** is a binary classifier with two characteristics:
- The weights are initialized randomly.
- For each example, the weights and bias are updated.

[Adaline](https://medium.com/ensina-ai/rede-neural-perceptron-adaline-8f69dc419d4e) teaches about continuous minimization of the cost function.

In Adaline, it is proposed to include an error signal block to modify the weight values before submitting to the activation function (g).

Adaline compares the correct value for the input with the linear function and updates the weights and corrects the error; the perceptron compares the original value with the predicted value to update the weights.

Adaline emerged as a solution to the fact that the Perceptron did not handle the (XOR) problem well, i.e., non-linearly separable data.

The Adaline neuron inaugurates the use of an algorithm to reduce the cost function (L) called Gradient Descent.

### Gradient Descent

Imagine you are on top of a mountain; Gradient Descent would be like trying to reach the lowest possible point (descending the mountain).
