---
title: "Today I Learned"
draft: false
ShowToc: true
date: 2024-04-01
tags: ["books", "knowledge management"]
author: Carlos L.
---

# 🌟 **Today I Learned (TIL)**

## Day 1: July 19, 2024

- **Large Language Models (LLMs)** are trained on vast amounts of data sourced from the internet, which means there is a high possibility of containing bias or inappropriate content.
- I learned that a software engineer must possess two principles: **self-learning** and **problem-solving**.
- A good software engineer is capable of delivering a **secure** and **functional** product, achievable through **Unit Testing**.
- How to make a Unit Test using Python:
  - 🐍 **Unit Testing in Python**
    - Use `python -m unittest test_module.py`
    - Common assertions: `assertEqual`, `assertRaises`
- I learned about **TDD (Test-Driven Development)**: A method to write software where you first write the tests, then write the code.
- **DRY (Don't Repeat Yourself)**
  - Your code should have as little repetition as possible.
  - Less repetition means fewer bugs.
- How to create a **function**.
- How to call a **function**.
- How to use **arrays** and operate them.
- **Unit Testing**
  - Use `python -m unittest test_module.py`
  - Common assertions: `assertEqual`, `assertRaises`.

## Day 2: July 20, 2024

- Learned how to authenticate HuggingFace using the login screen in Google Colab.
- Discovered the model [HuggingFaceTB/SmolLM-1.7B-Instruct](https://huggingface.co/HuggingFaceTB/SmolLM-1.7B-Instruct?text=write+a+poem).
- Explored the functionality of Prompt Template in LangChain.
- Understood the importance of standardizing prompts.
- Learned how to create an API and use it in Colab.
- Learned how the Prompt Template in LangChain works.
- Understood why it is important to standardize the prompt.
- Learned how to create an API and use it in Colab.

## Day 3: July 22, 2024
- How to create a Personal Access Token on GitHub
- How to use the PyGithub library
- How to mine GitHub using their API


**Machine Learning**

- How to train a Perceptron
- Bias, Batch Size
- Loss Function
- Activation Function

**matplotlib and numpy**
- np.meshgirid(x, y)
- plt.contourf()
- plt.clf()

**Resources**

- [REST API endpoints for users](https://docs.github.com/en/rest/users?apiVersion=2022-11-28)
- [Mining the social web](https://github.com/mikhailklassen/Mining-the-Social-Web-3rd-Edition)
- [Managing your personal access tokens](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens)
- [Neural Networks and Perceptron - Lesson 9](https://www.youtube.com/watch?v=fEukSrpDPH0)
- [Perceptron For Dummies](https://jilp.org/cbp/Daniel-slides.PDF)
- [Perceptrons, Marvin](https://www.amazon.fr/Perceptrons-Intro-Computational-Geometry-Exp/dp/0262631113)
- [What is the purpose of meshgrid in NumPy?](https://stackoverflow.com/questions/36013063/what-is-the-purpose-of-meshgrid-in-numpy)

## Day 4: July 23, 2024

- I learned that there are five stages to training a Machine Learning model.
- I learned about the `bincount` command in Numpy, which counts the occurrence of similar values in an array.

**Sklearn**

- I learned how to implement the Perceptron algorithm in scikit-learn.
- I learned about the OvO and OvR techniques to enable models limited to binary classifications (Logit, SVM) to perform classification on multi-class data.
  
**Resources**

- [One-vs-Rest and One-vs-One for Multi-Class Classification](https://machinelearningmastery.com/one-vs-rest-and-one-vs-one-for-multi-class-classification/)
- Page 503, Machine Learning: A Probabilistic Perspective, 2012.
- [Choosing the right estimator - Scikit-learn](https://scikit-learn.org/1.3/tutorial/machine_learning_map/index.html)

## Day 5: July 27, 2024

- I learned what Logistic Regression is.
- I learned what the Sigmoid Function is.
- I learned the difference between Gradient Descent and Stochastic Gradient Descent.

**Resources**
- [Tutorial 35 - Logistic Regression In-depth Intuition - Part 1 | Data Science](https://www.youtube.com/watch?v=L_xBe7MbPwk)
- [Tutorial 36 - Logistic Regression In-depth Intuition - Part 2 | Data Science](https://www.youtube.com/watch?v=uFfsSgQgerw)
- [Why Is Logistic Regression Called “Logistic Regression” And Not Logistic Classification?](https://medium.com/@praveenraj.gowd/why-is-logistic-regression-called-logistic-regression-and-not-a-logistic-classification-5a418293040d#:~:text=Linear%20regression%20gives%20a%20continuous,%E2%80%9CRegression%E2%80%9D%20in%20its%20name.)

## Day 6: July 31, 2024

- I learned about the concept of "maximum margin" in machine learning models.
- I understood that larger margins help reduce generalization error, while smaller margins increase the risk of overfitting or underfitting.
- I became familiar with the concept of "slack variables," introduced by W. Vapnik in 1995, which make SVM models more flexible when data is not linearly separable.
- I learned that these variables are represented by the parameter \( C \), which controls error tolerance and the trade-off between bias and variance.
- I realized that adjusting the value of \( C \) is crucial for ensuring the model generalizes well to new data, avoiding overfitting and underfitting.

**Resources**
- [StatQuest: Logistic Regression](https://www.youtube.com/watch?v=yIYKR4sgzI8&list=PLblh5JKOoLUKxzEP5HA2d-Li7IJkHfXSe)
- Chris J.C. Burges’ excellent explanation in A Tutorial on Support Vector Machines for Pattern Recognition (Data Mining and Knowledge Discovery, 2(2): 121-167, 1998)
- Vladimir Vapnik’s book The Nature of Statistical Learning Theory, Springer Science+Business  Media, Vladimir Vapnik, 2000
- Andrew Ng’s very detailed lecture notes available at https://see.stanford.edu/materials/aimlcs229/cs229-notes3.pdf

## Day 7: Aug 1, 2024

- I learned that Logistic Regression tries to maximize conditional likelihoods.
- I became familiar with the concept of conditional likelihoods.
- I learned that Logistic Regression is more vulnerable to outliers than SVM.
- I understood that Logistic Regression is simpler to explain and therefore more attractive for streaming data.
- I learned about the SGDClassifier in scikit-learn, which allows for incremental training.
- I became familiar with the possibility of initializing the SGDClassifier with Perceptron, Logistic Regression, and SVM.
- I understood that we can use SVM with a kernel to solve nonlinear problems.
- I learned about kernel methods for linearly inseparable data.
- I comprehended the use of the kernel trick to classify nonlinear data in a high-dimensional space.
- I learned that the Gaussian Kernel is one of the most common kernel methods.

**Resources**
- [Likelihood Function](https://en.wikipedia.org/wiki/Likelihood_function)
- [Maximum Likelihood Estimation in Logistic Regression](https://arunaddagatla.medium.com/maximum-likelihood-estimation-in-logistic-regression-f86ff1627b67)
- [Machine Learning Notation](https://nthu-datalab.github.io/ml/slides/Notation.pdf)

## Day 8: Aug 3, 2024

- Today I learned about decision tree learning.
- Tree-based models are a good choice when interpretability is crucial.
- Data is classified based on the questions the model asks.
- The process starts at the top of the tree, selecting the feature with the highest Information Gain (IG).
- This process is repeated until the branches are pure, meaning a class has been chosen.
- In practice, this process can easily lead to overfitting.
- The goal is to choose the feature that provides the highest possible gain in information.
- To achieve this, an objective function is defined and optimized using the Decision Tree algorithm.
- Mathematically, Information Gain is the difference between the impurity of the parent node and the sum of the impurities of the child nodes.
- The lower the impurity of the children, the higher the gain.
- Computationally, it can be impractical, so sklearn uses the binary decision tree algorithm.
- The impurity measures used by binary decision trees include: Gini impurity (IG), Entropy (IH), and Classification Error (IE).

**Resources**
- [Binary Search](https://www.kaggle.com/discussions/accomplishments/523939#:~:text=Futher%20Readings-,Binary%20Search,-Add%20Tags)

## Day 9: Aug 4, 2024

- Random Forest is a technique that combines multiple decision trees.
- This model is considered an **ensemble** of decision trees.
- Random Forest averages the decision trees to generate a consistent result.
- The method helps to avoid overfitting.
- The technique consists of four main steps:
  1. Create a test set.
  2. Branch a decision tree for each test set and split the features at each node with the highest gain, based on the chosen metric.
  3. Repeat steps 1 and 2.
  4. Aggregate the results and choose the winning class by majority vote.
 

### papers
- [Generative AI Text Classification using Ensemble LLM Approaches](https://arxiv.org/pdf/2309.07755)

### Userful
- [Bloom](https://bigscience.huggingface.co/blog/bloom)
- [DetectGPT](https://detectgpt.com/app/)
- [Bootstrapping (statistics)](https://en.wikipedia.org/wiki/Bootstrapping_(statistics))


## Day 10: Aug 6, 2024

- I learned that Random Forest is an ensemble learning technique that combines multiple decision trees to generate more consistent results and avoid overfitting.
- I learned that the Random Forest process involves creating test sets, building a decision tree for each test set, repeating these steps, and finally aggregating the results through majority voting.
- I learned that reducing the sample size increases diversity and reduces the chances of overfitting, although it may negatively impact overall performance.
- I learned that K-nearest neighbors (KNN) is a lazy-learning algorithm that memorizes training data instead of optimizing a function.
- I learned that KNN is a non-parametric and instance-based algorithm, which adapts easily to new data but requires more resources as the amount of data increases.
- I learned that KNN classifies data by identifying the nearest elements and choosing the class based on majority voting.


### papers

- [Discriminant Function Analysis](https://www.sciencedirect.com/topics/neuroscience/discriminant-function-analysis#:~:text=Discriminant%20function%20analysis%20(DFA)%20is,normally%20distributed%20for%20the%20trait.)

### Userful

- [Bloom](https://bigscience.huggingface.co/blog/bloom)
- [DetectGPT](https://detectgpt.com/app/)
- [Bootstrapping (statistics)](https://en.wikipedia.org/wiki/Bootstrapping_(statistics))

## Day 11: Aug 7, 2024

- In the real world, data can be presented in different ways, generally irregular, missing values ​​are one of the manifestations, they can occur for several reasons; forgetfulness, non-existence of information; typing errors. There are techniques to deal with the absence of this data, such as deleting or replacing the data.
- We can use `isnull().sum()` to verify all null values on a dataframe
- To remove null data from our dataframe we can you the method .drop(), the method has some parameters i.e 'all' that removes only rows where all values are null.

## Day 12: Aug 9, 2024

- **I learned** that deleting missing numeric values can lead to significant information loss.
- **I learned** about interpolation, a common technique for filling missing data by replacing null values with the column’s mean.
- **I learned** that scikit-learn provides tools to perform interpolation of missing values.
- **I learned** how to use the scikit-learn API:
  - `data.fit`: Used to learn the parameters from the data.
  - `data.transform`: Applies the learned transformation.
  - `data.predict`: A method used by estimators to make predictions on test data.
- **I learned** that data consistency is important, as the array used in `fit` must have the same number of features when it is transformed.
- Today I learned that nominal classes do not need to follow any specific order and can start counting from 0.
- Today I learned that assigning ordered numerical values to nominal categorical features can lead to incorrect assumptions in machine learning models.
- Today I learned that one-hot encoding is a technique to prevent models from assuming an ordinal relationship among nominal categories by creating a binary representation for each category.

## Day 13: Aug 12, 2024

- Today I learned the importance of partitioning a dataset into separate training and test datasets, which allows us to evaluate the model's performance before deploying it in the real world.
- I learned about the benefits of bringing features onto the same scale, as most machine learning models perform better when the data is scaled.
- I learned that normalization typically involves limiting the range of values, usually between [0, 1], and can be achieved using the `MinMaxScaler` in scikit-learn.
- I also learned that scaling adjusts the proportion of the data, but it does not normalize the data.
