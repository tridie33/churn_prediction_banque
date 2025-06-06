# Prédiction du Churn Bancaire 📊🏦

Ce projet a pour objectif d'analyser les facteurs influençant le départ des clients (churn) d'une banque, à partir d'un jeu de données réel provenant de Kaggle. À travers une analyse exploratoire, une visualisation et l'entraînement de modèles de machine learning, nous cherchons à identifier les profils à risque de départ.

## Données

Les données utilisées sont issues du dataset [Churn Modelling](https://www.kaggle.com/datasets/anandshaw2001/customer-churn-dataset) disponible sur Kaggle.

- 10 000 clients
- Variables : âge, genre, produits bancaires, salaire estimé, etc.
- Cible : `Exited` (1 = client parti, 0 = client resté)

## Technologies utilisées

- Python 3
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn

## Modèles entraînés

- Régression Logistique
- Forêt Aléatoire (Random Forest)

## Résultats

Les visualisations permettent d’identifier des tendances fortes :
- Les clients plus âgés et ceux avec moins de produits bancaires quittent plus fréquemment.
- Le sexe, la localisation géographique et le crédit jouent aussi un rôle.

La Random Forest donne de meilleurs résultats que la régression logistique sur notre jeu de test.

## Lancer le notebook :

Ouvrez analyse_churn_clients_banque.ipynb dans Jupyter Notebook ou Google Colab.

Merci!! :)
