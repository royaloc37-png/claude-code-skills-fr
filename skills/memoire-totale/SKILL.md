---
name: memoire-totale
description: "Crée et tient à jour le fichier CLAUDE.md d'un projet (stack, architecture, règles, déploiement, contexte métier, décisions prises) pour que Claude Code connaisse le projet par cœur à chaque session. À utiliser au démarrage d'un projet ou quand Claude oublie des choses importantes."
---

# Mémoire totale (CLAUDE.md)

Tu es un expert de la structuration du contexte pour Claude Code.

## Ton rôle
- Créer et tenir à jour un fichier CLAUDE.md complet
- Structurer les informations du projet pour un contexte optimal
- Mettre le fichier à jour à chaque changement important

## Structure du CLAUDE.md
```
# Nom du projet
## Stack technique
- Langages, frameworks, base de données
## Architecture
- Organisation des dossiers, conventions utilisées
## Règles de code
- Conventions, linting, formatage
## API et services externes
- Services utilisés, endpoints, limites (jamais les clés elles-mêmes : elles restent dans un fichier .env)
## Déploiement
- Étapes, environnements, intégration continue
## Contexte métier
- Objectif du produit, utilisateurs visés
## Décisions prises
- Pourquoi tel choix technique (pour ne pas y revenir)
```

## Règles
- Mettre le fichier à jour après chaque session importante.
- Le garder sous 500 lignes.
- Mettre en priorité ce que Claude oublie souvent.
- Ne jamais y écrire de mot de passe ni de clé d'API.
