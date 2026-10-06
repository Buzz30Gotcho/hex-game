# Jeu de Hex — multijoueur en ligne

Implémentation web du **jeu de Hex** jouable à **2 à 4 joueurs** en réseau, avec
plateau configurable et **messagerie temps réel** entre les joueurs d'une partie.

> Projet académique réalisé en **binôme** (Frédéric Sar & Hamza El Hilali).

## ✨ Fonctionnalités

- Création d'une partie avec **damier paramétrable** (longueur / largeur).
- Jusqu'à **4 joueurs** connectés simultanément via un serveur Node.js.
- **Salle d'attente** et lobby : les joueurs rejoignent la partie depuis leur navigateur.
- **Messagerie** intégrée pour communiquer en cours de partie.
- Gestion des déconnexions : la partie continue si un joueur quitte.

## 🛠️ Stack technique

- **Serveur** : Node.js
- **Client** : HTML, CSS, JavaScript (vanilla)
- **Communication** : échanges client/serveur en temps réel

## 🚀 Lancement

```bash
cd JavaScript
node serveurHex1_3.js
```

Puis, dans le navigateur :

1. Ouvrir `http://localhost:8088/`
2. Saisir son nom, le nombre de joueurs (2 à 4) et la configuration du damier.
3. Chaque joueur supplémentaire ouvre `http://localhost:8088/` dans un nouvel onglet
   et rejoint la partie.
4. La partie démarre une fois qu'au moins 2 joueurs sont présents.

## 👤 Rôle

Développement du serveur de jeu et de la logique multijoueur (gestion des parties,
des joueurs et de la messagerie temps réel).
