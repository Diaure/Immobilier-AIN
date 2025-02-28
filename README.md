# 🏡 Analyse du Marché Immobilier - Département de l'Ain

## 💡 Contexte

Le marché immobilier est un enjeu majeur pour les collectivités locales et les professionnels du secteur. La Direction Départementale des Territoires (DDT) de l'Ain a fait appel à une analyse approfondie des transactions immobilières issues des Données de Valeurs Foncières (DVF) pour comprendre les dynamiques du marché et orienter les politiques publiques.

## 🎯 Objectif

Concevoir un tableau de bord interactif permettant d'explorer et de visualiser les tendances du marché immobilier dans l'Ain afin de répondre à des questions stratégiques :

* Quelles sont les communes les plus dynamiques en termes de transactions ?

* Comment évoluent les prix selon les typologies de biens ?

* Quelles sont les disparités entre les différents secteurs du département ?

* Quel est le profil type des biens vendus par commune ?

* Quelles sont les tendances du marché des terrains non bâtis ?

## 🔬 Données Utilisées

Les données DVF couvrant les trois dernières années comprennent :

* Informations sur la transaction : date, nature, valeur foncière

* Localisation : adresse, code postal, commune, cadastre

* Caractéristiques du bien : type de local (maison, appartement...), surface, nombre de pièces, terrain

## 🔄 Méthodologie

1. Préparation des données<br>
[Notebook préparation des données](https://drive.google.com/file/d/1DEgut-4meybhNhMBWM-q6ipD7vb7Kc7k/view?usp=sharing)
    * Nettoyage des valeurs aberrantes

    * Gestion des valeurs manquantes (imputation, suppression...)

    * Harmonisation des types de biens et des surfaces <br>

2. Exploration et Analyse

    * Distribution des prix et surfaces

    * Corrélations entre typologies et prix

    * Identification des zones de tension

3. Visualisation et Tableau de Bord<br>
[Dashboard](https://drive.google.com/file/d/1mO7Mi959hcJWGvjGfeQMJmpxh3z0YIDu/view?usp=sharing)

    * Cartographie des prix au m² par commune

    * Graphiques dynamiques sur l'évolution des prix

    * Analyse des typologies et des tendances du marché

**Technologies Utilisées : Python (Pandas, Matplotlib, Seaborn), Power BI**

## 🎉 Résultats et Insights <br>

![Analyse des prix](https://github.com/Diaure/Immobilier-AIN/blob/main/03_Images/Analyse%20des%20prix.PNG)<br>

![Types de biens](https://github.com/Diaure/Immobilier-AIN/blob/main/03_Images/Types%20de%20biens.PNG)<br>

![Zones en tension](https://github.com/Diaure/Immobilier-AIN/blob/main/03_Images/zones%20en%20tensions%20%26%20terrains%20non%20b%C3%A2tis.PNG)<br>

## 💼 Livrables

  * Un tableau de bord interactif pour l'analyse des tendances

  * Une méthodologie de traitement des données

  * Un guide utilisateur pour faciliter l'interprétation des données

## 🚀 Impact et Perspectives

Ce projet permet aux acteurs locaux de :

  * Mieux comprendre le marché immobilier de l'Ain

  * Adapter les politiques d'urbanisme et d'aménagement

  * Anticiper les évolutions du marché et identifier les opportunités d'investissement
