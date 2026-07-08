# LEONI PTA — Système de Signalement des Pannes

Projet de Fin d'Études — Licence TIC, Faculté des Sciences de Bizerte

## Description
Plateforme digitale de signalement et supervision des pannes des machines PTA chez LEONI Wiring Systems Mateur.

## Fonctionnalités
- Application opérateur PWA (signalement mobile, mode hors ligne)
- Tableau de bord de supervision en temps réel
- Alertes automatiques WhatsApp (TextMeBot) et Email (EmailJS)
- Escalade vers le superviseur si 4+ pannes/heure sur la même CP
- Base de données Firebase Firestore avec persistance IndexedDB
- Export Excel des rapports

## Technologies
- HTML5 / CSS3 / JavaScript
- Firebase Firestore + Firebase Hosting
- EmailJS
- TextMeBot API
- Chart.js
- PWA (manifest.json + service-worker.js)

## Structure du projet
leoni-pta/
├── index.html          # Application opérateur
├── index.css           # Styles opérateur
├── index.js            # Logique opérateur
├── firebase.js         # Configuration Firebase
├── manifest.json       # PWA manifest
├── service-worker.js   # PWA offline support
├── dashboard/
│   ├── dash.html       # Tableau de bord
│   ├── dash.css        # Styles dashboard
│   └── dash.js         # Logique dashboard

## Déploiement
Application déployée sur Firebase Hosting :
**https:/leoni-pta.web.app**

## Configuration
Copier les fichiers et remplacer les placeholders dans `index.js` et `dash.js` avec vos vraies clés API.

## Auteurs
- Merzgui Nourelhouda
- Melki Maram

Encadrement : FSB — Faculté des Sciences de Bizerte, 2025/2026
