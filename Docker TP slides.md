class: center, middle

# Docker : mise en pratiques

Récupérer les slides sur <https://github.com/nagarian/cellenza_docker>

---

# Pré-requis

1. Installer docker
2. Ouvrir une ligne de commande

---

# Docker : Commande de bases

- `docker help` : ...
- `docker image ls` : lister les images disponibles en local
- `docker run -it <image>:<version> <command>` : lancer un container avec une commande et s'y attacher
  - `docker run -it nginx:alpine sh`
- `docker ps -a` : lister les containers crée
- `docker stop <nom du container>` : arrêter un container
- `docker rm` : suprrimer un container arrêté

---

# Docker-compose : Commande de bases

- ``