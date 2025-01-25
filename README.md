# Base de Données Netflix

Ce projet propose un modèle de base de données relationnelle pour une plateforme de streaming Netflix. Il permet d'organiser et de gérer les informations sur les contenus (films et séries), les utilisateurs, les acteurs, les studios et les langues.

---

## 🗂️ Structure de la Base de Données

### Tables Principales

- **Film** : Informations sur les films disponibles (titre, genre, durée, année de sortie, etc.).  
- **Serie** : Informations sur les séries (titre, genre, description, nombre de saisons, année de lancement, etc.).  
- **Utilisateur** : Gestion des utilisateurs de la plateforme (nom, email, date de naissance, abonnement, etc.).  
- **Acteur** : Données sur les acteurs ayant joué dans des films et séries.  
- **Studio** : Informations sur les studios de production.  
- **Langue** : Détails sur les langues disponibles (audio et sous-titres).  
- **Profil** : Permet à un utilisateur de créer plusieurs profils personnalisés.  

---

## 🔗 Relations Clés

- **Utilisateur ↔ Profil** : Un utilisateur peut avoir plusieurs profils.  
- **Film ↔ Acteur** : Un film peut inclure plusieurs acteurs, et un acteur peut apparaître dans plusieurs films.  
- **Serie ↔ Acteur** : Une série peut inclure plusieurs acteurs, chaque acteur pouvant jouer dans plusieurs séries.  
- **Film/Serie ↔ Langue** : Les contenus peuvent proposer plusieurs options de langues.  

---

## 🔧 Fonctionnalités

- **Gestion des Contenus** : Organisation des films et séries avec leurs métadonnées.  
- **Personnalisation des Profils** : Permet à chaque utilisateur de personnaliser son expérience.  
- **Support Multilingue** : Intégration de langues multiples pour l'audio et les sous-titres.  
- **Scalabilité** : Une structure extensible pour intégrer de nouvelles fonctionnalités à l'avenir.  

---

## 🛠️ Technologies

- **Base de Données Relationnelle** : Modèle conçu pour assurer l'intégrité et la cohérence des données grâce aux relations entre les tables.  
- **Optimisation des Requêtes** : Utilisation d'index pour améliorer les performances.  

---

## 📄 Licence
Peut etre réutilisé.
---

## 🚀 Objectifs Futurs

1. Ajouter des fonctionnalités d’analyse des données d’audience.  
2. Intégrer un système de recommandations basé sur l’intelligence artificielle.  
3. Améliorer la prise en charge des données de visionnage en temps réel.  

---
