# 🌳 OC - Projet 2 : Participez à un concours sur la Smart City

Ce projet a été réalisé dans le cadre d’un challenge de data science proposé par la ville de Paris via la plateforme **Data is for Good**.  
L’objectif du challenge est de **réaliser une analyse exploratoire** sur un jeu de données portant sur les arbres de Paris, dans le cadre du programme municipal **“Végétalisons la ville”**.  
Cette analyse contribuera à **optimiser les tournées d’entretien des arbres**, pour réduire les trajets et entretenir un plus grand nombre d’arbres.

---

## 🎯 Objectif

> Identifier des informations utiles dans le jeu de données des arbres afin d’optimiser les tournées des agents municipaux.

---

## 📊 Travaux réalisés dans le notebook

Le notebook documenté présente une **analyse exploratoire structurée** autour des étapes suivantes :

### 1. 📁 Chargement et présentation des données
- Lecture du jeu de données officiel (CSV)
- Visualisation des 10 premières et 10 dernières lignes
- Affichage de la structure (types de colonnes, dimensions)

### 2. 🧼 Analyse et nettoyage
- Analyse des valeurs nulles
- Suppression ou traitement des doublons
- Distinction entre **variables qualitatives** (type d’arbre, essence, alignement, etc.) et **variables quantitatives** (hauteur, diamètre, etc.)

### 3. 📈 Statistiques descriptives
- Calcul de statistiques de base (moyenne, écart-type, min/max, etc.)
- Description de la distribution des variables principales

### 4. 🚩 Détection de données incohérentes
- Identification des valeurs aberrantes (ex : arbres avec hauteur = 0)
- Proposition de traitements pour fiabiliser les données

### 5. 🌱 Exploration ciblée
- Focus sur les **arbres remarquables**
- Début d’analyse géographique (selon les arrondissements, ou quartiers)

---

## 🧪 Livrables attendus

1. **Présentation PowerPoint** comprenant :
   - Présentation générale du dataset
   - Démarche méthodologique
   - Synthèse de l’analyse

2. **Notebook Jupyter** :
   - Explication des traitements
   - Commentaires pédagogiques pour un public non technique

---

## 🔗 Données

- Source officielle : [opendata.paris.fr – Arbres de Paris](https://opendata.paris.fr/explore/dataset/les-arbres/)

---

## 🛠️ Outils utilisés

- **Python**
- **Jupyter Notebook**
- Librairies : `pandas`, `matplotlib`, `seaborn`, `numpy` (détails dans le notebook)

---

## 🧠 Auteur

Projet réalisé par **AnthonyJVID** dans le cadre du parcours *AI Engineer* chez OpenClassrooms.

---

## 📄 Licence

Projet à but pédagogique. Les données sont publiques (licence Opendata Paris).
