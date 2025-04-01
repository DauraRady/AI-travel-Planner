# AI-travel-Planner
# 🌍 AI Travel Planner Itinéraire – Daura Rady

## 🧭 Objectif

Une application Python interactive qui génère :
- 🛣️ Un **itinéraire de voyage personnalisé**
- ☀️ Un **rapport météo complet** à la destination
- Le tout enrichi avec des conseils, des emojis, et un rendu stylisé en Markdown pour une expérience utilisateur agréable.

---

## ⚙️ Fonctionnalités

- 📍 Saisie de la ville de départ, destination, et durée du voyage
- 🤖 Génération d’un itinéraire détaillé via l’API IA de SheCodes
- 🌦️ Rapport météo intelligent avec recommandations personnalisées
- 💬 Affichage élégant en terminal grâce à la bibliothèque `rich`
- 👤 Signature de l’autrice à la fin du programme

---

## 🛠️ Stack technique

- Python 3.x
- `requests` – pour interroger l’API
- `rich` – pour afficher du Markdown coloré dans le terminal
- API : [SheCodes AI](https://www.shecodes.io/weather)

---

## 🚀 Lancer l'application

### 1. Installer les dépendances :

```bash
pip install requests rich

2. Lancer le script :
bash
Copier
Modifier
python ai_travel_planner.py
Remplace ai_travel_planner.py par le nom exact de ton fichier si différent.

📌 Exemple d’usage
bash
Copier
Modifier
Bienvenue sur mon AI Travel Planner Itinéraire !
Préparez-vous à explorer vos prochaines aventures avec style et précision. 🚀
Entrez le lieu de départ : paris
Entrez la destination : rome
Entrez la durée du voyage (en jours) : 5
Calcul de l'itinéraire ! 🚀
(S’ensuit l’itinéraire généré + météo + recommandations utiles)


✅ Améliorations futures
 Traduction des jours de la semaine en français 🇫🇷

 Détection automatique de la localisation d’origine via IP 📍

 Interface web simple (Flask, Streamlit, etc.) 💻

 Ajout d’une carte interactive 🗺️

 Gestion des erreurs réseau ou d’API 🔒
