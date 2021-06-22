# Préparation des données OpenFoodFacts pour Santé Publique France

Visualiser le notebook en ligne : [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Abdess/sante_publique_france/HEAD)

![Santé Publique France](data/images/Sante-publique-France-logo.png)

L'agence "Santé publique France" a lancé un appel à projets pour rendre les données de santé plus accessibles.

![OpenFoodFacts](data/images/OpenFoodFacts.png)

L’agence souhaite faire explorer et visualiser les données d'OpenFoodFacts pour que ses agents puissent les exploiter.

## Visualiser le Dashboard en ligne avec Apache Superset

[![Dashboard](https://superset.apache.org/static/superset-logo-horiz-apache-ac1a91de27eed9f5c53944c555a39c6f.svg)](https://openfoodfactsspf.herokuapp.com/superset/dashboard/openfoodfacts/)

[![Aperçus du Dashboard](data/images/Dashboard-Preview.png)](https://openfoodfactsspf.herokuapp.com/superset/dashboard/openfoodfacts/)

## [Lire la présentation](https://github.com/Abdess/sante_publique_france/raw/main/P3_03_Pr%C3%A9sentation.pptx)

## Préparation de l'environnement

    pip install -r requirements.txt

## Explorer le notebook de nettoyage

    jupyter notebook P3_01_nettoyage.ipynb

## Visualiser le Dashboard Voilà

    voila --template=flex P3_02_dashboard.ipynb
