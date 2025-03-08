# Le-cote-obscure-de-la-force# Le Côté Obscur de la Force - Application Symfony

Bienvenue dans **Le Côté Obscur de la Force**, une application Symfony permettant de découvrir les personnages de l'univers Star Wars en utilisant l'API **SWAPI** (*Star Wars API*). Ce projet est une opportunité pour explorer **HttpClient** et apprendre à exploiter la puissance des **services Symfony** pour structurer efficacement son code.

## 🚀 Objectifs du Projet

- **Explorer l'API SWAPI** : Récupérer et afficher les informations sur les personnages, vaisseaux, et planètes.
- **Utiliser HttpClient** : Comprendre comment effectuer des requêtes HTTP en Symfony.
- **Exploiter les services Symfony** : Apprendre à organiser son code de manière modulaire et réutilisable.
- **Mettre en place une architecture claire** : Respecter les bonnes pratiques du framework Symfony.

## 🛠️ Technologies Utilisées

- **Symfony 7+** (Framework PHP)
- **Pico CSS** (Framework CSS minimaliste et moderne)
- **HttpClient** (Composant Symfony pour les requêtes HTTP)
- **Twig** (Moteur de templates)
- **Doctrine (optionnel)** (ORM pour la gestion des entités en base de données)
- **API SWAPI** ([https://swapi.dev/](https://swapi.dev/))

## 📦 Installation du projet

1. **Cloner le projet**
   ```bash
   git clone https://github.com/Ophelie22/Le-cote-obscure-de-la-force.git
   cd Le-cote-obscure-de-la-force
   ```

2. **Installer les dépendances avec Composer**
   ```bash
   composer install
   ```

3. **Configurer les variables d'environnement**
   ```bash
   cp .env .env.local
   ```
   Modifier le fichier `.env.local` si nécessaire.

4. **Démarrer le serveur Symfony**
   ```bash
   symfony serve
   ```
   L'application sera accessible sur [http://127.0.0.1:8000](http://127.0.0.1:8000).

## 🔗 Utilisation de l'API SWAPI

L'API SWAPI permet de récupérer des données sur l'univers Star Wars via des endpoints REST.

doc:
swapi.dev/documentation

api:
https://swapi.py4e.com/api/

https://swapi.dev/api/people


🛠 Auteur : Ophélie📜 Licence : MIT