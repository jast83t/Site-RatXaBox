+++
title = "Ratxabox"
date =  2017-11-26T09:17:16+01:00
weight = 5
+++

## Installation automatique de ruTorrent avec rTorrent
*Version "Seedbox-Manager Workflow"*

![](https://images.mondedie.fr/eGGF79nV/ALXQCNGT)

**Détail du tutoriel:**

1. Préambule
* Installation
* git-core
* cloner et lancer le script
* Les options
* Liens utiles


## 1. Préambule

* [Bien lire le tuto de Ex_Rat](https://mondedie.fr/d/5399 "Ratxabox") (juste le lire, ne pas exécuter script de ex_rat)
* [Dépot RatXaBox](https://github.com/xavier84/RatXaBox "Ratxabox")

## 2.  Installation

*Mise a jours + installation de Git:*
```bash
apt-get update && apt-get upgrade -y
apt-get install git-core -y
```

*On clone et on lance le script:*
```bash
cd /tmp
git clone https://github.com/xavier84/RatXaBox ratxabox
cd ratxabox
chmod a+x bonobox.sh && ./bonobox.sh
```
*Il vous suffira de suivre les indications affichées:*

![Google logo](https://cloud.llamasweet.tech/index.php/apps/files_sharing/ajax/publicpreview.php?x=1920&y=543&a=true&file=ratxaboxlin.jpg&t=EWJJRRVDeKBnP7I&scalingup=0 "google logo")

## 3.  Les options
Pour installer les options: après le redémarrage du serveur, relancer le script et choisir le numéro **10**

![Google logo](https://cloud.llamasweet.tech/index.php/apps/files_sharing/ajax/publicpreview.php?x=1920&y=543&a=true&file=options.jpg&t=QoqdE9ywmV4DzX8&scalingup=0 "google logo")

*Voici les options supplémentaires disponibles:*

![Google logo](https://cloud.llamasweet.tech/index.php/apps/files_sharing/ajax/publicpreview.php?x=1920&y=543&a=true&file=options%25C3%25A9tendues.jpg&t=GAKD2pGwgBIkhB9&scalingup=0 "google logo")

## 4. Liens utiles

*Voici les liens pour vous connecter à l'interface de vos services:*

* TARDIStart :
IPserveur/tardistart

* SickRage :
IPserveur/sickrage

* CouchPotato :
IPserveur/couchpotato

* Plex :
IPserveur:32400/web

* Emby :
IPserveur:8096

* Esm :
IPserveur/esm


*Partie technique:*

- TARDIStart
Administraion des liens TARDIStart :
IPserveur/tardistart/admin

{{% notice info %}}
Si vous rencontrez un bug ou tout autre problème, n'hésitez pas à me contacter !
[La discussion se passe ici](https://mondedie.fr/d/8717-Discussion-RatXaBox-ruTorrent-avec-rTorrent-Version-Workflow "Ratxabox")
{{% /notice %}}
