# 📦 Gest'Stock HACCP

> **La traçabilité alimentaire, libre et sans abonnement.**
> Une solution de gestion de stock et de traçabilité HACCP conçue pour les restaurateurs indépendants, les associations et les petites structures.

![License](https://img.shields.io/badge/license-MIT-green)
![Platform](https://img.shields.io/badge/platform-Web%20%7C%20Mobile%20%7C%20Tablet-blue)
![Data](https://img.shields.io/badge/data-Local%20Storage-orange)

## 📋 À propos

**Gest'Stock HACCP** est une alternative aux logiciels de gestion de cuisine coûteux et complexes. C'est une application web autonome ("Single File App") qui permet de gérer vos stocks, vos entrées/sorties et votre traçabilité sanitaire sans dépendre d'une connexion internet permanente ni d'un serveur tiers.

**Le problème :** Les logiciels HACCP actuels sont souvent des "usines à gaz" sur abonnement qui stockent vos données on-ne-sait-où.
**La solution :** Un simple fichier HTML qui tourne sur votre tablette en cuisine, où vos données restent chez vous.

## ✨ Fonctionnalités Clés

### 🛡️ Traçabilité & HACCP
*   **Journal des Mouvements** : Enregistrement précis des Entrées (Livraisons) et Sorties (Consommation/Pertes).
*   **Suivi Sanitaire** : Champs dédiés pour les numéros de lot, les températures à réception et les dates de péremption (DLC/DDM).
*   **Gestion des Allergènes** : Identification claire des allergènes pour chaque produit.

### 📦 Gestion de Stock
*   **État en Temps Réel** : Vue immédiate des quantités disponibles.
*   **Alertes Automatiques** : Notification visuelle dès qu'un produit atteint son seuil de stock critique.
*   **Base Produits** : Gestion des fournisseurs, catégories (Viandes, Épicerie, etc.) et unités.

### 🖨️ Rapports & Exports
*   **Registre des Mouvements** : Export propre pour les contrôles d'hygiène.
*   **Inventaire Valorisable** : Génération de la liste de stock pour la comptabilité.
*   **Annuaire Fournisseurs** : Centralisation des contacts.

## 🚀 Installation & Utilisation

### Option A : Utilisation en ligne (Recommandé pour tester)
Accédez simplement à la version hébergée (via GitHub Pages) :
> [Lien vers votre démo ici]

### Option B : Installation "App" (Tablette Cuisine)
Cette application est une PWA (Progressive Web App) qui fonctionne hors-ligne.
1. Ouvrez l'application sur votre tablette (iPad ou Android).
2. Touchez le bouton **Partager** (iOS) ou le menu **Options** (Android).
3. Sélectionnez **"Sur l'écran d'accueil"**.
4. L'application se lance désormais en plein écran, comme une app native, sans barre d'adresse.

### Option C : Hébergement Local
Téléchargez le fichier `geststockapp.html`. Vous pouvez l'ouvrir directement dans n'importe quel navigateur. Aucune installation de serveur (Node, PHP, Python) n'est nécessaire.

## 📂 Structure du Projet

```text
/
├── index.html           # Landing page (Présentation du projet)
├── geststockapp.html    # L'APPLICATION PROD (Le fichier principal)
├── demogeststock.html   # Version de Démonstration (Données fictives + Reset)
├── helpgeststock.html   # Manuel utilisateur / Aide
└── README.md            # Documentation
```

## 🛠️ Stack Technique

Conçu pour la pérennité et la simplicité de maintenance.

*   **Frontend** : HTML5, CSS3 (Variables natives), Vanilla JavaScript (ES6+).
*   **Stockage** : `localStorage` du navigateur (Persistance des données sur l'appareil).
*   **Dépendances** : Aucune. Pas de framework lourd, pas de build process.

## ⚠️ Avertissement Légal

**Gest'Stock HACCP** est un outil d'aide à la gestion. Bien qu'il soit conçu pour faciliter le respect des normes HACCP (Hazard Analysis Critical Control Point), l'utilisation de ce logiciel ne dispense pas l'utilisateur de ses obligations légales en matière d'hygiène, de contrôle des températures et de respect de la chaîne du froid. L'auteur décline toute responsabilité en cas de contrôle sanitaire non conforme.

## 🤝 Contribuer

Ce projet est open-source. Les restaurateurs et développeurs sont invités à l'améliorer.

1. Forkez le projet.
2. Proposez vos améliorations (ex: ajout d'un module de relevé de température frigo, export PDF, etc.).
3. Créez une Pull Request.

## 📄 Licence

Distribué sous la licence MIT. Vous êtes libre de l'utiliser, le modifier et le distribuer, même pour une utilisation commerciale dans votre restaurant.

---
*Développé pour rendre l'indépendance aux artisans du goût.*
