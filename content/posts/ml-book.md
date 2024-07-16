---
title: "Machine Learning with Pytorch and Scikit-Learn"
draft: false
ShowToc: true
---

# 1

## Giving Computers the Ability to Learn from Data

Machine Learning é um sub-campo da IA, consistem em algorítimos capazes de aprender com dados. Isso possibilita que nós humanos não tenhamos que explicitamente dizer o que o computador/máquina precisa fazer.

- Tipos de ML

- Supervisionado

  - Labeled data
  
  - Direct feedback
  
  - Predict future

- Não-supervisionado
  
  - No Labels/targets
  
  - No feedback
  
  - Find hidden structure

- Reforço

  - Decision process
  
  - Reward system
  
  - Learn series of actions

- Supervisionado

  - Usamos dados com labels ou seja com indicações, por exemplo, um conjunto de dados com uma coluna contendo registros feitos por humanas para quando uma mensagem é ou não spam.
  
  - A classificação é um tipo Supervisionado e consiste em obter uma saída que pode ser binária (sim/não ou spam/não-spam) ou multiclasse (inverno, verão, outono)
  
  - A regressão consiste em obter um resultado numérico na saída: a temperatura, idade ou valor de um imóvel.

- Reforço

  - No reinforcement learning treina-se um modelo capaz de melhorar sua performance à partir da interação com o ambiente.
  
  - Um exemplo é o jogo de Xadrez

- Unsupervised Learning

  - No tipo supervisionado sabemos a resposta correta; já no não-supervisionado não.
  
  - Clustering é uma técnica que permite encontrar padrões nos dados (sub-grupos).
  
  - Dimensionality reduction condensa informações do conjunto de dados e elimina o que não é relevante.

Cross-Validation ajuda em verificar a eficácia de um modelo sem que tenhamos que usar o conjunto de teste.

Hyperparameter optimization existe porque por padrão os parâmetros do modelo podem não ser o ideal para o nosso problema específico.
