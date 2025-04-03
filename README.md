# 🇫🇷📦 Étude de Marché – Exportation de Poulet Français

## 🎯 Objectif

Déterminer les **meilleurs pays vers lesquels exporter du poulet français** à l’aide d’analyses statistiques et de modèles de machine learning.

Le projet s’appuie sur deux notebooks complémentaires :

1. **Préparation et nettoyage des données**
2. **Analyse exploratoire, corrélations, ACP et classification**

---

## 📁 Structure du projet

### 🗂️ `IM_Etude_de_marche_poulets_francais_Preparation_donnees.ipynb`

> 🔧 **Préparation des données**

Ce notebook contient les étapes de :
- Chargement et exploration initiale des données
- Nettoyage (valeurs manquantes, renommage, conversions)
- Fusion des différentes sources en un seul DataFrame exploitable

🎯 **Objectif** : obtenir une base de données propre pour l’analyse.

---

### 📊 `IM_clustering_ACP_Correlations_visualisations_etude_de_marche_pouletFR.ipynb`

> 📈 **Analyse exploratoire et modélisation**

Ce notebook contient :
- **Analyse de corrélations** : Matrice de corrélation & ACP (Analyse en Composantes Principales)
- **Classification & segmentation** :
  - Algorithme **Random Forest** pour identifier les variables les plus discriminantes
  - Algorithme **K-Means** pour segmenter les pays selon leur profil
- **TOP 5 pays** identifiés comme les plus pertinents à viser pour l’export

---

## 🧰 Technologies utilisées

- Python 3
- Bibliothèques :
  - `pandas`, `numpy` pour la manipulation des données
  - `matplotlib`, `seaborn` et 'plotly' pour la visualisation
  - `scikit-learn` pour les modèles de machine learning (ACP, KMeans, Random Forest)

---

## 🏁 Résultat attendu

> ✅ Une **liste de 5 pays prioritaires** pour l’exportation de poulet français, issue d’une démarche analytique et prédictive rigoureuse.

---

## 📌 Auteurs

Projet réalisé dans le cadre de l’initiative **Ichraf MOUELHI**.

---


