# 🏦 Credit Scoring — Modélisation du risque de crédit

## 📘 Description du projet

Ce projet vise à **évaluer le risque de crédit** d'un client à partir de ses caractéristiques socio-économiques et financières.

L'objectif est de construire un modèle de **machine learning** capable de prédire si un individu est un bon ou mauvais payeur.

Tout le travail est réalisé dans le notebook **`credit_scoring.ipynb`**, qui illustre les étapes essentielles d'un pipeline de data science :

- Préparation et exploration des données
- Nettoyage et transformation
- Entraînement de modèles prédictifs
- Évaluation de la performance
- Interprétation des résultats

---

## 📂 Contenu du dépôt

| Fichier / dossier | Description |
|-------------------|--------------|
| `credit_scoring.ipynb` | Notebook principal contenant tout le code du projet |
| `README.md` | Ce fichier de documentation |
| `credit_scoring.csv` | Dossier pour stocker les jeux de données locaux |
| `requirements.txt` | Liste des dépendances Python |

---

## ⚙️ Environnement et dépendances

Le projet nécessite **Python 3.8+** et les bibliothèques suivantes :
```bash
numpy
pandas
matplotlib
seaborn
scikit-learn
jupyter
```

---

## 🔧 Configuration de l'environnement virtuel

### Sous Windows :
```bash
python -m venv venv
venv\Scripts\activate
python -m pip install --upgrade pip
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```

### Sous macOS / Linux :
```bash
python3 -m venv venv
source venv/bin/activate
python3 -m pip install --upgrade pip
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```

---

## 🚀 Exécution du projet

1. Activer votre environnement virtuel
2. Lancer Jupyter Notebook :
```bash
   jupyter notebook
```
3. Ouvrir le fichier : `credit_scoring.ipynb`

---
