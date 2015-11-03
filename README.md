------------------------------
MINI-JEU DE COMBAT version 1.0
------------------------------

Ce jeu est construit grace au tutoriel POO en PHP de OpenClassrooms.


Comment jouer ?
---------------

Chaque visiteur pourra créer un personnage (pas de mot de passe requis pour faire simple) avec lequel il pourra frapper d'autres personnages. Le personnage frappé se verra infliger un certain degré de dégâts.

Un personnage est défini selon 2 caractéristiques :

    Son nom (unique).

    Ses dégâts.

Les dégâts d'un personnage sont compris entre 0 et 100. Au début, il a bien entendu 0 de dégât. Chaque coup qui lui sera porté lui fera prendre 5 points de dégâts. Une fois arrivé à 100 points de dégâts, le personnage est mort (on le supprimera alors de la BDD).


Installation
------------

1) Copiez le minijeu dans votre serveur web :
   - /opt/lampp/htdocs/          avec Xampp sur Linux
   - C:\wamp\www\                avec Wamp pour Windows
   - /Applications/MAMP/htdocs/  avec Mamp pour Mac OS X

2) Créez une base de données nommée "combats" avec phpMyAdmin, importez le fichier structure.sql (bdd/structure.sql) dans cette base de données

3) Tapez l'URL http://localhost/minijeu dans votre navigateur préféré ou http://localhost:8888/minijeu pour Mac OS X.

4) Enjoy ! ;)