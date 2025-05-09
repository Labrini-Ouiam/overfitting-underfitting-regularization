# Overfitting, Underfitting & Regularization

Ce projet explore les concepts de **surdéapprentissage (overfitting)**, **sous-apprentissage (underfitting)** et les techniques de **régularisation L1 (LASSO)** et **L2 (Ridge)** à travers un modèle de régression polynomiale multivariée appliqué au dataset *Advertising*.

## 📌 Objectif

- Implémenter la régression polynomiale multivariée.
- Ajouter des termes de régularisation L1 (LASSO) et L2 (Ridge).
- Comparer les performances du modèle (avec et sans régularisation) sur les jeux d'entraînement et de test.

## 🗃️ Dataset

Le jeu de données **Advertising** contient des informations sur les budgets publicitaires et les ventes correspondantes. Les variables indépendantes comprennent :
- TV
- Radio
- Newspaper

La variable cible est :
- Sales

## 🧠 Méthodes

1. Régression polynomiale multivariée (sans régularisation)
2. Régression avec :
   - Régularisation L1 (LASSO)
   - Régularisation L2 (Ridge)
3. Comparaison des performances avec :
   - Mean Squared Error (MSE)
   - R² Score
   - Analyse via un tableau de comparaison

## 📊 Résultats

Les résultats sont présentés sous forme de tableau dans le notebook, montrant l'impact de chaque méthode de régularisation sur les erreurs de prédiction sur les jeux **Train** et **Test**.

## 🔧 Technologies

- Python
- NumPy, Pandas
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

## 📁 Fichier

- `overfitting-underfitting-regularization.ipynb` : Le notebook principal contenant le code, les visualisations, et les analyses.

## 👤 Auteur

**Labrini Ouiam**


---

> Pour toute remarque ou amélioration, n'hésitez pas à créer une issue ou un pull request !
