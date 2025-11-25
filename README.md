# file-rouge 
📊 Personal Finance Tracker — Projet Fil Rouge 2025/2026

Application web complète de suivi de finances personnelles, conçue en Laravel 10 (backend) et React 18 (frontend).
Elle permet aux utilisateurs de suivre leurs dépenses, revenus, comptes, budgets, ainsi que leurs objectifs d’épargne, à travers un tableau de bord interactif.

Ce projet s’inscrit dans le cadre du Projet Fil Rouge Full-Stack et démontre les compétences en développement, architecture, sécurité, documentation, testing et déploiement.

🔰 1. Présentation du projet

Le Personal Finance Tracker est une application web qui aide les utilisateurs à :

Suivre toutes leurs transactions (revenus / dépenses)

Organiser leur argent par catégories

Gérer plusieurs comptes (bank / cash / carte)

Planifier et suivre leurs objectifs d’épargne

Créer des budgets mensuels avec alertes

Visualiser leurs données financières sous forme de graphiques

Exporter leurs transactions au format CSV

L'objectif principal est de fournir un outil simple, clair et visuel pour encourager une meilleure gestion financière personnelle.

📄 2. Cahier des charges

Le cahier des charges décrit en détail :

le besoin métier,

les objectifs fonctionnels,

les contraintes techniques,

les cas d’utilisation,

la modélisation des données,

l’architecture générale de l’application.

📎 Lien vers le cahier des charges

https://docs.google.com/document/d/1uqyGqlgPDdZMnfj_ESsLeqLAxVemdMUYK3FzY_IjPgU/edit?usp=sharing

📝 Présentation du cahier des charges

Ce document sert de référence officielle pour tout le projet.
Il explique précisément :

pourquoi l’application est nécessaire,

ce qu’elle doit accomplir,

comment elle doit être construite,

et quelles technologies doivent être utilisées.

Il garantit une cohérence globale entre l’analyse, le développement, le testing et le déploiement.

🗂️ 3. Planification & Organisation (Jira)

La gestion du projet suit une méthodologie Scrum, organisée autour de plusieurs niveaux :

🔹 Épics

Authentification & utilisateurs

Comptes financiers

Transactions

Budgets

Objectifs d’épargne

Dashboard & reporting

Déploiement & documentation

🔹 User Stories

Chaque fonctionnalité est écrite d’un point de vue utilisateur :

"En tant qu’utilisateur, je veux ajouter une dépense pour suivre mes sorties d’argent."

🔹 Tâches techniques

Découpage en :

API (Laravel)

UI (React)

Base de données

Tests

Sécurité

Maquettage Figma

CI/CD

🔹 Sprints

Le projet est divisé en 5 sprints, chacun représentant une étape fonctionnelle.

📎 Lien vers le Jira board

https://wijdanesalik06.atlassian.net/jira/for-you

📝 Présentation de la planification Jira

La planification permet :

d’organiser les tâches,

de suivre l’avancement,

de prioriser les fonctionnalités,

et d’assurer un développement progressif.

Chaque sprint livre une version fonctionnelle de l’application.

🧩 4. Fonctionnalités clés
✔️ Authentification

Inscription / Connexion

Sécurité via Laravel Breeze + Sanctum

Rôles & permissions (Laratrust)

✔️ Gestion des comptes

Comptes multiples (cash, banque, carte)

Soldes en temps réel

✔️ Transactions

Ajouter / modifier / supprimer

Revenus & dépenses

Catégorisation

Filtres avancés

Import / Export CSV

✔️ Budgets

Définir un plafond mensuel

Suivi avec alertes (≥ 80%)

✔️ Objectifs d’épargne

Création d’objectifs

Progression visuelle

Contributions manuelles

✔️ Dashboard

Solde total

Graphiques revenus/dépenses

Dernières transactions

Alertes & notifications

🛠️ 5. Technologies
Backend

Laravel 10

Eloquent ORM

Laravel Breeze

Sanctum

Laratrust

MySQL

Frontend

React 18

Vite

TailwindCSS

Redux Toolkit

Axios

Outils & DevOps

Docker

GitHub Actions

Swagger/Postman

Figma

⚙️ 6. Installation
Backend (Laravel)
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate --seed
php artisan serve

Frontend (React)
cd frontend
npm install
npm run dev

🧪 7. Tests
Backend
php artisan test

Frontend
npm run test

🚀 8. Déploiement

Docker (backend + frontend + DB)

CI/CD : GitHub Actions

Hébergement : Render / Railway

🤝 Contribuer
git checkout -b feature/ma-feature
git commit -m "feat: ajout d'une nouvelle fonctionnalité"
git push origin feature/ma-feature

📄 Licence

Usage libre dans un cadre pédagogique.

Si tu veux, je peux aussi te créer :

✅ un README avec badges GitHub
✅ un README avec images / schémas UML / architecture
✅ un README plus minimaliste
✅ un README sans technique (version scolaire)

Dis-moi ce que tu préfères !
