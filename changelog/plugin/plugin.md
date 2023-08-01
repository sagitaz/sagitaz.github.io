---
title: Plugin
layout: default
parent: Changelog
grand_parent: Accueil
---

Dans le cas ou une mise à jour n'a pas de changelog, c'est que celle-ci est juste une correction de bug mineur ou de traduction.

Le plugin BETA est réservé aux utilisateurs de la version BETA de l'application JeeMate, son utilisation avec l'application en version STABLE peux rendre votre Jeedom et/ou votre JeeMate non fonctionnel. Le support des version BETA est effectué sur un fil privé du discord réservé aux utilisateurs autorisés.

## STABLE du 06/06/2023

### Corrections:

suppression et modification logs. 
suppression checkbox autorisation geofence (ne servait pas)
suppression des boutons sur équipements NFC et panel
Fix erreur JS filter param

### Nouveautés:

Conversion automatique en webp des jpg et png importés depuis l'application.

## STABLE du 23/04/2023

### Corrections:

Erreur code 0 
Gestion error ajax sur 4.4 (merci JAG)
synchronisation partielle
couleur des génériques JeeMate sur ios.

### Nouveautés:

Génériques pour Purificateur d'air
Génériques pour aspirateur robot ou tondeuse robot

## STABLE du 07/04/2023

### Corrections:

Erreur sur ask simple.
Soucis lorsque geofence son proche et que l'event effectue sortie de zone et entrée sur le même point.
Etat de charge qui n'était pas mis à jour.

## STABLE du 08/03/2023

### Nouveautés:

Intégration en automatique des plugins speedtest et speedtestByOocla (conseillé).

### Corrections:

Position GPS plus remonté à la commande.

## STABLE du 07/03/2023

### Nouveautés:

Affichage des tuiles pièces dans le plugin. merci Noodom.
Commandes infos volume et état écran.
icones affichées sur les commandes actions en comportant.
Log CoreDebugGeoloc séparé par users.
Mise en place pour news de l'application de nouvelles API.

### Corrections:

BLEA commande info custom name.
Valeur 1 sur résumé non remontée.

## STABLE du 11/02/2023

### Nouveautés:

Modification des databases Notifications, geofence et backup, pour les notifs groupées il faut resélectionner les appareils.

### Corrections:

Gestion gache nuki
suppression des migrations database anciennes, donc si vous utilisez encore une version de plus de 8 mois, il faudra repartir à 0.

## STABLE du 23/01/2023

### Nouveautés:

Personnalisation des notifs configurées via le plugin (de la même façon que notif_général)

### Corrections:

Nettoyage ask en timeout
liens vers la doc dans la création d'équipement

## STABLE du 18/01/2023

### Nouveautés:

Info source prochaine alarme
Notifications groupées
Ask groupés

### Corrections:

import images depuis app
Erreur JS sur widget map
Erreur sur setSensor

## STABLE du 04/01/2023

### Nouveautés:

