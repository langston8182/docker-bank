# Version

- **1.0.0-SNAPSHOT** : initialisation du projet

# Objectif

Projet docker pour lancer les differents services pour l'application bank.\
Les services conteneurises sont :
- service-utilisateur (https://github.com/langston8182/service-utilisateur)
- authorization : (https://github.com/langston8182/bank-oauth2-authorization-server)
- mariadb

# Docker

Utiliser docker-compose pour lancer les services.
`docker-compose up`

Pour arreter les containers
`docker-compose down`

# bank-ui

Lien github : https://github.com/langston8182/bank-ui

Pour lancer la ui, récupérer l'image sur docker hub\
`docker run -d -p 3000:3000 --name bank-ui langston8182/bank-ui:1.0.0-SNAPSHOT`

# Contributeur

Cyril Marchive (cyril.marchive@gmail.com)
