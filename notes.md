# Problema do Preço do Ingresso

## Descrição
Este é um problema de otimização que envolve determinar o preço ideal dos ingressos para maximizar a receita total da venda de ingressos para um evento, como um jogo de futebol.

## Variáveis
- \( P \): Preço do ingresso.

## Função Matemática
- \( R(P) \): Receita total da venda de ingressos.

A relação entre o preço do ingresso e a receita total pode ser modelada por uma equação, por exemplo:

\[
R(P) = P \times N(P)
\]

Onde \( N(P) \) é o número de ingressos vendidos a um determinado preço \( P \). A função \( N(P) \) pode depender de vários fatores, como a demanda esperada a diferentes preços.

## Objetivo
O objetivo é maximizar a receita total \( R(P) \) ajustando o preço do ingresso \( P \).

## Algoritmo L-BFGS-B
O algoritmo L-BFGS-B é utilizado para encontrar o preço do ingresso \( P \) que maximiza a receita total \( R(P) \). Para aplicar o algoritmo, é necessário especificar a função \( R(P) \) e seu gradiente com relação a \( P \). O algoritmo então ajusta iterativamente o valor de \( P \) para maximizar a função \( R(P) \).
