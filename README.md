# Projet de Test de Communication I2C

Ce projet vise à tester la communication I2C sur une carte électronique spécifique. L'I2C (Inter-Integrated Circuit) est un protocole de communication série qui permet à plusieurs périphériques de communiquer entre eux en utilisant uniquement deux fils de données.

## Objectif

L'objectif principal de ce projet est de vérifier la fonctionnalité de la communication I2C sur la carte électronique en question. Cela implique :

- Établir une connexion I2C entre la carte électronique STM32 et un dispositif maître
- Envoyer des données de test à partir du dispositif maître et vérifier si la carte électronique les reçoit correctement.
- Recevoir des données de la carte électronique et s'assurer qu'elles sont interprétées correctement par le dispositif maître.

## Structure du Projet

Le projet est organisé comme suit :

- `README.md`: Ce fichier que vous lisez actuellement, fournissant des informations sur le projet.
- `core/`: Répertoire contenant le code source pour tester la communication I2C.
- `inc/`: Répertoire contenant la documentation supplémentaire, le cas échéant.
