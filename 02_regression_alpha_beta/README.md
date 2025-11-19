# Quant 101 — Régression Linéaire, $\alpha$, $\beta$ et CAPM  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](
https://colab.research.google.com/github/luca-dupont2/quant-101-workshops/blob/main/03_linear_regression_capm/linear_regression_capm.ipynb)

## Objectif
Estimer et interpréter les coefficients **$\alpha$** et **$\beta$** via la régression linéaire,  
décomposer le risque d’un actif et comprendre comment le modèle **CAPM** relie rendement et risque systématique.

---

## Contenu
- **Rappel** : rendements, volatilité, corrélations et leur lien avec la régression.  
- Construction d’un modèle de régression linéaire avec `statsmodels`.  
- Estimation et interprétation de :
  - **$\beta$** — sensibilité d’un actif au marché.  
  - **$\alpha$** — rendement excédentaire.  
  - **$R^2$** — part du risque expliquée par le marché.  
  - **Résidus** — risque spécifique et variance idiosyncratique.  
- Visualisation :
  - Nuages de points et ligne de régression.  
  - Distribution et évolution temporelle des résidus.  
  - QQ-plot pour évaluer l’hypothèse de normalité.  
- Introduction concrète au **CAPM** et calcul du rendement « juste » selon le risque.

---

## Prérequis
- Connaissances de base en Python et manipulation de DataFrames.  
- Notions de rendements et volatilité.  
- Librairies : `pandas`, `numpy`, `matplotlib`, `seaborn`, `statsmodels`, `yfinance`.

---

## Livrable
Un notebook complet incluant :  
- Un modèle OLS estimant **$\alpha$**, **$\beta$**, **$R^2$**, et la variance des résidus.  
- Des graphiques de diagnostic (scatter, fitted vs real, distribution des résidus, QQ-plot).  
- Un mini-pricer CAPM comparant rendements **observés** vs **attendus**.

---

## Fichiers
- `regression_alpha_beta.ipynb` — Notebook principal.
- `figures/` — Dossier contenant les figures utilisées dans le notebook.

---

## À explorer ensuite
Le prochain atelier portera sur la **construction de stratégies** et la **validation empirique** via un premier module de **backtesting**.  
Tu y verras comment transformer un signal quantitatif (comme $\beta$, $\alpha$ ou des facteurs) en règles d’investissement testables.
