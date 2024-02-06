# Laboratoire 1 - Antenne motorisée

Dans les situations d’urgence, les premiers répondants ont besoin d’un canal de communication fiable entre eux et avec les autres services (hôpitaux, centre météo…). Pour cela, ils peuvent utiliser une connexion satellitaire.  

Afin de garder un lien de communication, il faut continuellement orienter l’antenne dans la direction d’un satellite accessible. 

On vous demande de réaliser un prototype démontrant qu’on peut asservir la direction de l’antenne malgré des changements continus de direction du véhicule. Il faut également être capable de changer de satellite cible si le signal devient trop faible. 

La consigne d’orientation sera donnée sous la forme d’un angle par rapport au nord magnétique terrestre (entre 0° et 360°). 

Vous utilisez un servo-moteur à rotation continue, commandé en vitesse, ainsi qu’un magnétomètre pour connaitre son orientation. 

![vehiculeAntenne](https://github.com/max848484/243-620-H24_Labo1/assets/156249332/e0dba8f5-1d8a-4347-b549-5ab6d6e73dd1)

## 1. Moteur en boucle ouverte 

Réalisez un montage préliminaire simple et démontrez que vous pouvez : 

- Contrôler le moteur à vitesse nulle 
- Contrôler le moteur CW à différent niveau de vitesse
- Contrôler le moteur CCW à différent niveau de vitesse
- Contrôler le moteur CW à sa vitesse maximale
- Contrôler le moteur CCW à sa vitesse maximale

La commande peut être ajustée grâce à un potentiomètre ou des commandes au terminal. La commande peut être ajustée grâce à un potentiomètre ou des commandes au terminal ou une séquence prédéfinie. Affichez la valeur de la commande sur un terminal. La vitesse du terminal devra être réglée à 115200 bauds. 

Démontez ce comportement à votre enseignant 

## 2- Lecture de l’orientation 

Réaliser un montage préliminaire simple et démontrer que vous pouvez : 

- Lire l’orientation du support à la sortie du moteur entre 0 et 255
- Lire l’orientation du support à la sortie du moteur entre 0 et 360 (à 0.1° près) 

Afficher la valeur de la mesure sur un terminal. 

Démonter ce comportement à votre enseignant 

## 3- Schéma boucle fermée 

Réaliser un schéma de votre système d’asservissement du moteur en position avec tous les détails de la chaine de commande et de lecture. 

## 4- Asservissement de la position 

Réaliser un système qui asservi la position du moteur à l’aide un régulateur Propotionnel. 
