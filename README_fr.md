# Analyse des comportements offensifs en NBA (2004–2024)

🇬🇧/🇺🇸 [Read the English version](README.md)

Ce projet de data analyse l'évolution des comportements au tir dans la NBA entre les saisons régulières 2003–2004 et 2023–2024.

L’analyse repose sur des données publiques détaillées, disponibles sur [Kaggle](https://www.kaggle.com/datasets/mexwell/nba-shots/data), et met en lumière des tendances spatiales, positionnelles et individuelles à travers des visualisations.

Deux notebooks sont proposés :

* `nba_offensive_behaviors_en.ipynb` : [Version anglaise](nba_offensive_behaviors_en.ipynb)
* `nba_offensive_behaviors_fr.ipynb` : [Version française](nba_offensive_behaviors_fr.ipynb)

---

## Données utilisées

Les données proviennent du lien suivant :
[https://www.kaggle.com/datasets/mexwell/nba-shots/data](https://www.kaggle.com/datasets/mexwell/nba-shots/data)

Elles contiennent tous les tirs tentés lors de chaque saison régulière NBA entre 2004 et 2024. Chaque saison est stockée dans un fichier `.csv` distinct.

---

## Organisation de l’analyse

L’analyse se structure en trois grandes parties :

### 1 - Répartition des tirs

* Proportions de réussite au tir
* Étude des tirs improbables
* Le biais de la ligne à 3 points
* Relation entre réussite au tir et distance au panier

### 2 - Spécificités offensives par poste et évolutions

* Comportements offensifs par poste
* Modernisation du poste de pivot

### 3. Focus sur deux joueurs emblématiques

* **Stephen Curry** : un expert du shoot à 3 points
* **Dirk Nowitzki** : l’intérieur moderne par excellence

---

## Lancer le projet

### Prérequis

Installer les bibliothèques nécessaires via pip :

```pip install -r requirements.txt```

### Lancer le notebook

Utiliser Jupyter pour lancer le notebook :

```jupyter notebook notebooks/nba_analysis_fr.ipynb```
