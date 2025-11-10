# Quant 101 — Rendements, Volatilité et Corrélations

## Objectif
Comprendre et manipuler les mesures fondamentales de la performance et du risque financier.  
Cet atelier introduit la base de toute modélisation quantitative : les **rendements**, la **volatilité** et les **corrélations**.

---

## Contenu
- **Survol théorique** des concepts clés : rendements, volatilité, corrélation.
- Téléchargement et manipulation de données financières avec **Pandas** et **YFinance**.  
- Calcul des **rendements simples** et **logarithmiques**.  
- Mesure et annualisation de la **volatilité**.  
- Construction, interprétation et visualisations de **matrices de corrélation**.   
- Discussion du lien entre corrélations et **diversification de portefeuille**.

---

## Prérequis
- Connaissances de base en Python et manipulation de DataFrames.  
- Librairies : `pandas`, `numpy`, `matplotlib`, `seaborn`, `yfinance`.

---

## Livrable
Un mini-dashboard Python affichant :
- Les prix des actifs choisis.  
- La volatilité dynamique annualisée de chaque actif sur une rolling window.  
- Une matrice de corrélation interactive entre les titres analysés.

---

## Fichiers
- `returns_volatility_correlation.ipynb` — Notebook principal.   

---

## À explorer ensuite
## 💡 À explorer ensuite
L’atelier suivant, **Régression linéaire et estimation de $\alpha$ et $\beta$**, appliquera ces notions pour quantifier la relation entre un actif et son indice de référence.  
Tu y apprendras à mesurer la sensibilité d’un titre au marché, à interpréter le risque systématique et à introduire les fondements du modèle **CAPM**.
