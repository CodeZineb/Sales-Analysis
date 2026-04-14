Tableau de Bord d’Analyse des Ventes
 Présentation du Projet :

Ce projet consiste en la réalisation d’un tableau de bord d’analyse des ventes en utilisant SQL Server (SSMS) et Power BI.
L’objectif est de transformer des données brutes en informations exploitables à travers une modélisation efficace et des visualisations interactives.

Outils & Technologies :
SQL Server Management Studio (SSMS)
Power BI Desktop
Modélisation de données (Schéma en étoile)
Data Visualization
Modélisation des Données :

Un schéma en étoile (Star Schema) a été conçu avec les tables suivantes :

📂 Tables de dimensions :
DIM_Calendar
DIM_Customer
DIM_Product
 Table de Faits :
DIM_FactInternetSales

Les données ont été extraites, nettoyées et transformées à l’aide de requêtes SQL avant leur intégration dans Power BI.

 Fonctionnalités du Dashboard :

Le tableau de bord permet d’analyser :

Les ventes par catégorie de produit (Bikes, Accessories, Clothing)
Les ventes par client (Top clients)
Les ventes par produit
L’évolution des ventes dans le temps (année, mois, jour)
La répartition géographique des ventes (carte)
Des filtres interactifs (année, mois, produit, ville)

Insights Clés :

La catégorie Bikes représente la majorité des ventes (~87%)
Les ventes varient selon les périodes (jours/mois)
Certains clients génèrent une part importante du chiffre d’affaires
La carte permet d’identifier les zones géographiques les plus performantes
 
 Utilisation :
 
Télécharger le fichier .pbix
Ouvrir avec Power BI Desktop
Actualiser les données si nécessaire
Explorer les visualisations interactives
Compétences Développées :
Analyse de données avec SQL
Nettoyage et transformation des données
Modélisation (Schéma en étoile)
Data Visualization (Power BI)
Analyse des indicateurs de performance (KPI)
