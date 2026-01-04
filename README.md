# 🤖 Projet Cobot – Détection d’Anomalies avec PatchCore

## 📌 Présentation du projet

Ce projet vise à **concevoir et simuler un robot collaboratif (Cobot)** intégrant un système de **détection d’anomalies basé sur le modèle PatchCore**.  
L’objectif est d’analyser le comportement du cobot ou l’état visuel de ses composants afin d’identifier automatiquement des situations anormales (défauts, anomalies, comportements inhabituels).

Le projet est implémenté en **Python**, exécuté via **Jupyter Notebook**, et exploite un **modèle PatchCore pré-entraîné** sauvegardé dans le fichier `patchcore_model.pth`.

---

## 🎯 Objectifs du projet

- Comprendre le fonctionnement d’un **robot collaboratif**
- Mettre en place une **détection d’anomalies non supervisée**
- Utiliser **PatchCore** pour l’analyse d’images ou de données visuelles
- Exploiter **PyTorch** pour le chargement et l’inférence du modèle
- Visualiser et analyser les résultats de détection

---

## 🧠 PatchCore – Principe général

**PatchCore** est une méthode de détection d’anomalies basée sur :
- L’extraction de **caractéristiques profondes** via un réseau CNN
- La mémorisation de patches représentatifs de données normales
- Le calcul de distances pour détecter des écarts anormaux

Le fichier **`patchcore_model.pth`** contient le modèle PatchCore déjà entraîné, utilisé directement pour l’inférence.

---

## 🛠️ Technologies utilisées

- **Python 3**
- **Jupyter Notebook**
- **PyTorch**
- **NumPy / SciPy**
- **Matplotlib**
- **OpenCV**
- **Scikit-learn**

---

## 📂 Structure du projet

```text
ProjetCobot/
│
├── ProjetCobot.ipynb        # Notebook principal
├── patchcore_model.pth     # Modèle PatchCore pré-entraîné
├── requirements.txt        # Dépendances Python
└── README.md               # Documentation du projet
````

---

## 🚀 Installation et exécution

### 1️⃣ Cloner le projet

```bash
git clone https://github.com/AchrafMenach/ProjetCobot.git
cd ProjetCobot
```

### 2️⃣ Installer les dépendances

```bash
pip install -r requirements.txt
```

⚠️ Pour une exécution avec GPU (CUDA), installe PyTorch depuis le site officiel.

### 3️⃣ Lancer le notebook

```bash
jupyter notebook
```

Puis ouvrir :

```
ProjetCobot.ipynb
```

---

## ⚙️ Fonctionnalités principales

* Chargement du modèle `patchcore_model.pth`
* Extraction de caractéristiques
* Détection d’anomalies
* Visualisation des scores et heatmaps
* Analyse du comportement du cobot

---

## 📊 Résultats attendus

* Identification claire des anomalies
* Visualisation graphique des zones suspectes
* Évaluation de la performance du modèle
* Amélioration de la sécurité et de la fiabilité du cobot

---

## 🔮 Perspectives d’amélioration

* Entraînement du modèle sur des données spécifiques
* Intégration temps réel avec capteurs ou caméra
* Utilisation de modèles plus avancés (ViT, Transformers)
* Déploiement industriel

---

## 👤 Auteur

* **Nom :** *Achraf Menach*
* **Année universitaire :** 2025 – 2026

---

## 📜 Licence

Projet réalisé dans un **cadre pédagogique et académique**.
Toute utilisation doit mentionner l’auteur et la source du projet.

---

✨ *Projet réalisé avec Python, PyTorch et PatchCore*
