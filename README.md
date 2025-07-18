**Contexte**

Data Scientist chez Fruits!, une startup AgriTech spécialisée dans la reconnaissance de fruits par robotique intelligente, nous avons été missionnés pour reprendre, améliorer et déployer une chaîne de traitement Big Data permettant de préparer les données d’images de fruits pour de futures prédictions via un modèle TensorFlow.

L’objectif est de traiter des données massives issues de l’application mobile de reconnaissance de fruits, à l’aide de PySpark sur un environnement AWS EMR, tout en assurant la scalabilité, la conformité RGPD et l’optimisation des coûts.

***

**Objectifs**

Concevoir une architecture Big Data scalable avec AWS EMR.

Compléter un pipeline PySpark avec réduction de dimension (PCA).

Intégrer les poids TensorFlow pour permettre de l’inférence distribuée.

Garantir la conformité RGPD en traitant les données en Europe.

Préparer une démonstration technique de la chaîne de traitement dans le cloud.

***


**Étapes du projet**

1. Développement local de la chaîne de traitement

Environnement PySpark configuré en local

Nettoyage des données images (formatage, filtrage, vectorisation)

Réduction de dimension par PCA pour faciliter le traitement massif

Livrable : Notebook local PySpark avec pipeline PCA complet


2. Migration vers AWS EMR (Traitement distribué)

Création d’un cluster EMR avec configuration optimisée

Utilisation d’AWS S3 pour le stockage des données et des sorties

Intégration des poids du modèle TensorFlow via broadcast PySpark pour l’inférence

Livrable : Pipeline distribué opérationnel sur AWS EMR

***

**Technologies utilisées**

PySpark : Traitement parallèle des données, PCA

TensorFlow : Utilisation des poids pour inférence distribuée

AWS EMR : Exécution Big Data à grande échelle

AWS S3 : Stockage des données/images et résultats

AWS IAM : Gestion des droits d’accès

PCA : Réduction de dimension sur données d’images

***

**RGPD et Scalabilité**
Traitement des données exclusivement sur instances EU AWS pour conformité RGPD

Sécurisation des accès aux buckets S3 via politiques IAM

Chaîne pensée pour scalabilité progressive après mise en production de l’app mobile

***

📬 Contact

Nom : Maty KANE

Email : matymbaye09@live.fr

GitHub : github.com/MatyKane

**Projet réalisé dans le cadre du parcours Data Scientist – OpenClassrooms.**