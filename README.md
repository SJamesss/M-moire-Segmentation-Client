# Segmentation Client par Apprentissage Non Supervisé
Ce projet a été réalisé dans le cadre d'un mémoire pour le **Master 2 Chef de Projet en Intelligence Artificielle** d'Eugenia School (2024-2025).

Le notebook `segmentation_clients.ipynb` présente l'intégralité de la démarche technique, de l'exploration des données à la modélisation, pour répondre à la problématique de la segmentation client dans le secteur du retail.
 
## Problématique

> Comment segmenter efficacement la clientèle pour optimiser les campagnes marketing et maximiser le ROI publicitaire dans un contexte retail multi-catégories ?
 
## Démarche Méthodologique
 
L'analyse s'articule autour des étapes suivantes :
1.  **Analyse Exploratoire des Données (EDA)** : Étude statistique et visuelle du jeu de données pour en comprendre les caractéristiques principales.
2.  **Feature Engineering** : Création de variables comportementales pertinentes pour enrichir l'analyse (génération, pouvoir d'achat, intensité d'achat, etc.).
3.  **Modélisation par Clustering** : Comparaison de plusieurs algorithmes d'apprentissage non supervisé (K-Means, DBSCAN, Clustering Hiérarchique) pour identifier la meilleure approche.
4.  **Évaluation et Interprétation** : Utilisation de métriques (Score de Silhouette, Davies-Bouldin, Calinski-Harabasz) pour valider le choix du modèle (K-Means avec K=9) et interprétation business des segments obtenus.
 
## Données
 
Le projet utilise le jeu de données `retail_sales_dataset.csv`, qui est un dataset simulé de 1000 transactions de clients, représentatif des comportements d'achat dans le retail en France.
 
## Technologies Utilisées
 
*   **Langage :** Python 3
*   **Librairies principales :**
     *   Pandas
     *   NumPy
     *   Scikit-learn
     *   Matplotlib
     *   Seaborn
