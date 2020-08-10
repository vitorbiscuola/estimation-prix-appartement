# Projet : Estimation du Prix d'un Appartement à Paris

* Ce projet a été réalisé lors de la formation "Data Science - Essentials" (Jedha Bootcamp).
* Il consiste à estimer le prix d'un appartement à Paris à partir des données publiques.

## Source des données
* Source de données : https://www.data.gouv.fr/en/datasets/demandes-de-valeurs-foncieres/
* Fichiers recupérés : 2018 (année complète) et 2019 (jusqu’à Mai/2019)

## Préparation des données
* Etape 1 : compréhension des données
* Etape 2 : une partie du traitement des données a été effectuée en amont (SQL) : compilation des fichiers ; regroupement des données ; filtres sur département = 75 et type local = appartement ; suppression des variables
* Etape 3 : définition des features
* Etape 4 : traitement des valeurs manquantes et outliers

## Méthodes
* Régression Linéaire Simple
* Régression Linéaire Multiple
* XGBoost

## Axes d'amélioration
* Utiliser l'historique complet des données publiques (depuis 2015)
* Nouvelles features (Ex : étage). Données supplémentaires disponibles sur https://datafoncier.cerema.fr/
* Tuning des paramètres
* Utilisation d'autres modèles

