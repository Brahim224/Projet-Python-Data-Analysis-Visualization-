# 📊 Analyse et Visualisation de Données CSV

Ce projet implémente une application Python structurée en Programmation Orientée Objet (POO) pour nettoyer, analyser et visualiser les données contenues dans un fichier CSV.

## 🚀 Fonctionnalités
- **Chargement & Nettoyage** : Importation automatique du fichier CSV avec `pandas` et gestion des valeurs manquantes.
- **Analyse Statistique** : Calculs mathématiques et statistiques descriptives via `numpy` et `pandas`.
- **Visualisation** : Génération de graphiques (corrélations, tendances, distributions) avec `matplotlib`.
- **Structure POO** : Code organisé en classes (ex: EducationAnalysis) pour une meilleure maintenance.

## 🛠️ Prérequis et Installation

1. **Cloner le projet** :
   ```bash
   git clone <URL_DE_VOTRE_DEPOT_GITHUB>
   ```

2. **Installer les dépendances** :
   Assurez-vous d'avoir Python installé, puis lancez la commande suivante pour installer les bibliothèques requises :
   ```bash
   pip install numpy pandas matplotlib
   ```

## 📂 Structure des Fichiers
- `analyzer.py` : Contient la logique des classes POO (analyse et graphiques), Point d'entrée de l'application (instancie et lance les classes).
- `projet_python.csv` : Le jeu de données utilisé pour l'analyse.
- `Rapport.pdf` : Le rapport explicatif de la demarche mise en place et resultat de visuelles .
- `.gitignore` : Spécifie les fichiers à ignorer par Git (caches Python, etc.).

## 💻 Utilisation

Placez votre fichier CSV dans le dossier du projet, puis exécutez le script principal depuis votre terminal :
```bash
projet_python.py
```

## 📊 Résultats
<img width="658" height="449" alt="boxplot avec type d&#39;ecole" src="https://github.com/user-attachments/assets/573edcea-2b40-42dd-a294-26dd93e98dd5" />
<img width="659" height="428" alt="histogramme des score" src="https://github.com/user-attachments/assets/ab35a689-04b2-406e-81bb-9a3df1c8fce1" />
