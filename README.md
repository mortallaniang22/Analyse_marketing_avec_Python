# Analyse marketing avec Python

Ce projet est une analyse des ventes, du chiffre d'affaires et du comportement client d'une librairie en ligne.

Données traitées :

- table **customers** : donne des informations sur les clients
- table **products** : donne des informations sur les produits
- table **transactions** : donne des informations sur des opérations de vente. 


## [Préparation - Exploration des données](./Exploration_et_nettoyage_des_données.ipynb)
Dans cette partie, nous avons essentiellement travailler sur la préparation des données. Dans ce cadre, nous sommes passés par les process suivants:

- Nettoyage des valeurs manquantes.
- Nettoyage des doublons.
- Détection et analyse des outliers.
- consolidation des tables.
 
L'analyse de chacune des variables nous a permis de visualiser et de mieux comprendre les données.

Voir l'image ci-dessous qui nous permet de visaliser la distribution de la variable age à titre d'exemple.

<img alt="MySQL" width="60%" src="./tranche.png" style="padding-right:10px;" />

## [Analyse du chiffre d'affaires et le comportement des clients](./KPIs_et_comportement_client.ipynb)

### Analyse du chiffre d'affaires
- Répartition du chiffre d'affaires sur les clients et les catégories de produits.
- Evolution du chiffre d'affaires
- Chiffre d'affaires glissant
- Top chiffre d'affaires

<img alt="MySQL" width="80%" src="./seriet.png" style="padding-right:10px;" />

### Analyse du comportement des clients
- Test du chi carré
- Test de Spearman
- Test ANOVA
<img alt="MySQL" width="100%" src="./matricecor.png" style="padding-right:10px;" />


## outils
Python, Pandas, Seaborn, Scipy, Numpy

## Données:
- Fichier clients
- Fichier produits
- Fichiers transactions
