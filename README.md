# 🔌 Projet Cobot – Détection d’Anomalies des Wall Plugs avec PatchCore

## 📌 Présentation du projet

Ce projet a pour objectif la **détection automatique d’anomalies sur des wall plugs (prises murales)** à l’aide d’un **système de vision artificielle basé sur le modèle PatchCore**.  
Il s’inscrit dans un contexte **industriel et de contrôle qualité**, où l’identification rapide de défauts visuels est essentielle pour garantir la sécurité et la fiabilité des produits.

Le système utilise un **modèle PatchCore pré-entraîné** (`patchcore_model.pth`) afin de détecter des défauts tels que :
- fissures,
- déformations,
- anomalies de surface,
- défauts d’assemblage,
- variations visuelles anormales.

Le projet est implémenté en **Python**, exécuté via **Jupyter Notebook**, et repose sur **PyTorch** pour l’inférence du modèle.

---

## 🎯 Objectifs du projet

- Mettre en place une **détection d’anomalies non supervisée**
- Identifier automatiquement les **défauts visuels des wall plugs**
- Exploiter le modèle **PatchCore** pour l’analyse d’images industrielles
- Visualiser les anomalies détectées (scores et heatmaps)
- Fournir une base exploitable pour un **système de contrôle qualité automatisé**

---

## 🧠 PatchCore – Principe de fonctionnement

**PatchCore** est une méthode de détection d’anomalies basée sur :
- l’extraction de **caractéristiques profondes** via un réseau convolutionnel,
- la mémorisation des **patches représentatifs des images normales**,
- le calcul de distances pour détecter des **écarts anormaux**.

Le fichier **`patchcore_model.pth`** correspond à un modèle entraîné uniquement sur des **wall plugs normaux**, ce qui permet de détecter toute anomalie sans apprentissage supervisé.

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
git clone https://github.com/AchrafMenach/Projet-Cobot-D-tection-d-Anomalies-avec-PatchCore
cd ProjetCobot
```

### 2️⃣ Installer les dépendances

```bash
pip install -r requirements.txt
```

⚠️ Pour une exécution avec GPU (CUDA), installer PyTorch depuis le site officiel.

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
* Analyse d’images de wall plugs
* Calcul des scores d’anomalie
* Génération de heatmaps de défauts
* Visualisation et interprétation des résultats

---

## 📊 Résultats attendus

* Détection fiable des anomalies visuelles
* Localisation précise des zones défectueuses
* Réduction des erreurs de contrôle manuel
* Amélioration du processus de contrôle qualité

---

## 🔮 Perspectives d’amélioration

* Entraînement du modèle sur un dataset plus large
* Intégration d’une caméra industrielle en temps réel
* Couplage avec un cobot pour le tri automatique
* Intégration avec ROS / systèmes industriels
* Déploiement en environnement de production

---

## 👤 Auteur

* **Nom :** *Achraf Menach*
* **Année universitaire :** 2025 – 2026

---

## 📜 Licence

Ce projet est réalisé dans un **cadre pédagogique et académique**.
Toute réutilisation doit mentionner l’auteur et le contexte du projet.

---

✨ *Projet de détection d’anomalies industrielles des wall plugs avec PatchCore et PyTorch*


