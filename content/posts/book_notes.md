---
title: "Deep Learning"
draft: false
ShowToc: true
---

## 📚 **Book Notes: Deep Learning**
**Status**: 🚀 Published

### **Table of Contents**

- [Chapter 1](#chapter-1)
- [Introduction](#introduction)
- [Machine Learning](#machine-learning)
- [Deep Learning](#deep-learning)

# Chapter 1

> 📝 **Tip**: Read it slowly. A lot of the terminology and math will be unfamiliar — look them up. You may need to sketch some things out or code them to understand — give yourself the space to do that. If the math is unfamiliar, a good complementary resource is *Math for Machine Learning*. Even though architectures like CNN or RNN might seem out of date in a world moving towards transformers, CNNs are still widely used, and everything old is new again with RNNs. When you’re done with the first 2 parts of the book (you can skip part 3), you should be able to code up any of the main neural network architectures in plain numpy (forward and backward passes).

---

## 🌟 **Introduction**

AI can be applied in various fields such as: automation of repetitive tasks, speech and image recognition, medicine, and foundational research support.

**Artificial Intelligence** involves solving problems in a way that machines learn from experience (data) and understand the world in terms of a hierarchy of concepts.

- **Experience** ➡️ This means humans don't need to explain every detail to the machine.
- **Hierarchy of Concepts** ➡️ Allows the machine to learn complex concepts by breaking them down into simpler parts.

If we build a graph showing how these concepts connect, it would be deep with many layers; hence, we call it **Deep Learning**.

In daily life, a person needs a lot of knowledge, which is often informal. The big challenge for AI is how to capture this knowledge.

---

## 🤖 **Machine Learning**

- **Machine Learning** is the ability of a machine to extract ideas or patterns from data to build its own knowledge.

- For instance, if you need a model to identify cars, you might choose to map parts like wheels. This can be challenging due to poor image quality or shadows that hinder recognition. To improve, you can use the model to understand the whole (what a car is): this is called **representation learning**.

- An example of representation learning is the **autoencoder**:
  - **Encoder**: Creates a representation for the input.
  - **Decoder**: Returns the representation to its original state.

---

## 🧠 **Deep Learning**

- When it becomes impossible to obtain the representation using simpler methods, we use **Deep Learning**.

- Deep Learning solves problems by allowing the machine to represent complex concepts simply.

- A classic example of Deep Learning is the **MLP (Multilayer Perceptron)**.

If we build a [graph](https://en.wikipedia.org/wiki/Graph_(discrete_mathematics)) showing how these concepts connect, it would be deep with many layers; hence, we call it **Deep Learning**.
