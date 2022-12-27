# Wled-soundreactive-tutoriel-complet
Tutoriel complet en français pour la configuration de WLED sound reactive avec un panneau LED (plans &amp; objets inclus)

#remarque: aucun des liens n'est affilié ou partenaire, ce sont juste les composants que j'ai utilisé.

Installation de base du panneau

Un esp32 dev kit C (avec pin 5 v!, pas un LOLIN) : https://amzn.eu/d/hWhCrPs

un panneau LED matrix (il y en a des plus évolués mais j'ai pris un bon marché): https://www.amazon.de/-/en/WS2812B-Digital-Flexible-Programmed-Density/dp/B07Z62WYT4

le logiciel wled sound reactive : https://github.com/THATDONFC/WLED-Reactive

un micro inmp441 : https://invensense.tdk.com/wp-content/uploads/2015/02/INMP441.pdf

une alimentation 5V à découpage : https://amzn.eu/d/iQsgmgx

Merci à https://github.com/jozsefcsiza/ESP32-INMP441-SPECTRUM pour son schéma de connexion du INMP441

Merci infini à l'équipe Wled : https://kno.wled.ge/

Précautions:
Je vous encourage à placer un interrupteur sur votre alimentation, à ne pas toucher le module ESP32 lorsqu'il est sous tension et à être prudent de manière générale soit pour vous ou au moins pour ne pas griller le matériel ;-)


#Procédure:

Configuration de WLED :
1. # Installer WLED

<https://install.wled.me/>

utiliser chrome ou edge et l’installation se fait via l’esp32 connecté au pc en usb

1. # Configuration de base

une fois connecté à Wled configurer comme ceci:,

<img src="https://github.com/wizbe/Wled-soundreactive-tutoriel-complet/blob/main/image001.png">

Current maximum = 55 ma maximum théorique par led \* nombre de led (150 dans mon cas)



## Taille de la bande ou du panneau

Fixer la taille du panneau et la pin sur laquelle il peut-être commandé

<img src="https://github.com/wizbe/Wled-soundreactive-tutoriel-complet/blob/main/image002.png">

1. # Connexion du micro INMP441

<img src="https://github.com/wizbe/Wled-soundreactive-tutoriel-complet/blob/main/image003.png">

Schéma complet en fritzing disponible dans la section fichiers.

Selon le schéma de câblage ci-avant la configuration par défaut de Wled reactive est correcte.
Il faut maintenante activer le micro dans WLED

<img src="https://github.com/wizbe/Wled-soundreactive-tutoriel-complet/blob/main/image005.png">

1. # Faire un test
Le bandeau doit être allumé !

<img src="https://github.com/wizbe/Wled-soundreactive-tutoriel-complet/blob/main/image007.png">

Dans l’écran principal de WLED, choisir :

<img src="https://github.com/wizbe/Wled-soundreactive-tutoriel-complet/blob/main/image008.png">

Puis

<img src="https://github.com/wizbe/Wled-soundreactive-tutoriel-complet/blob/main/image009.png">

Faire attention aux paramètres de niveau lumineux et de sensibilité du micro !

<img src="https://github.com/wizbe/Wled-soundreactive-tutoriel-complet/blob/main/image010.png">

Faire un peu de bruit ou mettre de la musique et la lumière devrait apparaître !
1. # Faire une sauvegarde de la configuration de base telle qu’illustrée ci-avant !


