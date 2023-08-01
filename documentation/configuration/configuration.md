---
title: Configuration
layout: default
parent: Documentation
grand_parent: Accueil
---

# Configuration

![configurationjeemate.jpg](/configurations/configurationjeemate.jpg =300x)

# Notifications
![configuration-notifs.jpg](/configurations/configuration-notifs.jpg =300x)
Configurer ici les permissions de l'applications pour la réception des notifications.

Les notifications sont automatiquement supprimées passé un certain delais, configurer celui-ci ici.

Si vous avez des objets multimédia importés dans Jeemate, vous pouvez sélectionner ceux pour lesquel vous voulez recevoir une notifications.

Plus d'informations sur les notifications ici : [notifications](/fr/doc/notifications)

# Géolocalisation
![configuration-geoloc.jpg](/configurations/configuration-geoloc.jpg =300x)

Plus d'informations sur la configuration géoloc/géofence ici : [Geolocalisation](/fr/doc/Geolocalisation)

# Jeedom / Session
![sessions.jpg](/configurations/sessions.jpg =200x) ![jeedomconfig.jpg](/configurations/jeedomconfig.jpg =200x) ![jeedomserveur.jpg](/configurations/jeedomserveur.jpg =200x)

Si vous utilisez la version gratuite de JeeMate, vous arriverez directement sur le 2eme écran.

Si vous utilisez la version premium, le premier écran vuos permet de gérer vos différentes sessions et les jeedom qui y sont associés.

-   Long polling / DNS , cette option est automatiquement coché lors de l'appairage.
-   Serveur (3ème image), paramètres de connexion à votre serveur Jeedom (adresse interne, externe etc) récupérés lors de l'appairage.
-   Appairage : vous pouvez soit rechercher un Jeedom sur le réseau en indiquant son adresse interne (192.168.x.x) où son adresse externe (https://monjeedom.com) soit scanner le QR Code disponible dans votre équipement du plugin JeeMate.
-   Synchroniser l’interface : importe vos équipements Jeedom dans JeeMate.
-   Tester la connexion : permet de tester la connexion entre l’application mobile et votre serveur Jeedom
- Compte jeedom : OK si vous êtes premium, NOK si vous êtes free. Si vous êtes un utilisateurs premium mais que le compte affiche NOK, clicker simplement dessus pour mettre à jour.
- Test validité certificat SSL : Pour une bonne utilisation de JeeMate et de ces services associés, il est important que votre connexion soit sécurisée, vérifier ici si cela est bien le cas.


# Reconnaissance vocale

JeeMate permet de contrôler votre Jeedom, en mode offline. C’est-à-dire que la reconnaissance du hotword ainsi que la transcription de la voix en texte est faite sur votre appareil, et ne passe pas par le Cloud.

-   Interactions : si l’option est activée, la commande vocale est envoyée aux Interactions Jeedom
-   Rhasspy plugin : si l’option est activée, la commande vocale est envoyée à Rhasspy
-   Toujours active : si l’option est activée, l’appareil reste en permanence sur écoute, en attente d’une commande. Dans ce mode, la configuration d’un hotword est obligatoire
-   Hotword : la phrase clé que vous souhaitez pour valider une commande. Exemple : « Jasper », « Dis Toto » etc


# Service SMS

*Version Hors Stores (Android)*
![configuration-sms.jpg](/configurations/configuration-sms.jpg =300x)
Il est possible d’utiliser un ancien mobile comme passerelle entre Jeedom et les SMS.

-   Autoriser ou non l’envoi de SMS depuis Jeedom
-   Autoriser ou non la réception de SMS
-   Interactions : si l’option est activée, le contenu du SMS est envoyé aux Interactions Jeedom
-   Rhasspy plugin : si l’option est activée, le contenu du SMS est envoyé au plugin Rhasspy
-   Liste blanche permet d’ajouter/supprimer des contacts autorisés. Tout SMS, envoyé par un contact non présent dans cette liste blanche, ne sera pas transmis à Jeedom

# Service SIP
![configuration-sip.jpg](/configurations/configuration-sip.jpg =300x)
Il est possible de connecter JeeMate à un serveur compatible Asterisk, et d’effectuer ou recevoir des appels audios/vidéos SIP (softphones, portier vidéo etc)

Exemple d’un appel softphone Windows (PC sans webcam) vers JeeMate

![](/img/doc/sip_call-287x300.webp)

# NFC Tags
![configuration-nfc.jpg](/configurations/configuration-nfc.jpg =300x)

# Bluetooth
![configuration-ble.jpg](/configurations/configuration-ble.jpg =300x)

# Sécurité
![configuration-sécurité.jpg](/configurations/configuration-sécurité.jpg =300x)


-   Activer biométriques : permet d’activer la reconnaissance sur empreinte digitale, ou faciale
-   Activer digicode : permet d’activer l’utilisation d’un digicode
-   Digicode : saisir le code souhaité
-   Sécuriser lancement JeeMate : permet de sécuriser le lancement de l’application avec une des options ci-dessus
-   Sécuriser menu Configuration : permet de sécuriser l’accès au menu Configuration de JeeMate, cela bloque également toutes les configurations accessibles sur les pages, tuiles, onglets.
- Sécuriser plugin Mode : pour toutes action sur une tuile du plugin mode, le code vous sera demandé.
- Sécuriser plugin alarme : pour toutes action sur une tuile du plugin alarme, le code vous sera demandé.

**Si vous configurez un mot de passe sur vos commandes dans Jeedom (dans les paramètres des commandes), alors ce sera ce dernier qui sera utilisé en priorité. Le digicode sera d’ailleurs affiché même si le digicode n’est pas activé.**


# Interface
Voir la section dédiée : [interface](/fr/doc/interface)


# Raccourcis système

# Service d'arrière plan
![configuration-sap.jpg](/configurations/configuration-sap.jpg =300x)

# Sauver/Importer App
![configuration-backup.jpg](/configurations/configuration-backup.jpg =300x)
- Sauvegarder : permet d’enregistrer toute la configuration de votre application mobile, paramètres et interface, dans votre serveur Jeedom. Vous devez saisir un nom pour votre sauvegarde.
- Automatiser la création de sauvegarde.
- Restaurer une sauvegarde : permet de récupérer dans votre serveur Jeedom la sauvegarde de votre application mobile.

## Sauvegarde globale / partagée

Dans l'application : slider sur le nom d'une de vos sauvegarde pour pourvoir soit la passer en sauvegarde globale, soit la supprimer.

Dans le plugin JeeMate, aller dans ***mon jeemate*** , vous pourrez ici aussi passer une de vos sauvegarde en globale ou non, ou bien encore la supprimer.


