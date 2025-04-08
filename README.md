# 🏋️‍♂️ Body Performance Data Analysis

Ce projet est une **étude exploratoire approfondie** sur un jeu de données de performance physique. L’objectif est de comprendre les facteurs qui influencent les performances sportives à partir de données démographiques, physiologiques et fonctionnelles.

## 📊 Objectifs de l'analyse

- Étudier la répartition des individus par **classe de performance**
- Analyser les **corrélations entre les variables numériques**
- Visualiser la **distribution des variables** selon les classes
- Identifier les **caractéristiques les plus discriminantes**
- Appliquer des techniques de **réduction de dimension** (PCA)
- Effectuer un **clustering non supervisé** (KMeans) pour détecter des regroupements naturels

## 🔧 Outils & bibliothèques

- `pandas`, `numpy` pour la gestion des données
- `matplotlib`, `seaborn` pour les visualisations
- `scikit-learn` pour le prétraitement, le PCA, le clustering et la modélisation

## 📈 Méthodologie

1. **Préparation des données** : traitement des valeurs manquantes, encodage des variables catégorielles
2. **Analyse descriptive** :
   - Statistiques globales
   - Visualisations (distributions, boxplots, heatmaps)
3. **PCA** : réduction de dimension et visualisation dans l’espace projeté
4. **Clustering (KMeans)** : segmentation des individus en groupes et comparaison avec les classes
5. **Random Forest** : analyse de l’importance des variables pour la classification

## 🧠 Résultats

- Mise en évidence des **caractéristiques physiques associées à chaque classe de performance**
- Utilisation du **PCA** pour visualiser les clusters dans un espace réduit
- Détection d’une bonne cohérence entre les **clusters non supervisés** et les **classes réelles**
- Identification des variables les plus influentes via l’**importance des features** (Random Forest)

## 🚀 Perspectives

- Amélioration du modèle avec des algorithmes supervisés (SVM, XGBoost)
- Visualisation interactive avec Streamlit ou Dash
- Création d’un système de recommandation basé sur les caractéristiques physiques

# body-performance-analysis
