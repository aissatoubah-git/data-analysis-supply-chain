# Analyse de données volumineuses - Supply Chain 

Ce projet a pour objectif d'explorer, nettoyer et analyser un jeu de données massif lié à la chaîne d'approvisionnement, en utilisant des outils adaptés au traitement de big data.

# Objectif

- Nettoyer et analyser un dataset volumineux (+2M lignes) lié aux performances logistiques.
- Identifier les tendances : retards de livraison, bénéfices, catégories de produits, etc.
- Développer un pipeline rapide et reproductible sous Google Colab.

# Outils utilisés

- Python (Dask, Pandas, Seaborn, Matplotlib)
- Google Colab pour l’exécution dans le cloud
- Dask pour le traitement parallèle de fichiers CSV très volumineux
- GitHub pour publier le projet

# Données

- Source: (https://www.kaggle.com/datasets/shashwatwork/dataco-smart-supply-chain-for-big-data-analysis)
- Format : CSV
- Taille: ~2M lignes, 53 colonnes

# Étapes du projet

1. Chargement efficace des données avec Dask.
2. Nettoyage :
   - Sélection des colonnes utiles
   - Conversion des dates
   - Suppression des lignes trop incomplètes
3. Analyse exploratoire:
   - Moyennes des délais réels vs prévus
   - Retards de livraison
   - Bénéfice moyen par catégorie
4. Visualisations :
   - Histogrammes, barplots, scatter plots
5. Exportation d’un échantillon nettoyé pour réutilisation

# Résultats obtenus

- Pipeline capable de traiter un CSV de 2M+ lignes en moins de 2 minutes
- Visualisation claire des retards et catégories à bénéfices négatifs
- Nettoyage des données corrompues ou incomplètes
- Gain estimé de 40% sur le temps de traitement vs Pandas seul

# Lancement du notebook

Notebook directement dans Google Colab : https://github.com/aissatoubah-git/data-analysis-supply-chain/blob/main/TraitementAnalyseBigDatasets.ipynb

# Auteur

- Aissatou BAH
- Étudiante en Data Analyst | À la recherche d’un stage  




