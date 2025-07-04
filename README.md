# Segmentation de clients pour Olist - Projet Data Science

## 🎯 Objectif du projet

Ce projet a été réalisé dans le cadre d’une mission professionnelle simulée pour Olist, une entreprise brésilienne spécialisée dans les solutions de vente sur les marketplaces.  
L'objectif est de **segmenter les clients** à partir de données transactionnelles et de satisfaction afin d'aider l’équipe marketing à mieux cibler ses actions.

---

## Contexte de la mission

Olist souhaite créer une première segmentation client à des fins marketing.  
En tant que consultante data, j’ai été sollicitée pour :

- Concevoir une segmentation pertinente et exploitable basée sur les données RFM (Récence, Fréquence, Montant) et les scores de satisfaction.
- Proposer une stratégie de maintenance du modèle en analysant la stabilité des clusters dans le temps.

---

## 🛠️ Méthodologie

### 1. **Exploration et préparation des données**
- Analyse des données issues de plusieurs tables : commandes, produits, clients, avis.
- Construction de variables RFM.
- Intégration des scores de satisfaction.

### 2. **Clustering non supervisé**
- Comparaison de plusieurs modèles (K-Means, DBSCAN).
- Sélection du nombre optimal de clusters avec la méthode du coude et le score de silhouette.
- Analyse métier des segments.

### 3. **Stabilité du modèle**
- Simulation sur différentes périodes pour évaluer la robustesse de la segmentation à l’aide de la métrique ARI (Adjusted Rand Index).
- Recommandation de mise à jour tous les 15 jours pour conserver une qualité de segmentation optimale.

---

## 📊 Résultats

- **4 segments clients** ont été identifiés : Champions, Loyaux, À risque, Perdus.
- L’ajout des **Review Scores** a permis une meilleure séparation des segments.
- **Des recommandations concrètes** de ciblage marketing ont été proposées pour chaque segment.
- Une stratégie de **mise à jour du modèle** basée sur la stabilité des clusters a été définie.

---

## 🖼️ Visualisation

Une présentation complète a été réalisée pour exposer les résultats et convaincre les parties prenantes internes.  
Elle contient des graphiques 3D, boxplots, résultats d’ARI, et une synthèse des insights business.

---

## 🛠️ Stack technique
- Python (Pandas, Scikit-learn, Matplotlib, Seaborn, Yellowbrick)
- SQL (PostgreSQL)
- Jupyter Notebook
- Visualisation avec PowerPoint / Matplotlib 3D


## Auteure

Oumou Faye  
Formation : Data Scientist  
Mentor : Medina Hadjem
