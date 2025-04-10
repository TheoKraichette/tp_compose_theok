# Projet Docker Compose : Backend + Frontend

## Description

Ce projet est une application web composée d'un **backend Node.js** et d'un **frontend React**, orchestrée avec Docker Compose. Le backend expose une API qui retourne des citations aléatoires, et le frontend consomme cette API pour afficher la citation.

## Prérequis

- Docker et Docker Compose installés sur votre machine. Docker engine doit être en fonctionnement.

## Lancer le projet

1. Clonez ce dépôt.
2. Assurez-vous d'être dans le répertoire du projet.
3. Assurez-vous que les ports 3000 et 5001 sont disponibles.
4. Exécutez la commande suivante pour démarrer les services :

```bash
   docker-compose up
```
## Questions de réflexion

1. **Quelle différence fais-tu entre un Dockerfile et un docker-compose.yml ?**

   Le `Dockerfile` permet de créer une image Docker en définissant les étapes de construction. Le `docker-compose.yml` orchestre plusieurs conteneurs et services en définissant leur configuration et interaction.

2. **Quels sont les avantages de séparer les services dans une architecture Docker ?**

   Isolation des services, scalabilité, et maintenance simplifiée. Chaque service fonctionne indépendamment, ce qui rend les mises à jour plus simples et l’architecture plus flexible.

3. **En quoi Docker Compose facilite-t-il le travail en équipe et le déploiement ?**

   Il permet de démarrer facilement l'ensemble des services avec une seule commande. Docker Compose assure un environnement cohérent pour tous les membres de l'équipe et simplifie le déploiement.

4. **Pourquoi est-il utile de publier une image sur Docker Hub même pour un projet perso ?**

   Cela rend l'image accessible de partout, facilite le déploiement et la réutilisation, et centralise les différentes versions de ton application.
