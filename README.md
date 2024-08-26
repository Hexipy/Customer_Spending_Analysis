# Customer_Spending_Analysis
**Contexte et Objectif**

Le projet "Analyse des Dépenses Client" vise à explorer et à analyser un ensemble de données relatif aux dépenses des clients dans différents pays. Ce projet a pour but de fournir des insights significatifs sur les habitudes de dépenses des clients, en identifiant des tendances et des modèles dans les données. L'objectif final est de créer un rapport détaillé et des visualisations qui permettent de mieux comprendre les comportements de consommation dans divers contextes géographiques.
**Données**

Les données utilisées dans ce projet proviennent d'un fichier CSV contenant les informations suivantes :

    Pays : Le pays où le client réside.
    Âge : L'âge du client.
    Genre : Le genre du client (Male/Female).
    Dépenses des clients : Le montant total des dépenses du client en euros.

Exemple de Données
Pays	Âge	Genre	Dépenses des clients
France	32	Female	150.50
Germany	45	Male	200.75
Spain	28	Female	75.25
Italy	39	Male	180.00
UK	52	Female	250.30
Étapes du Projet

    Préparation des Données
        Chargement des Données : Importation du fichier CSV dans un DataFrame.
        Exploration Initiale : Affichage d'un résumé technique des données, incluant les types de données des champs et le nombre de valeurs non-nulles.

    Nettoyage des Données
        Gestion des Valeurs Manquantes : Identification et traitement des valeurs NaN (Not a Number) dans les colonnes. Suppression des lignes avec des valeurs manquantes critiques.
        Conversion des Types de Données : Conversion des âges en entiers et des dépenses en flottants, si nécessaire.
        Suppression des Valeurs Inexactes : Nettoyage des lignes avec des dépenses inférieures à 10 € et suppression des doublons.

    Analyse des Données
        Calcul des Statistiques : Calcul de la médiane et de la moyenne des colonnes "Âge" et "Dépenses des clients".
        Visualisation des Dépenses : Création d'un graphique à barres pour visualiser les dépenses des clients par pays, avec ajustement des valeurs sur l'axe des y pour améliorer la lisibilité.

    Export des Données Nettoyées
        Création d'un Fichier CSV Nettoyé : Export des données nettoyées dans un nouveau fichier CSV contenant uniquement les colonnes "Pays", "Âge", "Genre" et "Dépenses des clients".

    Documentation et Rapport
        Documentation : Rédaction d'un rapport expliquant les étapes de nettoyage, les résultats de l'analyse et les visualisations produites.
        Préparation du Notebook Jupyter : Nettoyage des sorties et sauvegarde du notebook avec toutes les étapes du projet pour soumission.

**Outils et Technologies**

    Python : Langage de programmation utilisé pour la manipulation et l'analyse des données.
    Pandas : Bibliothèque Python pour la gestion des données.
    Matplotlib : Bibliothèque Python pour la création de visualisations graphiques.
    Jupyter Notebook : Environnement de développement interactif pour documenter et exécuter le code.

**Résultats Attendus**

Le projet devrait aboutir à une compréhension approfondie des dépenses des clients par pays, avec des visualisations claires montrant les différences et similitudes dans les comportements de consommation. Les insights fournis permettront de faire des recommandations basées sur les données pour des stratégies de marketing et d'analyse de marché.
