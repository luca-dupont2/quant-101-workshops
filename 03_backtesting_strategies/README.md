# Quant 101 — Intro au Backtesting de Stratégies

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/luca-dupont2/quant-101-workshops/blob/main/03_backtesting_strategies/backtesting_strategies.ipynb)

## Objectif

Apprendre les bases du **backtesting** pour évaluer la performance historique de stratégies d’investissement quantitatives simples.

---

## Contenu

-   Quick recap des ateliers précédents.
-   Introduction au backtesting :
    -   Qu’est-ce que le backtesting et pourquoi est-ce important ?
    -   Structure d’un backtester simple.
-   Implémentation d’une stratégie de trading basique (ex : momentum, mean reversion).
-   Analyse des résultats d’un backtest :
    -   Mesures de performance (rendement, volatilité, ratio de Sharpe).
    -   Visualisation des performances (courbe de capital, drawdowns).
-   Pièges à éviter lors du backtesting.
-   Mini-projet : construire et backtester une stratégie simple.

---

## Prérequis

-   Connaissances de base en Python et manipulation de DataFrames.
-   Librairies : `pandas`, `numpy`, `matplotlib`, `yfinance`.
-   Notions de base en investissement (long, short, frais, slippage, etc.).

---

## Livrable

Un notebook complet incluant :

-   Un backtester **simple**<sup>1</sup> implémentant une stratégie de trading basique.
-   Des analyses de performance et des visualisations des résultats du backtest.
-   Une discussion sur les pièges courants en backtesting et comment les éviter.
-   Une structure de backtester plus avancée pour des développements futurs.

<sup>1</sup> Note : ce backtester est très simplifié afin de faciliter la compréhension, il ne doit pas être utilisé en production sans améliorations significatives.

---

## Fichiers

-   `backtesting_strategies.ipynb` — Notebook principal.

---

## À explorer ensuite

Le prochain atelier portera sur les bases du **statistical arbitrage**.
Tu y apprendras comment identifier et exploiter des inefficiences de marché à l’aide de techniques statistiques avancées.