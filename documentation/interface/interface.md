---
title: interface
layout: default
parent: Documentation
grand_parent: Accueil
nav_order: 5
---

# Configuration interface
Depuis le menu configuration -> interface vous pouvez modifier l'apparence de votre JeeMate.
3 types existent, morphic, matérial et glass
A vous de tester, jouer, changer afin de trouver le type d'affichage qui vous correspond.

# Configuration des  onglets
L’application est décomposée en quatre onglets, par défaut. Il est possible d’en créer, cacher, réorganiser, ou customiser leur icône.

-   Favoris Maison
-   Pièces
-   Designs Jeedom et pages web favorites
-   Caméras

Pour naviguer entre les onglets, il suffit de cliquer sur les boutons dans la barre d’onglets en bas de l’application.

Lorsque vous cliquez sur les boutons Pièces, ainsi que Designs, une liste apparaitra afin de sélectionner la Pièce ou le Design que vous souhaitez afficher.

Pour créer un nouvel onglet, ou éditer un onglet existant, il suffit de faire un appui long sur la barre d’onglet afin d’afficher la page d’édition, un double click sur l'icône d'un onglet vous ouvre directement sa configuration.

![](/img/doc/onglets-1-273x300.jpg.webp)

Depuis la page d’édition, faire un appui long puis glisser pour réorganiser les onglets et cocher pour rendre visible.

**Les onglets par défaut ne peuvent pas être supprimés. L’onglet Maison ne peut être ni caché, ni déplacé.**

Cliquer sur le nom d’un onglet pour accéder à sa configuration.
![](/img/doc/onglet-configuration-2-207x300.jpg.webp)

# Onglets Favoris Maison

L’écran principal contient les sections suivantes :


1.  Barre d’outil tout en haut.  
    Permet d’accéder au menu latéral gauche de configuration JeeMate, au statut de connexion, aux notifications, de rafraîchir les statuts des équipements, ou bien d’ouvrir le menu latéral droit.
2.  Résumé global Jeedom (dépend de la configuration des résumés dans Jeedom).
3.  L'emplacement de vos tuiles.
4.  Barre d’onglets


## les résumés
L'affichage des résumés est le même que celui de votre Jeedom.

Vous pouvez depuis JeeMate (ouvrir une pièce, editer pièce, configurer les résumés) faire tout ce que vous faite depuis Jeedom, a savoir :
modifier l'icone et sa couleur
créer un nouveau type de résumé
ajouter, supprimer, désactiver un equipement etat.

## Ajout de tuile

Pour ajouter une tuile (Équipements, Scénarios, Groupes, Applications Android), cliquer sur le crayon en haut à gauche de l’écran, puis choisir le type de favori que vous souhaitez ajouter.

![](/img/doc/favoris-206x300.jpg.webp)

## Personnalisation des tuiles

Dans les onglets, il est possible de réorganiser et redimensionner les tuiles.

Pour pouvoir réorganiser les tuiles, il suffit de cliquer sur le bouton « Crayon » dans la barre, coin haut droit de l’écran. Puis dans le menu latéral, activer la fonction « Éditer ».

Une fois le mode « Éditer » actif, il est alors possible de réorganiser les tuiles.

Pour afficher le menu de personnalisation d’une tuile, il suffit de faire un appui long sur la tuile.

Note: le menu est disponible si le mode « Éditer » est **inactif**.

D’autres options peuvent être accessibles en fonction du type de tuile (Groupes/Panels etc)

![editiontuile-285x300.jpg.webp](/img/doc/editiontuile-285x300.jpg.webp)
Tuile Taille mini ou normale :

![MiniNormale-300x168.jpg.webp](/img/doc/mininormale-300x168.jpg.webp)

Contenu centré ou aligné à gauche :

![IMG_20211029_144514-2-300x151.jpg.webp](/img/doc/img_20211029_144514-2-300x151.jpg.webp)

Grille : permet de changer le nombre de colonnes de tuiles dans les onglets.

![Grille.gif](/img/doc/grille.gif)

Configuration : Ici on accède à tous les réglages disponibles sur une tuile (changer le nom, l’icone, etc…)

![ConfigurationTuile-768x1156.jpg.webp](/img/doc/configurationtuile-768x1156.jpg.webp)

**Configurer les commandes (coché)**  
  
**Commandes infos et actions :**  
La liste des ID des commandes de votre équipement.  
  
**Rendu conditionnel :**  
Modifications de l’icône, un mode avancé permet de personnaliser encore davantage.  
  
**Commandes optionnelles :**  
Si votre équipement en dispose vous pouvez mettre les infos batterie, connecté, etc…, ce sera visible sur la page détails de votre tuile.  
  
**Rendu conditionnel vue détails :**  
Ajouter une image de fond sur la page détails de votre tuile, possibilité d’y mettre également des conditions.  
  
**Personnaliser tuile :** (plus d’info en dessous)  
  
**Indicateur lumineux tuile :**  
Utiliser la led de la tuile dans des conditions.  
de base rouge fixe si la batterie est faible, rouge qui clignote si info sabotage activé.  
Il vous est possible d’ajouter des conditions (voir info dédié)

**Personnaliser tuile :**

![PersonnaliserTuile.jpg.webp](/img/doc/personnalisertuile.jpg.webp)

**D’autres options peuvent être accessibles en fonction du type de tuile (Groupes/Panels etc)**

## Contrôle d’un équipement

**_Simple clic sur tuile_**

