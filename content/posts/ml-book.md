---
title: "Machine Learning with Pytorch and Scikit-Learn"
draft: false
ShowToc: true
date: 2024-03-01
tags: ["books"]
---

# 1

## Giving Computers the Ability to Learn from Data

Machine Learning is a sub-field of AI, consisting of algorithms capable of learning from data. This allows us humans to not have to explicitly tell the computer/machine what it needs to do.

- Types of ML

- Supervised

  - Labeled data
  
  - Direct feedback
  
  - Predict future

- Unsupervised
  
  - No Labels/targets
  
  - No feedback
  
  - Find hidden structure

- Reinforcement

  - Decision process
  
  - Reward system
  
  - Learn series of actions

- Supervised

  - We use data with labels, that is, with indications, for example, a data set with a column containing records made by humans to indicate whether a message is spam or not.
  
  - Classification is a type of Supervised learning and consists of obtaining an output that can be binary (yes/no or spam/not-spam) or multiclass (winter, summer, autumn).
  
  - Regression consists of obtaining a numerical result as output: temperature, age, or the value of a property.

- Reinforcement

  - In reinforcement learning, a model is trained to improve its performance by interacting with the environment.
  
  - An example is the game of Chess.

- Unsupervised Learning

  - In the supervised type, we know the correct answer; in the unsupervised type, we do not.
  
  - Clustering is a technique that allows finding patterns in data (sub-groups).
  
  - Dimensionality reduction condenses information from the data set and eliminates what is not relevant.

Cross-Validation helps verify the effectiveness of a model without having to use the test set.

Hyperparameter optimization exists because by default, the model parameters may not be ideal for our specific problem.
