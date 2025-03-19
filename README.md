# Ateliers Data Tuxae 2024-2025

_Rémy SIAHAAN--GENSOLLEN_

Ce dépôt contient quelques ressources relatives aux ateliers que j'ai organisés 
pour l'association Tuxae durant l'année scolaire 2024-2025 à l'ENSAE Paris.
Il est loin d'être complet, mais comprend notamment les jeux de données 
utilisés, des slides ainsi que quelques extraits de code. Ces ressources 
s'adressent principalement aux premières années et à des personnes n'ayant 
jamais fait de science des données, bien que mon ambition soit de 
progressivement élever le niveau.

Les outils utilisés sont principalement des jeux de données publics 
(Kaggle, UC Irvine Machine Learning Repository, etc.), souvent 
accompagnés de slides en support, avec une démonstration de code en 
direct dans un environnement Jupyter hébergé sur le 
[SSPCloud (Onyxia)](https://datalab.sspcloud.fr).

Ci-dessous un sommaire résumant très succinctement les ateliers :

### 0 - Présentation de la Data Science et du Machine Learning

Petit atelier de présentation. Les slides ne sont pas complètes.

### 1 - Introduction à la classification

Présentation d'une tâche de classification concrète. Présentation du kNN classique
(distance euclidienne, implémentation naïve), et code "à la main" (avec numpy).

- _Cortez, P., Cerdeira, A., Almeida, F., Matos, T., & Reis, J. (2009). 
Wine Quality [Dataset]._ UCI Machine Learning Repository.
https://doi.org/10.24432/C56S3T.

- _Fisher, R. (1936). Iris [Dataset]._ UCI Machine Learning Repository.
https://doi.org/10.24432/C56C76.

### 2 - Classification. Prédire un cancer du sein ?

Approfondissements sur la classification. Brève présentation historique
du problème de la détection du cancer du sein, apport de la data. Introduction
aux concepts de validation croisée (train-test-split, K-Fold, stratification...).
Introduction au concept d'hyper-paramètre et hyper-parameter tunning (pas encore 
de grid search quelconque, juste une boucle). Autres métriques classiques pour la
classification binaire (précision, rappel, f1). Standardisation, normalisation.
Mention des questions d'interprétabilité et de réduction de dimension.

- _Wolberg, W., Mangasarian, O., Street, N., & Street, W. (1993).
Breast Cancer Wisconsin (Diagnostic) [Dataset]._
UCI Machine Learning Repository. https://doi.org/10.24432/C5DW2B.

### 3 - Régression. Prédire le prix des maisons ?

- _Anna Montoya and DataCanary. House Prices (2016) - Advanced Regression Techniques._
Kaggle. https://kaggle.com/competitions/house-prices-advanced-regression-techniques