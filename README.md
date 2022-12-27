# Wled-soundreactive-tutoriel-complet
Tutoriel complet en français pour la configuration de WLED sound reactive avec un panneau LED (plans &amp; objets inclus)

Installation de base du panneau



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


