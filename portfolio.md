---
layout: page
title: Portfolio
---

<style>
/* Largeur centrée + lisibilité */
.main-content {
  max-width: 980px;
  margin: 0 auto;
  padding: 2rem 1.5rem;
  font-size: 18px;
  line-height: 1.75;
}

/* Titres */
.main-content h1 { font-size: 2.2rem; }
.main-content h2 { font-size: 1.8rem; }
.main-content h3 { font-size: 1.35rem; }

/* Listes */
.main-content ul, 
.main-content ol {
  padding-left: 1.4rem;
}
.main-content li {
  margin: 0.3rem 0;
}

/* Mobile */
@media (max-width: 600px) {
  .main-content {
    font-size: 16px;
    padding: 1.25rem 1rem;
  }
}
</style>


Data Analyst / BI orienté décision métier. Spécialisé en Power BI, automatisation analytique et modélisation statistique.  
Habitué aux environnements corporate et aux projets data end-to-end.

Après une alternance chez AXA France en tant que Chargé d’Études Statistiques,  
je suis ouvert aux opportunités **CDD / CDI – Data Analyst / BI Analyst / Chargé d’Études**.

📌 Disponible immédiatement – France / Remote

---

## Formations

🎓 Master 2 – Innovation, Marché & Science des Données (Paris-Saclay, Evry) – 2024/2025  
🎓 Master 2 – Expertise Économique (Lille) – 2022/2024  
🎓 Licence 3 – Économétrie (Orléans) – 2022/2023  

---

## Compétences clés

### Business Intelligence & Data Visualisation
- Power BI (avancé) : DAX, KPIs, modélisation étoile/flocon
- Power BI Service : publication, sécurité, actualisation
- Dashboards décisionnels (Finance, RH, CRM, Ventes)
- Data storytelling & bonnes pratiques de visualisation

### Statistiques & Machine Learning
- Régression : Linéaire, Ridge, Lasso, XGBoost
- Classification : Logistic Regression, Random Forest, XGBoost, LightGBM
- Segmentation, scoring, churn prediction
- Évaluation : Accuracy, F1-score, ROC AUC, MAE, RMSE, R²

### 🗄️ Data Engineering & Automatisation
- **SQL** : PostgreSQL, Azure SQL, BigQuery
- **Pipelines** ETL / ELT
- **Python** (pandas, numpy, scikit-learn)
- **Automatisation** : VBA, SAS / WPS
- **Cloud** : Azure, Google Cloud Platform

### 🛠️ Outils
Power BI • Python • R • SAS • SQL • Git/GitHub • Streamlit • VS Code • Databricks • Dataiku

---

#~# 💼 Expérience professionnelle

### **Chargé d’Études Statistiques – AXA France**  
📅 Septembre 2024 – Septembre 2025  
- Automatisation des processus analytiques (SAS/WPS, VBA)
- Optimisation de traitements Excel (réduction significative des délais)
- Conception de dashboards Power BI pour le suivi des aides aux agents généraux
- Appui à la prise de décision pour les équipes métiers

### **Chargé d’Études & Optimisation – AXA France**  
📅 Janvier 2024 – Juin 2024  
- Développement et mise en production de tableaux de bord Power BI
- Analyse des besoins métiers et participation aux ateliers de conception
- Amélioration des processus décisionnels via la data

---

## Projets Data – GitHub

### 📊 Retail Sales ETL & BI (MySQL / Power BI)

Projet end-to-end Data Analyst / BI : de la donnée brute à l’aide à la décision.

- Pipeline ETL en Python avec contrôles de qualité
- Data Warehouse MySQL en schéma étoile
- Modélisation analytique pour Power BI
- Dashboard interactif orienté pilotage métier

