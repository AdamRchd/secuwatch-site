# 💻 SecuWatch Frontend

**Interface utilisateur pour la plateforme d'audit SecuWatch.**

Ce projet est le client web (SPA) permettant d'interagir avec l'API SecuWatch. Il offre un tableau de bord intuitif pour lancer des scans, visualiser les risques en temps réel et gérer son historique d'audit.

🔗 **Backend API :** [https://github.com/AdamRchd/secuwatch-api]

## ✨ Fonctionnalités

* **Dashboard Interactif :** Visualisation claire des scores de sécurité (Code couleur Vert/Jaune/Rouge).
* **Espace Membre :** Formulaires de Connexion et d'Inscription connectés à l'API (JWT).
* **Rapports PDF :** Bouton de téléchargement direct des rapports d'audit.
* **UX/UI :** Interface "Dark Mode" responsive et moderne.
* **Gestion d'Historique :** Tableau de bord personnel des derniers scans effectués.

## 🛠️ Stack Technique

* **HTML5 / CSS3 :** Design responsive sans framework lourd.
* **JavaScript (ES6+) :** Gestion asynchrone (`async/await`) des appels API.
* **Sécurité Client :** Stockage sécurisé du Token d'accès (LocalStorage) et gestion des états de connexion.

## 🚀 Déploiement

Le projet est statique et peut être hébergé sur n'importe quel serveur web (Netlify, Vercel, Render Static).

### Configuration
L'URL de l'API est définie dans `index.html` :
```javascript
const API_URL = "[https://secuwatch-api.onrender.com](https://secuwatch-api.onrender.com)";
