---
title: "Book Notes: Deep Learning"
draft: false
ShowToc: true
---

> Read it slowly. A lot of the terminology and math will be unfamiliar — look them up. You may need to sketch some things out or code them to get them — give yourself the space to do that. If the math is unfamiliar, a good complementary resource is Math for Machine Learning. Even though architectures like CNN or RNN might seem out of date in a world that is moving towards transformers for everything, CNNs are still widely used, and everything old is new again with RNNs. When you’re done with the first 2 parts of the book (you can skip part 3), you should be at a point where you can code up any of the main neural networks architectures in plain numpy (forward and backward passes).

# Chapter 1

## Introduction

AI pode ser aplicada em: automação de trabalhos repetitivos; reconhecimento de fala e imagem; medicina e suporte a pesquisas de base.

AI consiste em solucionar problemas de modo que as máquinas aprendam com experiência (data) e entenda o mundo em termos de uma hierarquia de conceitos.

experiência → significa que não será necessário ao humano esclarecer o que precisa ser feito.

hierarquia de conceitos → permite a máquina aprender conceitos complexo quebrando eles em partes simples.

Se construímos um grafo mostrando como esses conceitos se conectam ele seria profundo e com várias camadas; por esse motivo chamamos AI Deep Learning.

Em sua vida cotidiana uma pessoa precisa de muito conhecimento, no geral esse conhecimento é informal, o grande desafio da AI é como capturar esse conhecimento.

## Machine Learning

machine learning é a capacidade que uma máquina possui de extrair ideias ou padrões de dados para construir seu próprio conhecimento.

Digamos que precise de um modelo para identificar automóveis, quais partes gostaria de mapear; talvez escolha roda e por esse motivo tenha dores de cabeça, pode ser que a imagem tenha baixa qualidade, que sombras atrapalhem o reconhecimento por parte do modelo. Você resolve dar um passo além e usa o modelo para entender o todo (entender o que é o carro): isso se chama representation learning.

Um exemplo de representation learning é o autoencoder; ele é formado por um encoder: cria uma representação para a entrada e o decoder: retornar a representação para seu estado original.

## Deep Learning

Quando se tornar impossível obter a representação usamos Deep Learning.

O problema é resolvido porque Deep Learning permite a máquina a representar conceitos complexos de forma simples.

Um exemplo clássico de Deep Learning é o MLP (multilayer perceptron).

Se construímos um [grafo](https://en.wikipedia.org/wiki/Graph_(discrete_mathematics)) mostrando como esses conceitos se conectam ele seria profundo e com várias camadas; por esse motivo chamamos AI Deep Learning.
