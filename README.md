# Iris Classification using Machine Learning

## 1. Présentation du projet

Ce projet consiste à classifier trois espèces de fleurs du genre *Iris* à partir de leurs caractéristiques morphologiques en utilisant des algorithmes de Machine Learning.

## 2. Dataset

Le jeu de données utilisé est `IRIS.csv`.

Il contient 150 observations et les variables suivantes :

- `SepalLengthCm` : longueur du sépale.
- `SepalWidthCm` : largeur du sépale.
- `PetalLengthCm` : longueur du pétale.
- `PetalWidthCm` : largeur du pétale.
- `Species` : espèce de la fleur.

La colonne `Id` est un identifiant et n'est pas utilisée pour l'entraînement des modèles.

## 3. Objectifs

- Explorer et analyser le jeu de données.
- Préparer les données pour l'entraînement.
- Construire des modèles de classification.
- Évaluer les performances des modèles.
- Comparer les résultats obtenus avec différentes tailles de données d'entraînement.

## 4. Algorithmes utilisés

Trois algorithmes de Machine Learning sont étudiés :

- Decision Tree
- K-Nearest Neighbors (KNN)
- Random Forest

## 5. Évaluation des modèles

Les performances sont évaluées à l'aide des métriques suivantes :

- Accuracy
- Precision
- Recall
- F1-score
- Matrice de confusion

Une comparaison est également réalisée entre l'utilisation de 100 % et 50 % des données d'entraînement.

## 6. Outils utilisés

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 7. Structure du projet

- `Iris_Classification.ipynb` : notebook contenant les étapes d'analyse, de prétraitement, d'entraînement et d'évaluation.
- `IRIS.csv` : jeu de données utilisé dans le projet.

## 8. Conclusion

Ce projet permet d'étudier l'application des algorithmes de Machine Learning à la classification des espèces d'Iris à partir de leurs caractéristiques morphologiques, ainsi que de comparer leurs performances.
