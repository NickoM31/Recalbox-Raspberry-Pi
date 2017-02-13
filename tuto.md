#Recalbox sur Raspberry Pi  




Je vous propose de créer vous même votre plateforme de jeux rétro sur Raspberry Pi.
Pour se faire, nous allons utiliser un système qui regroupe plusieurs émulateurs : Recalbox.

Nous remercierons *DigitalLumberjack*, créateur de Recalbox, pour le partage de son savoir-faire.

##Etape 1: Le matériel

Pour créer votre Recalbox vous aurez besoin des éléments suivants :
* Un Raspberry Pi 3 (Pi 2, Pi 1 B/B+, ou un Zero);
* Une carte micro SD d'au moins 16GO
* Un câble d'alimentation micro USB > 1.5AMP 
* Un cable HDMI
* Une manette de Xbox360 (PS3 Sixaxis, Dualshock 3 ou une manette usb) 
* Une clé bluetooth si vous utilisez une manette sans fil
* Un boîtier pour le Raspberry 
* Un clavier USB si vous avez une manette non supportée par défaut.

##Etape 2: Formatage de la carte sd

Vous devez utiliser au moins une carte SD de 8GB.

Si vous êtes sous Windows ou MacOSX utiliser SD Card Formatter (https://www.sdcard.org/downloads/formatter_4/).

Si vous êtes sous Linux, utilisez l'éditeur de partitions GParted.
Insérez votre carte SD dans votre pc et démarrez Gparted.

Si vous avez des partitions existantes il faudra toutes les démonter puis les supprimer.
![GParted1](/screenShot/gparted1.jpg)

Ensuite créer une table de partitions avec comme type de table ms-dos.

![GParted2](/screenShot/gparted2.jpg)

Pour le choix du système de fichiers sélectionnez FAT32 .
![GParted3](/screenShot/gparted3.jpg)

Appliquez toutes les opérations.
![GParted4](/screenShot/gparted4.jpg)

Voilà votre carte SD est prête.

##Etape 3: Le logiciel

Pour télécharger la dérnière version de Recalbox rendez-vous sur (https://github.com/recalbox/recalbox-os/releases) .
![Recalbox1](/screenShot/recalbox1.jpg)

Décompressez le fichier recalboxOS.zip puis ouvrez le dossier.

Copiez tous ce qu'il y a dedans et coller le à la racine de la carte SD.

Placez la carte dans votre Raspberry Pi, branchez le hdmi et l’alimentation micro-usb.

##Etape 4: L'installation et la configuration de Recalbox

Elle démarre automatiquement et vous devrez attendre quelques minutes pour commencer à jouer.

Si vous avez une manette USB, branchez votre clavier USB, appuyez sur ENTRER dans le menu de séléction des système. Ensuite séléctionnez "Configure Input" avec la touche S et sélectionnez "Configure a controller" encore avec S. Suivez les instructions pour configurer votre manette. Le nom des bouton est basé sur la manette Super Nintendo.