Traduction du plugin (US, DE, ES, PT, IT).
Plugin meteoFrance, rteEcowatt, suiviConso ajoutés dans la liste des plugins auto géré (nécessite la prochaine version de l'app)
Passage à leaflet 1.8.0 pour les cartes.
Recherche possible sur les objets et sur les équipements.
Bouton copier les infos user pour les partager plus facilement.
Commande info “prochaine alarme”
Commande action TTS et configutation du volume et de la rapidité sur chaque user.
Commande action pour changer le type de sonnerie (Android only)
Ajout de la gestion des images, import, suppression et conversion vers format webp (1,8mo en png = 0,4mo en webp).
Amélioration graphique des pages.

### Corrections :

SSID qui force geofence à 0
Remove backup si fichier n’existe pas
TTS speak
Verif date geoloc
Valeur info pour jeedom 4.3
notification vidéos
distance marche/voiture Geoloc

## Beta du 18/09/2022

Widget map : redimensionnement, 2 nouvelles cartes, map par default.
Notification : soudMode qui forcé le mode normal.
Filtre sur les pièces (page principale du plugin).
Message premium sur la partie geofence.

## Beta du 06/09/2022

### Nouveautés:

Widget Map
Ajout de la tendance
Météo France plugin géré en auto.

## V 1.4.0

### Nouveautés :

Option pour les multiples SSID du type monSSID_5g, monSSID_Ext, monSSID_2.4, dans le champ, vous entourez le SSID avec % (%monSSID%).
Penser à configurer dans jeedom votre code postal, sera utilisé pour les alertes météo.
SSID wifi à indiquer dans vos zones geofence, si le wifi est capté avant qua la geofence le soit, celle-ci est forcé.
Ajout des plugins alexaFireTv et aTVremote dans la liste des plugins pris en charge sans configuration.

### Corrections :

Level de batterie du plugin APC reste à 0.
Notification, level volume et pitch.
Erreur en 4.1 qui bloqué le lancement de jeemate.

## V 1.3.0

### Nouveautés :

Barre de recherche dans les pièces.
Barre de recherche d'adresse sur la page geofence.
Option pour cacher des commandes lors de l'import.
Nettoyage de l'import des scénarios afin d'éviter les erreurs.
Panel, popup multiple, movable et gestion des thèmes dark/light. possibilité de personnaliser l'image depuis votre équipement dans le plugin, focus sur user.

### Corrections :

Couleur bulle notification était supprimée lors de la maj du plugin.
Page geofence - la carte chargée plusieurs fond en même temps.
Commande geofence et distance n'était pas renommé si la geofence l'était.
Notif caméra.
Erreur sur batterie state dans HTTP ERROR.
Géolocalisation erreurs diverses et améliorations.
Distance entre les users ne fonctionnait plus.
Date des backups.
+++ pleins de petites corrections et ce qu'on a oublié.

## V 1.1.0 (1690)

Plugin stable (2022-05-24 11:20:33) et beta (2022-05-24 11:20:39) identique

### Nouveautés :

Panel : ajout d’infos, choix de carte.
Géofence : choix de carte.
Notifications systèmes, les images sont visibles.
Notifications Android, possibilité de modifier le mode (normal, silencieux, vibreur).
Refonte de la page principale du plugin (choix des pièces et équipements, etc…).
Bouton “auto-configuration”, utile sur une première installation pour cocher et importer automatiquement tous les plugins compatible JeeMate.
Prise en compte de tous les nouveaux plugins.

### Corrections :

commande info ip locale de nouveau disponible.
Notifications avec images et vidéo caméra corrigée.
Optimisation géolocalisation.
Position par défaut sur la géofence et le panel si pas de configuration dans jeedom.
Notification media player.
Nom des commandes notifications changées si notification renommée.
+++ pleins de petites corrections et ce qu'on a oublié.

## V1.1.0

Test d'amélioration de la charge en polling
Refonte visuelle d'une partie du plugin

## V1.0.0

Clics sur le nom dans la session dans la barre de menu du 1er onglet: Clic simple: menu changement rapide session Clic long: page de gestion des sessions
Ajout/correction dans la page Config Geoloc de l’app, d’une option pour définir le jeedom qui recoit les events de geoloc
Ajout possibilité de configurer les raccourcis systèmes pour chaque session
Ajout et correction des types génériques Volet BSO Slider, Véhicule dans App et plugin (widget véhicule en cours)
Ajout réorganisation des sessions
Ajout possibilité de lancer une session depuis les raccourcis systèmes
Passage de la page About en pleine page
Réactivation de la fonction « Appliquer la personnalisation à des widgets compatibles » A betastester
Correction scénarios provenant d’une pièce vide
Correction iOS scroll en bas de page
Correction icone Garage
Correction de l’interface dans la page détails Météo
Correction Raccourcis systèmes (veuillez reconfigurer vos raccourcis, 4 raccourcis max)
Correction volume media. Note1: pour les medias, le plugin jeemate a actuellement quelques soucis d’envoi events/refresh vers l’app, corrigés prochainement Note2: corrections playlist et radio en cours pour certains plugins (sonos..), probablement dispo dans prochaine maj
Correction lastCommunication page détails
Correction lien github dans page About
Correction personnalisation icone alarme ON qui écrasait le icone OFF
Correction pairing connection externe dans le step by step
Correction de certains plugins dans l’import piscine, sonos, googlecast, spotifyconnect, alexa amazon,deezer
Corrections dans l’import en cours
Correction import
Correction icone jeedom Mode dans la tuile
Correction couleur libellé bouton Mise à jour plugins
Correction Tuile Media Play/Pause, Slider Volume, et libellés
Correction delete raccourci système
Correction icone vert/rouge dans Page détails Santé
Correction dans Pièce, éditer, utiliser image de la synthese : ne fonctionnait qu’en thème glass/dégradé global
Correction on ne pouvait pas renommer les onglets par défaut (maison etc)
Correction changement du nom de la session active n’était refresh dans onglet accueil que lors du reboot
Correction la popup design n’était pas filtrée en multijeedom
Correction page Plugin tenir compte de ne pas mettre à jour dans jeedom
Correction quand la configuration est sécurisée, verrouiller boutons mise à jour plugin
Correction de certains libellés FR/EN
Corrections dans l’import en cours
Corrections dans l’import en cours
