# Docker Getting started

## Présentation

- Le doc pptx concerne la partie théorique.
- Pour la partie mise en pratique, le fichier [Docker TP](./Slides/Docker_TP.html) contient les bases. Pour le faire fonctionner il faut run un server local. Par exemple : `npx http-server` et aller sur <http://localhost:8080/Docker_TP.html> ou `docker-compose up`

## Travaux pratiques

Pour cette partie, plusieurs options sont à votre disposition :

1. Pour ceux qui ont besoin de petite roulette : <https://github.com/docker/labs/tree/master/beginner/>
2. Pour les casse-cou je vous propose un premier TP où vous devez mettre en place une archi composé de 2 services -> [RobotShop](./TP/RobotShop/README.md)
3. Pour ceux qui préférent les défis corsés, le second TP devrait être à votre convenance ! -> [CFlix](./TP/CFlix/README.md)

Pour les points **2.** et **3.**, vous serez en autonomie et le but commun des deux TP est de vous faire pratiquer l'écriture de `Dockerfile` et de `docker-compose.yml`

Documentation de référence sur la syntaxe du Dockerfile : <https://docs.docker.com/engine/reference/builder/>

Documentation de référence sur la syntaxe du docker-compose.yml : <https://docs.docker.com/compose/compose-file/>

## Pour aller plus loin

Un recueil de TP et de samples :
<https://docs.docker.com/samples/>
