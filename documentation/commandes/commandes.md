---
title: Commandes
layout: default
parent: Changelog
grand_parent: Accueil
---
# Les commandes actions

## Afficher la page météo :

Affiche la page des informations avancées de votre widget météo. 

## Afficher Horloge :

Non fonctionnel pour le moment 

## Afficher Alarme :

Affiche la page avancée de vos Alarmes, celle affichée sera la première par ordre Alphabétique. 

## Afficher le digicode :

Affiche le digicode si vous en avez configuré un dans les options de JeeMate. Entrer votre code pour le fermer. 

## Afficher la synthèse :

Affiche la page synthèse de votre installation, vous pouvez personnaliser les images des pièces ainsi que les résumés depuis la page Objets de Jeedom. 

## Smart Caméra :

Non fonctionnel pour le moment 

## Verrouiller application :

Non fonctionnel pour le moment 

## Assistant vocal :

Non fonctionnel pour le moment 

## Regénerer interface :

Permet de faire une regénération de votre interface JeeMate 

## Lancer une application (Android) :

Vous permet de démarrer une des applications présentes sur votre équipement.saisir dans le champ « Message » le nom de l’apk.exemplepour lancer Chrome, saisir com.android.chromepour lancer AntiCovid saisir fr.gouv.android.stopcovid

Pour récupérer facilement le nom de l’apk (Android), click long sur l’icône de votre application, informations, puis le petit i en haut à droite.

## Afficher un design :

Dans le champ Message saisir l’id du design. Seuls les designs cochés dans JeeMate / Configuration sont affichables par cette commande.Vous trouverez cette information soit dans l’url de votre design, soit dans le fichier GetDesign (JeeMate / Debug Fonction) 

## Afficher la pièce :

Dans le champ Message, saisir l’id de la pièce. Seules les pièces cochées dans JeeMate / Configuration sont affichables par cette commande.Vous trouverez cette informations soit dans l’url de votre pièce, soit dans le fichier GetObjects (JeeMate / Debug Fonction) 

## Afficher un onglet :

Dans le champ Message saisir l’id de l’onglet à afficher.L’id de l’onglet Home est le 0, ensuite l’id est incrémenté sur les onglets actifs. 

## Show Flap :

Non fonctionnel pour le moment

## Set Android Alarm (Android) :

Vous permet de créer une Alarme sur votre appareil Android.

Dans le champ titre, il faut indiquer les informations de répétition, soit non, soit les jours de répétition.

Pour que l’alarme soit seulement sur la journée en cours, laisser le champ vide.Pour répéter l’alarme le lundi, jeudi et samedi mettre 2,5,7 ou 0,2,5

Exemple sur le dashboard

Dans le champ Message, indiquer l’heure et le titre de l’alarme sous la forme suivante :heure;titre12:00;mon alarme



exemple depuis un scénario


## Afficher URL :

Saisir simplement l’url au format www.jeemate.fr dans le champ message. 

## Show Screen (Android) :

Vous permet d’allumer ou d’éteindre votre appareil Android.

Important : il faut autoriser JeeMate à faire un ScreenOnOff dans les paramètres Android (Application d’administration de l’appareil).
Pas le choix, il faut en assumer les risques.

## TTS Speak :

Plus d’infos à venir dans une section dédiée.

## Envoyer des SMS (Android) :

 Plus d’infos à venir dans une section dédiée.  Android Only

 # Les commandes infos

![cmdinfos.png](/img/doc/cmdinfos.png)

## État cmd
Vous donnera l'id de la dernière commande exècutée depuis l'appareil, cela vous permet de mettre en place divers scénarios.
Plus d'infos : [Savoirqui](/fr/tuto/Savoirqui)

## État Batterie
Le pourcentage restant de la batterie.

## Date prochaine alarme
La date et l'heure de la prochaine alarme programmée sur votre appareil, vous devrez configurer dans l'application JeeMate les applications autorisées à donner l'information.

## État Location Pièce
A venir.

## État ID Bluetooth à proximité
L'id de l'appareil bluetooth le plus proche.

## État RSSI Bluetooth à proximité

## IP locale
L'IP de votre appareil lorsque vous étes connecté sur le réseau local.

## État Capteur Lux
La luminosité remonté par le capteur de votre appareil. Peut être désactivé dans les services d'arrière plan.

## Nom Bluetooth à proximité
A venir.

## Source prochaine alarme
le nom de l'apk de l'application ayant envoyé l'info prochaine alarme.

## Volume
Le pourcentage du volume réglé sur votre appareil.

## Ecran
L'etat actuel de votre ecran 
- SCREEN_ON
- SCREEN_OFF 
- SCREEN_UNLOCKED

## État de charge
information binaire :
0 = l'appareil n'est pas en train d'être chargé.
1 = l'appareil est mis en chage.