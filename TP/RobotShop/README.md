# RobotShop

RobotShop est un projet qui a pour but de montrer comment exploiter une faille de type XSS. Cependant ce n'est pas l'objet de sa présence ici aujourd'hui.

Il est constitué de 2 parties distinctes :

- `robotshop` est un site web développé en `PHP`. Il a également besoin d'une base `sqlite3` (en locale sur le même container) pour pouvoir fonctionner.
- `shoxx-bot` est un bot qui va venir crawler a intervalle régulier le site `robotshop`. Il permet de simuler un admin qui irait régulièrement consulté ledit site.

Votre challenge si vous l'accepter et de :

- réécrire le `Dockerfile` du site web. *NB: il faudra installer les dépendances dont il a besoin*
- compléter ce qu'il manque dans le `docker-compose.yml`, les objectifs à atteindre sont :
  - pouvoir accèder au site web sur le port 1234
  - le bot doit être sur le même réseau que le site web. Lui ira requêter le site sur le port 80
