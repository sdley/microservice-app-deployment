# microservice-app-deployment

## 1st part 
Dans cette activité, nous allons déployer une application full-stack dans docker :
- déploiement de la BD
- déploiement du backend
- déploiement du frontend
- Exécution de l'application déployée

## 2nd part

Il faut déployer les images crées dans docker hub
Puis utiliser docker-compose afin de lancer les images pour exécuter votre application
A faire après le lab d'introduction à docker compose
JE joins le fichier compose.yml



1. Placez votre fichier docker-compose.yml à la racine de votre projet.
2. Organisez votre projet avec la structure suivante :

![Project structure](image.png)

3. Construisez et démarrez les conteneurs avec :
docker compose up --build 