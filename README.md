# Gestionnaire de Projets – React Hooks

## Présentation

Ce projet est une application de gestion de projets/tâches, développée avec React, illustrant l’utilisation des hooks fondamentaux (`useState`, `useEffect`, `useReducer`). Elle permet de créer, modifier, supprimer et trier des projets, gérer des timers et stocker les données localement.

## Fonctionnalités

- Ajouter, modifier, supprimer un projet
- Filtrer les projets par statut (todo, doing, done)
- Trie par deadline
- Recherche par titre ou description
- Timer Pomodoro pour chaque projet
- Persistance dans localStorage
- Statistiques visuelles du nombre de projets par statut

```
L’application sera accessible sur [http://localhost:3000].

## Utilisation

- Pour ajouter un projet : remplir le formulaire et valider
- Pour modifier/supprimer : utiliser les boutons dédiés dans la liste
- Pour lancer un timer, cliquer sur « démarrer »
- Utiliser les filtres, recherche et tri selon besoin

## Structure technique

- **useState** : gestion des formulaires
- **useReducer** : gestion de la liste et du statut des projets
- **useEffect** : persistance localStorage, timer, effets secondaires
- Le reducer centralise la logique métier (ajout, suppression, modification en respectant l’immutabilité)
- Application découpée en composants réutilisables (Form, List, Statistics, etc.)




```
<img width="591" height="655" alt="image" src="https://github.com/user-attachments/assets/11bd6bd3-cd21-4ce1-b0ee-4b9a3e76eac7" />

