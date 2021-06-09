# Création d'un CRUD via NestJS

Le but de ce test est de créer une API NestJS permettant d'obtenir des informations sur des codes barres via l'API OpenFoodFact.

## Liens utiles

Voici quelques liens utiles pour commencer :
- [NestJS](https://nestjs.com/)
- [API OpenFoodFact](https://fr.openfoodfacts.org/data)

## Fonctionnalités

Le choix de la base de donnée, la structure des routes, le format des tests automatiques sont laissés à la discrétion du candidat. 

### Fonctionnalités indispensables

L'API doit avoir les fonctionnalités suivantes :
- permettre l'inscription d'un utilisateur via login / password
- permettre l'authentification d'un utilisateur via login / password
- sur une route authentifiée, permettre la recherche d'un produit par son code barre sur l'API de OpenFoodFacts

### Points bonus

- Permettre la mise à jour de l'utilisateur
- Système de caching des appels à OpenFoodFacts
- Dockerisation 
- Manifest Kubernetes pour déploiement