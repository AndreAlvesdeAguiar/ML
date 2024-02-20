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


BASE - PRÉ LIMPEZA

### Informações dos Jogos:
- **ano_campeonato**: Ano do campeonato.
- **data**: Data do jogo.
- **rodada**: Rodada do campeonato.
- **estadio**: Estádio onde o jogo foi realizado.
- **arbitro**: Árbitro que conduziu o jogo.
- **publico**: Público presente no jogo.
- **publico_max**: Capacidade máxima do estádio.
- **time_mandante**: Time mandante.
- **time_visitante**: Time visitante.
- **tecnico_mandante**: Técnico do time mandante.
- **tecnico_visitante**: Técnico do time visitante.
- **colocacao_mandante**: Colocação do time mandante no campeonato.
- **colocacao_visitante**: Colocação do time visitante no campeonato.
- **valor_equipe_titular_mandante**: Valor da equipe titular do time mandante.
- **valor_equipe_titular_visitante**: Valor da equipe titular do time visitante.
- **idade_media_titular_mandante**: Idade média dos titulares do time mandante.
- **idade_media_titular_visitante**: Idade média dos titulares do time visitante.
- **gols_mandante**: Número de gols marcados pelo time mandante.
- **gols_visitante**: Número de gols marcados pelo time visitante.
- **gols_1_tempo_mandante**: Número de gols marcados pelo time mandante no primeiro tempo.
- **gols_1_tempo_visitante**: Número de gols marcados pelo time visitante no primeiro tempo.
- **escanteios_mandante**: Número de escanteios conquistados pelo time mandante.
- **escanteios_visitante**: Número de escanteios conquistados pelo time visitante.
- **faltas_mandante**: Número de faltas cometidas pelo time mandante.
- **faltas_visitante**: Número de faltas cometidas pelo time visitante.
- **chutes_bola_parada_mandante**: Número de chutes de bola parada realizados pelo time mandante.
- **chutes_bola_parada_visitante**: Número de chutes de bola parada realizados pelo time visitante.
- **defesas_mandante**: Número de defesas realizadas pelo time mandante.
- **defesas_visitante**: Número de defesas realizadas pelo time visitante.
- **impedimentos_mandante**: Número de impedimentos marcados contra o time mandante.
- **impedimentos_visitante**: Número de impedimentos marcados contra o time visitante.
- **chutes_mandante**: Número total de chutes realizados pelo time mandante.
- **chutes_visitante**: Número total de chutes realizados pelo time visitante.
- **chutes_fora_mandante**: Número de chutes para fora realizados pelo time mandante.
- **chutes_fora_visitante**: Número de chutes para fora realizados pelo time visitante.

BASE POS 1 LIMPEZA


### Informações da Venda de Ingressos:
- **Data do jogo**: Data do jogo.
- **Hora do jogo**: Hora do jogo.
- **Total de ingressos vendidos**: Total de ingressos vendidos para o jogo.
- **Arrecadação total**: Arrecadação total com a venda de ingressos para o jogo.
