# Projet CI13 — Marchés exportateurs à fort potentiel

**Étudiant :** Essafini Malak  
**Code Apogée :** 23008749  
**Groupe :** Commerce International (S7)  
**Établissement :** ENCG Settat  
**Enseignant :** A. Larhlimi  
**Année universitaire :** 2026–2027  

---

## 🎯 Sujet et Problématique
**Sujet CI13 :** Classer les pays par croissance future des importations.
**Problématique :** Quels pays présentent aujourd'hui le profil le plus favorable pour devenir des marchés exportateurs à fort potentiel, et peut-on anticiper leur croissance grâce à leurs indicateurs macroéconomiques et logistiques ?

**Tâche :** Classification supervisée (Régression Logistique / Random Forest).
**Objectif :** Obtenir un F1-score > 0.70 sur l'ensemble de test et surpasser la référence naïve.

---

## 📊 Source des données
- **Organisme :** Banque mondiale — World Development Indicators (WDI) & UN Comtrade.
- **URL complète :** [https://databank.worldbank.org/source/world-development-indicators](https://databank.worldbank.org/source/world-development-indicators)
- **Date d'extraction :** 19/11/2026
- **Licence :** CC BY 4.0
- **Période :** 1960–2023, fréquence annuelle.
- **Unité d'observation :** Un pays pour une année donnée.

---

## 📁 Structure du dépôt
- `data/raw/` : Données brutes (ou notice de récupération)
- `docs/` : Fiche du sujet et références
- `notebooks/` : Notebook principal (`projet_CI13.ipynb`)
- `figures/` : Graphiques générés (.png)
- `rapport/` : Export PDF du notebook
- `presentation/` : Diapositives (6 slides)
- `video/` : Vidéo explicative ou lien

---

## ⚙️ Exécution
Pour lancer le projet localement :
```bash
pip install -r requirements.txt
jupyter notebook notebooks/projet_CI13.ipynb
