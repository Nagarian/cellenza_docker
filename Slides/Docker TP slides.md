class: center, middle

# Docker : mise en pratiques

Récupérer les slides sur <https://github.com/nagarian/cellenza_docker>

---

# Pré-requis

1. Installer docker
2. Ouvrir une ligne de commande

---

# Terminologie

1. docker cli -> interface en ligne de commande
2. `Dockerfile` -> nom du fichier permettant de créer un nouveau container
3. `docker-compose.yml` -> nom du fichier permettant de déclarer l'ensemble des ressources composant notre application

---

# Docker : Commande de bases

- `docker help` : ...
- `docker image ls` : lister les images disponibles en local
- `docker build -t <image>`: builder une image à partir du Dockerfile du dossier courant
- `docker run -it <image>:<version> <command>` : lancer un container avec une commande et s'y attacher
  - `docker run -it nginx:alpine sh`
- `docker ps -a` : lister les containers crée
- `docker stop <nom du container>` : arrêter un container
- `docker rm` : suprrimer un container arrêté

---

# Docker-compose : Commande de bases

Lien utile : <https://docs.docker.com/compose/reference/overview/>

- `docker-compose up -d` : créer et démarrer l'ensemble des services définis dans `docker-compose.yml`
- `docker-compose down` : arrête et détruit l'ensemble des services définis dans `docker-compose.yml`
