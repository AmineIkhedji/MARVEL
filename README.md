# Gestion des dons d'une association caritative

Mini-projet du module **DevOps**, Université de Béjaïa, Département d'Informatique
Année universitaire 2026 – 2027

> **Statut : projet en cours de démarrage.** Ce README est temporaire et sera complété au fil de l'avancement.

## Équipe : Avengers

| Membre |
|--------|
| Belaloui Samy Abdelmadjid |
| Boucekkine Anais Saleha |
| Ikhedji Amine |
| Khier Nassim |
| Lachi Kouceila |

## Description du projet

Application destinée à aider une association caritative à collecter des dons (argent et dons en nature), à les répartir entre les bénéficiaires et à rendre des comptes de façon transparente aux donateurs.

### Fonctionnalités prévues

- Vitrine publique : présentation de l'association, campagnes en cours, actualités
- Dons financiers (paiement simulé) et dons en nature
- Reçus de don numérotés en PDF
- Gestion des bénéficiaires et des distributions
- Bénévoles et missions
- Suivi budgétaire et rapports de transparence
- Tableau de bord et statistiques

## Démarche DevOps

| Axe | Statut |
|-----|--------|
| Dépôt Git, branches et pull requests | À faire |
| Intégration continue (lint, tests, build) | À faire |
| Conteneurisation (Docker Compose) | À faire |
| Livraison continue et retour arrière | À faire |
| Configuration et secrets (variables d'environnement) | À faire |
| Observabilité (logs, healthcheck, indicateur) | À faire |
| Sécurité (authentification, rôles, sauvegardes) | À faire |
| Documentation (API, manuel utilisateur) | À faire |

## Technologies

À définir.

## Installation et lancement

À compléter (objectif : tout lancer avec une seule commande via Docker Compose).

## Architecture

À compléter. Le site public (vitrine) et le back-office seront séparés.

## Organisation du travail

- Branche principale : `main` (protégée, modifications via pull request relue par un autre membre)
- Branches de travail : `feature/nom-de-la-fonctionnalite`
- Suivi des tâches : onglet **Issues** / **Projects** du dépôt

## Règles importantes

- Aucun mot de passe, clé ou secret dans le dépôt : utiliser un fichier `.env` (ignoré par Git) et fournir un `.env.example` avec des valeurs factices
- Aucune donnée bancaire réelle : paiement simulé uniquement