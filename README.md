# 🏠 House Prices Prediction - Kaggle Regression Challenge

Ce projet a été réalisé dans le cadre d’un exercice pratique de machine learning supervisé en régression, en utilisant les données du concours **[House Prices - Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques)** sur Kaggle.

---

## 📌 Objectif

Prédire le prix de vente (`SalePrice`) de maisons résidentielles à Ames, Iowa, à partir de caractéristiques structurelles, temporelles et géographiques.

---

## 🧪 Méthodologie

Le projet a été structuré en 8 étapes :

1. **Input**  
   - Données fiables issues de Kaggle.
   - Données nettoyées, structurées, et bien annotées.

2. **Data Analysis (EDA)**  
   - Exploration approfondie avec visualisations.
   - Identification des variables clés et outliers.

3. **Preprocessing**  
   - Encodage des variables catégorielles.
   - Imputation des valeurs manquantes.
   - Transformation logarithmique de la variable cible.

4. **Feature Selection**  
   - Sélection manuelle guidée par la corrélation, l’expertise métier, et SHAP.
   - Sélection finale de 15 variables.

5. **Model Training**  
   - Entraînement de plusieurs modèles : Ridge, Lasso, XGBoost.
   - Optimisation des hyperparamètres avec Optuna.

6. **Stacking & Feature Analysis**  
   - Combinaison des modèles avec **StackingRegressor**.
   - Analyse de l’importance des variables avec SHAP.

7. **Evaluation**  
   - Validation croisée via RMSE.
   - Comparaison des performances des modèles.

8. **Residual Analysis**  
   - Analyse graphique des résidus.
   - Visualisation des erreurs de prédiction.

---

## 🏁 Résultats

- **RMSE sur la compétition Kaggle : 0.14143**
- **Modèle final :** `Stacking(Ridge + Lasso + XGBoost)`
- **Fichier de soumission :** `submission_stacking.csv`

---

## 📁 Structure du projet

## 📚 Ressources

- [Kaggle Dataset & Competition](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques)
- [Scikit-learn Documentation](https://scikit-learn.org/stable/documentation.html)
- [SHAP Documentation](https://shap.readthedocs.io/en/latest/)
- [Optuna Documentation](https://optuna.org/)

---

## 👨‍💻 Auteur

**Yann Keita**  
Master Data Management in Bioscience  
Université Catholique de Lille  
📫 Contact : [yann.keita@lacatholille.fr](mailto:yann.keita@lacatholille.fr)
