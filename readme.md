# Projet 3 : Exploration des Tendances du Marché Airbnb

## Description  
Ce projet vise à analyser les données des annonces Airbnb à New York City, qui propose une variété de logements temporaires pour les voyageurs. L'objectif est de fournir des informations précieuses à une start-up immobilière sur le marché des locations à court terme, en se concentrant spécifiquement sur les chambres privées.

## Contexte  
Bienvenue à New York City, l'une des villes les plus visitées au monde. Il existe de nombreuses annonces Airbnb à New York pour répondre à la forte demande d'hébergement temporaire pour les voyageurs, qui peuvent séjourner de quelques nuits à plusieurs mois. Dans ce projet, nous examinerons de plus près le marché Airbnb de New York en combinant des données provenant de plusieurs types de fichiers, tels que .csv, .tsv et .xlsx.

## Données  
Les fichiers suivants sont disponibles dans le dossier de données :
- `airbnb_price.csv`
- `airbnb_room_type.xlsx`
- `airbnb_last_review.tsv`

## Méthodologie  
Voici les étapes suivies pour réaliser cette analyse :

1. **Chargement des données**  
   Importation des données à partir des fichiers fournis.

2. **Fusion des trois DataFrames**  
   Combinaison des données provenant des trois fichiers pour créer un seul ensemble de données.

3. **Détermination des dates de la première et de la dernière évaluation**  
   Identification des dates des évaluations les plus anciennes et les plus récentes.

4. **Comptage des annonces de chambres privées**  
   Calcul du nombre total d'annonces de chambres privées.

5. **Calcul du prix moyen des annonces**  
   Calcul du prix moyen des annonces, arrondi à deux décimales.

6. **Création d'un DataFrame avec les quatre valeurs de solution**  
   Stockage des résultats dans un DataFrame appelé `review_dates` avec les colonnes suivantes : `first_reviewed`, `last_reviewed`, `nb_private_rooms`, et `avg_price`.

## Résultats  
Les résultats de l'analyse incluent :
- Dates de la première et de la dernière évaluation.
- Nombre d'annonces de chambres privées.
- Prix moyen des annonces.