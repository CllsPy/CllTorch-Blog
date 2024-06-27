---
title: "Entenda o Cálculo Diferencial: Intuitivamente"
draft: false
ShowToc: true
date: 27 Jun 2024
tags:
    - math
    - python
    - AI
---
      
**Índice**:
1. O que é uma função?
2. Encontrando a variação de uma função simples
3. Entendendo a complexidade de funções no mundo real
5. Encontrando a variação de funções complexas

O objetivo deste artigo é demonstrar como compreender o Cálculo Diferencial de uma forma intuitiva **com a menor quantidade de números e matemática possível.**

## O que é uma função?
Você pode pensar que uma função é como uma máquina com esteira. Sempre que algo entra (input), será transformado em algo diferente do outro lado (output).

![Esteira de Produtos](https://nucleoexpert.com/wp-content/uploads/2022/08/Esteira-de-Produtos-AUMENTE-SEU-FATURAMENTO.jpg)

Por que isso importa? Bem, porque nos ajuda a entender tendências e, no mundo real, as tendências nos ajudam a compreender coisas como: qual retorno financeiro terei ao investir no produto "X", quão rápido uma doença se espalha, etc.

Um exemplo simples de função é a função $f(x) = x + 1$. Ou seja, para cada $x$ (input), nossa máquina o transformará em $x + 1$. Por exemplo, se $x$ for 1, então $f(1) = 2$, e assim por diante.

![Função f(x)](https://www.googleapis.com/download/storage/v1/b/kaggle-forum-message-attachments/o/inbox%2F11611801%2F2a49a486a4a7ae7886954799fff713f0%2Ffx.jpg?generation=1719527446403213&alt=media)

## Encontrando a variação de uma função simples

![Inclinação](https://www.googleapis.com/download/storage/v1/b/kaggle-forum-message-attachments/o/inbox%2F11611801%2F07d130b3df36d046bef146896dc7a431%2Finc.png?generation=1719527612377553&alt=media)

Agora precisamos entender algo **importante e crucial para a continuação deste artigo: a inclinação dessa reta**. Digamos que eu queira saber qual a inclinação entre os pontos em $x_0, x = (3, 4)$, sabendo que eles resultam em $y_0, y = (4, 5)$. Como se trata de um intervalo, vamos chamar de $\Delta x$ e $\Delta y$. A inclinação é dada por:

$$
\dfrac{\Delta y}{\Delta x} = \dfrac{(y-y_0)}{(x-x_0)} = \dfrac{(5-4)}{(4-3)} = 1
$$

Simples, não? Agora eu sei que a taxa de variação é 1, ou seja, cada unidade em $x$ implica uma variação de 1 em $y$.

> Como essa função é linear, qualquer par de pontos $x, y$ que escolher sempre resultará em 1.

## Entendendo a complexidade de funções no mundo real

![Dragão Europeu](https://1001dragons.com/wp-content/uploads/2022/04/dragon-europeen-800-01-696x377.jpg)

Como você deve imaginar, no mundo real, as coisas não são bem assim. As funções são muito mais caóticas. Vamos ver outro exemplo: $f(x) = x^2$.

![Função f(x) = x^2](https://www.googleapis.com/download/storage/v1/b/kaggle-forum-message-attachments/o/inbox%2F11611801%2F5e44df8d8878cabd0ab66a772a7d5702%2Ffx2.jpg?generation=1719527503787040&alt=media)

Por exemplo, temos um caso em que não é possível simplesmente aplicar o que aprendemos antes, porque não temos mais uma reta. Nesse caso, a variação ocorre em cada ponto desta função. **O que eu faria para saber a variação naquele exato ponto?**

> Você acabou de fazer a pergunta que é a base de todo cálculo diferencial!

## Encontrando a variação de funções complexas
Como vimos, não é possível encontrar, de forma simples, **a taxa de variação** para a função $f(x) = x^2$. Aqui entra o cálculo diferencial e uma palavra que você pode ter ouvido antes: **DERIVADA**. Ela permite que, para cada ponto, seja possível saber a inclinação. Sabemos que a derivada de $f(x) = x^2$ é $f'(x) = 2x$, ou seja, no ponto $x = 4$, nossa variação é $2 \cdot 4 = 8$.

> Não vou entrar nos detalhes de por que isso é assim, pois não é o objetivo deste artigo.

**Em suma, podemos concluir que o objetivo do cálculo diferencial é entender como se comportam funções complexas (que mudam de variação em cada ponto) no mundo real.**