Sur les tuiles actions de type lumières, volets ou prises, exécute l’action.  
**– Si dans jeedom un mot de passe est défini pour la commande à exécuter alors il vous sera demandé à l’aide du digicode ou du capteur d’empreinte.**  
Sur les tuiles actions du style multimédias, thermostats, etc…, ouvre la page dédiée.

Sur les tuiles infos du style température, ouvrant, détecteur, etc…, ouvre la page détails et historique.

**_Double click sur tuile_**

Sur les tuiles actions du style lumières, volets, ouvre la page des commandes supplémentaires.

**_Les pages spécifiques_**

| **Thermostat** | **Alarme** | **Mode** |
| --- | --- | --- |
| ![](/img/doc/pagethermostat-scaled.jpg.webp) | ![](/img/doc/pagealarme.jpg.webp) | ![](/img/doc/pagemode-scaled.jpg.webp) |
|     |     |     |
|     |     |     |
| Eclairage Luminosité | Eclairage Température de couleur | Eclairage couleur |
| ![](/img/doc/pagelumierelum-scaled.jpg.webp) | ![](/img/doc/pagelumieretemp-scaled.jpg.webp) | ![](/img/doc/pagelumierecouleur-scaled.jpg.webp) |
|     |     |     |
|     |     |     |
| Multimédia |     |     |
| ![](/img/doc/pagemultimedia-2-scaled.jpg.webp) |     |     |

# Onglet Pièces

![](/img/doc/photo1-1.webp)

De la même manière que pour l’onglet Favoris, l’écran contient trois sections :

1.  Résumés
2.  Scénarios
3.  Equipements  
      
    La personnalisation des tuiles est identique aux onglets favoris, ici seul l’option afficher nom de la pièce ne sera pas pris en compte.

Il est possible de customiser l’affichage pour chaque pièce en cliquant sur l’icône d’édition (crayon) en haut à droite dans la barre d’outils JeeMate.

![](/img/doc/jeemate_edit_piece.webp)

Il sera alors possible de :

-   Définir la pièce par défaut lorsque l’on clique sur la barre d’onglet pour accéder aux pièces
-   Renommer la pièce
-   Choisir une image de fond
-   Choisir l’image de Synthèse Jeedom en fond
-   Choisir une couleur/un dégradé de fond
-   Utiliser le thème par défaut
-   rendre visible ou non les tuiles

## Designs Jeedom et pages web favorites

Cet onglet permet d’afficher des pages web. Telles que :

-   Designs Jeedom
-   Vos dashboards Grafana préférés
-   etc

Pour cela, il suffit de cliquer sur le bouton Onglet « Design » dans la barre en bas, puis sur l’icône « Roue crantée ».

![](/img/doc/jeemate_onglet_design.webp)

Dans la page « Liste des designs », il est possible de :

-   Ajouter un design
-   Choisir d’afficher le design par défaut au démarrage de JeeMate
-   Trier par ordre alphabétique les designs de la modale de sélection
-   Changer l’ordre des designs, de la même manière que les tuiles en appuyant pendant quelques secondes sur le design puis déplacer
-   Éditer la configuration d’un design en cliquant dessus

Pour ajouter un « design » ou url vers une page web, il suffit de cliquer sur le bouton « + », puis

-   Visible : si vous souhaitez cacher ou non le design dans la modale de sélection
-   Défaut : pour définir le design par défaut à afficher lorsque l’on clique sur le bouton Onglet « Design »
-   Saisir un nom
-   Saisir son URL
-   La fréquence de rafraichissement si besoin

## Onglet Caméras

L’onglet Caméras permet de visualiser toutes les caméras disponibles dans Jeedom ou non, et en Live!  
Les caméras présentes dans Jeedom sont automatiquement importées.

![](/img/doc/jeemate_onglet_camera.webp)

Cliquer sur le bouton « + » pour ajouter une caméra puis :

-   saisir un nom
-   et son URL

La caméra apparaitra alors dans JeeMate. Vous pourrez ensuite rééditer ses paramètres, ou bien la supprimer, en swipant sur son nom pour faire apparaître le menu de configuration.

La liste des caméras peut être réorganisée. Pour cela, il suffit d’appuyer pendant quelques secondes dessus et ensuite de la placer à l’endroit souhaité.

Un clic simple sur la caméra permet de l’afficher en plein écran et avoir accès aux boutons PTZ.

# Type de grille
Pour chaque onglet, pièce, résumé ou panel vous avez le choix entre 3 types de grilles différentes.
## Normal
Un placement à la suite de chaque tuiles intégrées. Possibilité de chosir le nombre de colonne. La page est scrollable.
En mode édition (crayon), un appui long permet de déplacer la tuile, un double click permet de pouvoir modifier sa taille.
## Avancée
Un placement libre en fonction des colonnes de la grille. Possibilité de chosir le nombre de colonne. La page est scrollable.
En mode édition (crayon), un appui long au centre de la tuile permet de la déplacer, un appui long sur un des bords permet de pouvoir modifier sa taille.
Les composants JeeMate sont accessible.
## Plan
Un placement de chaque élément au pixel. La page à une taille fixe, celle de votre écran.
Les composants JeeMate sont accessible.
Le mode plan apporte également une gestion des calques, vous pouvez donc utiliser une image de fond comme base et ensuite ajouter des calques sous condition. Les calques doivents être de la même taille que l'image de fond.
Exemple ici : [plan](/fr/tuto/plan)
