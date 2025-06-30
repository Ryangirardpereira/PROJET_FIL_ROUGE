# 📊 Analyse de l'impact du COVID-19 sur l'économie française

## 🧠 Contexte
Ce projet s’inscrit dans le cadre du module "Projet Fil Rouge" de notre formation. L'objectif principal est d'étudier les effets de la crise sanitaire liée au COVID-19 sur l'économie française, en particulier sur deux indicateurs clés :
- Le **PIB (Produit Intérieur Brut)**
- Le **taux de chômage**

## 🎯 Problématique
> *Comment une crise sanitaire comme celle du COVID-19 peut-elle affecter la dynamique économique d’un pays ?*


## 📉 Données utilisées

- **PIB trimestriel** : Banque de France / Eurostat  
  📁 `CLVMNACSCAB1GQFR.csv`  
  Source : [FRED St Louis](https://fred.stlouisfed.org/series/CLVMNACSCAB1GQFR)

- **Données COVID-19** : Santé publique France  
  📁 `sp-dep-jour-2023-06-30-16h26.csv`  
  Source : [data.gouv.fr](https://www.data.gouv.fr/fr/datasets/donnees-hospitalieres-relatives-a-lepidemie-de-covid-19/)

  - **Taux de chômage** : INSEE  
  📁 `valeurs_trimestrielles_sans_codes.csv`  
  Source : [insee.fr](https://www.insee.fr/fr/statistiques/serie/001688526)

## 🧪 Méthodologie

1. **Nettoyage des données**
   - Conversion de formats (virgule → point)
   - Agrégation trimestrielle
2. **Fusion des datasets**
   - Alignement sur la base du trimestre
3. **Visualisations**
   - Corrélation COVID ↔ PIB
   - Corrélation COVID ↔ Chômage
   - Heatmaps par département
   - Comparaison par tranche d’âge

## 📌 Résultats clés

- Forte chute du PIB au 2e trimestre 2020, corrélée au pic des cas COVID.
- Hausse significative du taux de chômage sur la même période.
- Taux de positivité plus élevé dans certains départements fortement peuplés (Paris, Bouches-du-Rhône...).

## 💡 Auteurs

- **Ryan Girard** – Analyse PIB & traitement COVID
- **Gwendal Kerboul** – Étude du chômage

## ✅ Livrables

- Notebook d’analyse `COVID.ipynb`
- Présentation Canva
- Code source et graphique disponibles sur ce dépôt

## 🛠 Outils

- Python, Pandas, Plotly, Matplotlib, dash
- Jupyter Notebook

## 📎 Licence

Ce projet est à but pédagogique uniquement.