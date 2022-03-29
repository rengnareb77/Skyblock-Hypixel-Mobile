# Cahier des charges

## Table des matières :

1. Présentation du projet

2. Expression des besoins
   
   2.1 Besoins d'utilisation
   
   2.2 Fonctionnalités

3- Contraintes techniques

4. Vocabulaire

## 1 - Présentation du projet

Le serveur minecraft Hypixel offre un mode de jeu skyblock, ce mode de jeu est très complet, il offre une autre dimension au mode skyblock original, on y retrouve de touts **nouveaux équipements,** des **événements**, des "minions", de toutes **nouvelles statistiques**, un système d'enchères etc...

L'objectif est donc d'avoir une application mobile multi-plateforme qui permettrait au joueurs d'avoir des informations relatives à leur partie, on pourrait par exemple choisir de recevoir une notification lorsque certaines événements sont sur le point de se produire. Cette application pourra être possible grâce à [l'API de Hypixel](https://api.hypixel.net/).

## 2 - Expression des besoins

### 2.1 - Besoins d'utilisation

L'application devra fonctionner sur téléphone portable de la même manière peu importe le système d'exploitation (IOS,Android). La langue devra être principalement l'anglais car la plupart des joueurs d'Hypixel sont anglophone.

### 2.2 - Fonctionnalités

- [ ]  Recevoir une notification lorsque l'inventaire d'un minion est plein ainsi qu'une prévision en temps réel du temps restant.

- [ ]  Recevoir une notification lorsque l'événement **Jacob's Farming Contest** commence et propose comme ressources à collecter la/les ressources que l'on a choisi au préalable.

## 3 - Contraintes techniques

- Limite de requête de l'API :
  
  L'API d'Hypixel permet d'effectuer 120 requêtes par minutes ce qui peut être limitant dans le cas où plusieurs personnes utilises l'application simultanément.

- Certaines informations ne sont pas accessible via l'API d'Hypixel:
  
  Certaines informations comme l'événement Jacob's Farming Contest n'est pas accessible via l'API d'Hypixel

## 4 - Vocabulaire

Vocabulaire général :

- **Minecraft** : Jeu vidéo de type "sandbox".

- **Hypixel** : Serveur minecraft de la société du même nom. 

- **Skyblock** : Mode de jeu présent sur le serveur Hypixel.

Vocabulaire relatif au mode de jeu Skyblock:

- **Minions** :  Minions: Ce sont des "sbires" qui collectent des ressources automatiquement, chaque minon collecte les ressources associées à son nom. Chaque minions possède une taille d'inventaire ainsi qu'une vitesse, il est cependant possible d'améliorer via différents items ces statistiques. Plus d'informations sur le [wiki](https://hypixel-skyblock.fandom.com/wiki/Minions).

- **Jacob's Farming Contest**: Événement qui consiste à collecter le maximum d'une ressources pendant 20 min. Un classement est établie à la fin des 20 min (GOLD, SILVER, BRONZE) et des récompenses sont attribuées. Plus d'information sur le [wiki](https://hypixel-skyblock.fandom.com/wiki/Jacob%27s_Farming_Contest).
