# Projet Python S1 : the Movie Database
Auteurs : Claire He, Marie Ganon

## Prédiction de la "recette" parfaite pour un film performant

Ce projet s'inscrit dans le cadre du projet d'informatique du cours de Python pour la datascientist du 1er semestre de 2ème année à l'ENSAE. 
A partir de la base Movie Database disponible : https://www.kaggle.com/rounakbanik/the-movies-dataset que nous avons nettoyée, complétée par du scrapping de mots-clés sur le site IMDB et d'une base labellisée de commentaires IMDB issue d'un projet de classification de sentiments binaires (disponible http://ai.stanford.edu/~amaas/data/sentiment/), nous souhaitons à l'aide de modèles de ML et de NLP prédire la "recette", s'il y en a une, du succès d'un film au cinéma. 

## Détails des fichiers présents sur le repo

- Scraping_nettoyage.ipynb : Notebook comprenant les codes de nettoyage de la base initiale, ainsi que les différents scrapping réalisés
- Statistiques_descriptives.ipynb : Notebook comprenant les codes de visualisation des données et de statistiques descriptives
- Modélisation.ipnyb : Notebook comprenant les codes relatifs à la modélisation du problème
- movies_metadata.csv.zip : Dataset originel, disponible à l'adresse ci-dessus
- base.csv : Base de données nettoyée
- base_keywords2.csv.zip : Base de données comportant les mots-clés scrappés sur IMDB, ainsi que l'identifiant *imdb_id* du film et son titre *original_title*

## Méthodes utilisées 
LDA, régression linéaire,  sentiment analysis via classificateur bayésien naïf et SVM