🎯 Objectif métier : identifier les leviers de croissance et fiabiliser la prise de décision.
- 👉 **[Retail Sales ETL-BI](https://github.com/mamadou-data/retail-sales-etl-bi)**

---

### 📊 Pipeline ELT & Machine Learning E-commerce (GCP)
*Développement d’un pipeline ELT automatisé sur GCP (GCS, BigQuery, Airflow/Cloud Composer) avec intégration Machine Learning via BigQuery ML pour la prédiction de l’activité client.*
- Pipeline ELT automatisé sur Google Cloud Platform
- Orchestration avec Airflow (Cloud Composer)
- Modélisation BigQuery + BigQuery ML
- Prédiction de l’activité client (ROC AUC ≈ 0.88)
- 👉 **[gcp-ecommerce-elt-ml](https://github.com/mamadou-data/gcp-ecommerce-elt-ml)**

---

### 📊 **Projets Power BI – Dashboards & Cas pratiques**
- Dashboards BI sur des cas Ventes, RH et CRM  
- DAX, modélisation avancée, Power BI Service  
- 👉 **[Power-BI](https://github.com/mamadou-data/Power-BI)** 

---

### 🚕 **NYC Yellow Taxi – ELT Pipeline sur GCP**
Pipeline **ELT cloud-native** de bout en bout sur Google Cloud Platform, depuis l’ingestion de données brutes jusqu’à l’analyse avancée et la préparation au Machine Learning.

**Objectif :** concevoir un pipeline reproductible, automatisé et orienté analytics, basé sur des données réelles à fort volume.

* ### 🔧 Stack technique
- Google Cloud Storage (GCS)
- BigQuery (RAW / TRANSFORMED / VIEWS)
- Cloud Composer (Airflow 2)
- Python
- SQL (BigQuery)
- BigQuery Notebooks

* ### 🏗️ Architecture & étapes clés
- **Ingestion automatisée** des données NYC Yellow Taxi (format Parquet)
- **Stockage cloud** des données brutes dans GCS
- **Chargement BigQuery** idempotent (gestion des doublons par fichier source)
- **Transformation SQL** (nettoyage, filtrage, structuration analytique)
- **Orchestration Airflow** via Cloud Composer
- **Création de vues analytiques** prêtes pour le reporting
- **Analyse & visualisation** via Notebooks Python BigQuery
- **Projet ML-ready** (préparation BigQuery ML)

* ### 📊 Cas d’analyses réalisés
- Évolution de la demande dans le temps (journalière, hebdomadaire, mensuelle)
- Identification des **heures de pointe par borough et zone**
- Analyse spatiale et temporelle des usages taxi
- Préparation de features pour usages prédictifs

* ### 📦 Livrables
- Pipeline Airflow opérationnel
- Tables BigQuery RAW et TRANSFORMED
- Vues analytiques SQL
- Notebooks d’analyse Python
- Documentation complète (README)

👉 **Code source :**  
- 🔗 **[Yellow_Taxi_Trips_Analytics](https://github.com/mamadou-data/Yellow_Taxi_Trips_Analytics)**

---

### 📉 **Scoring & Prédiction du Risque**
Modèles de scoring et segmentation des profils assurés  
Régression & classification supervisée  
- 👉 **[Projet-Scoring](https://github.com/mamadou-data/Projet-Scoring)**
- 👉 **[Risk-Profil-Prediction](https://github.com/mamadou-data/Risk-Profil-Prediction)**

---

### 📡 **Churn Prediction – Télécommunications**
Anticipation des départs clients  
Machine Learning + évaluation complète  
Déploiement via **Streamlit**  
- 👉 **[telco_churn_prediction](https://github.com/mamadou-data/telco_churn_prediction)**  

---

### 🌸 **Machine Learning & Streamlit**
Application web interactive (Iris Dataset)  
Classification et visualisation en temps réel  
- 👉 **[iris-streamlit-app](https://github.com/mamadou-data/iris-streamlit-app)**

---

### 🌐 **Web Scraping & Analyse de données**
Collecte automatisée de données  
Nettoyage, analyse exploratoire et visualisation  
- 👉 **[projet-scraping](https://github.com/mamadou-data/projet-scraping)**

---

## 🎓 Certifications
- 📈 Microsoft Certified : Power BI Data Analyst Associate  
- ☁️ Microsoft Certified : Azure Data Fundamentals
- 🧠 Dataiku Advanced Designer Certificate
- 🧮 Udemy Certified : SAS – Programmation

---

## Ce que je peux apporter
- Structuration et fiabilisation des données
- Création de dashboards décisionnels orientés métier
- Automatisation des reportings
- Appui à la prise de décision stratégique

---

## À propos de ce portfolio
Ce portfolio met en avant :
- une maîtrise complète de la chaîne Data
- une forte orientation business & décision
- des projets concrets et déployés
- un profil opérationnel prêt pour un CDD ou CDI Data Analyst / BI

---

> N’hésitez pas à explorer les projets, dashboards et applications.  
> Je suis ouvert aux opportunités **Data Analyst / BI Analyst / Chargé d’Études Statistiques**.

