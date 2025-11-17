# Projet 12 – Détectez des faux billets avec Python

## 🧾 Mission
Vous êtes envoyé(e) en tant que **Senior Data Analyst** en mission auprès de l’**ONCFM** (Organisation nationale de lutte contre le faux-monnayage).  
Objectif : construire une **application de machine learning** capable de prédire si un billet en euro est **vrai ou faux** à partir de ses caractéristiques physiques (longueur, hauteur, marges, diagonales, etc.).

Vous disposez :
- d’un **cahier des charges** ;
- de **1500 observations** déjà scannées (1000 vrais billets, 500 faux).

L’ONCFM et l’agence européenne EMV souhaitent que vous testiez en priorité les algorithmes suivants :
- **K-means**  
- **Régression logistique**  
- **KNN**  
- **Random Forest**  

Vous êtes autonome sur toute la partie technique (préparation, modélisation, évaluation, choix du modèle final, application).

---

## 🎯 Objectifs
- Effectuer le **prétraitement des données** (valeurs manquantes, outliers, variables explicatives).  
- Utiliser une **régression linéaire** pour imputer certaines valeurs manquantes.  
- Entraîner et comparer un **modèle supervisé** (classification) pour prédire la nature du billet.  
- Entraîner un **modèle non supervisé** (K-means) pour explorer la structure des données.  
- Comparer les performances des modèles (précision, rappel, F1, matrice de confusion, etc.).  
- Sélectionner le **modèle final** et justifier ce choix.  
- Mettre en place une **application simple** (dans un notebook) permettant la saisie de caractéristiques et la prédiction associée.  

---

## 🧰 Outils utilisés
- **Python** :  
  - pandas, numpy (prétraitement)  
  - scikit-learn (KMeans, LogisticRegression, KNeighborsClassifier, RandomForestClassifier, métriques, train_test_split)  
  - éventuellement : LinearRegression pour l’imputation des valeurs manquantes  
  - matplotlib, seaborn (visualisation)  
- **Jupyter Notebook** – analyses et application finale  
- **PowerPoint** – support de présentation  

---

## 🧠 Compétences acquises
- Préparation avancée des données (imputation, standardisation, gestion des variables explicatives).  
- Entraînement de **modèles de classification supervisés**.  
- Utilisation d’un **modèle non supervisé** (clustering K-means) pour explorer les données.  
- Mise en place d’une **régression linéaire** pour imputer des valeurs manquantes.  
- Évaluation et comparaison de plusieurs algorithmes de machine learning.  
- Construction d’une **mini-application de prédiction** dans un notebook.  

---

## 💬 Soft skills
- **Rigueur** dans la mise en place du protocole expérimental (train/test, métriques).  
- **Esprit critique** dans le choix du modèle final (ne pas se fier qu’à une seule métrique).  
- **Capacité de synthèse** pour comparer clairement plusieurs algorithmes.  
- **Pédagogie** dans la présentation du fonctionnement de l’application à des non-techniciens.  
- **Autonomie** sur un projet de bout en bout (de la data brute à l’outil utilisable).  
