# Bibles Notes
- <u>Speaking languages supported :</u> `French FR`
- <u>Software supported :</u> `Obsidian`
- <u>Main files format :</u> `.md` (Markdown)
- <u>OS supported :</u>
  - Fully supported : `Linux`, `Windows`, `MacOS`
  - Partialy supported : `Android` (through a [Syncthing](https://syncthing.net/) setup with an external PC)
  - Should work but hasn't been tested yet : `iOS` (through an [iCloud](https://www.icloud.com/) setup sync with an external PC)
> Only **me** (which is **Zratex** or **Zratey** on Github) are allowed to force-push. Otherwise this repository will mainly be read-only. And the main reason is because it's my personal notes

The next sections of this `README.md` file will be in the supported languages listed above.
## Sommaire
- [Présentation du dépôt](#bibles-notes)
  - [Prélude](#prélude)
  - [Version de la Bible utilisée](#version-de-la-bible-utilisée)
  - [Remarques et Disclaimer](#remarques-et-disclaimer)
- [Utilisation du dépôt](#utilisation-du-dépôt)
  - [Installation](#installation)
  - [Modifier des notes](#modifier-les-notes)
  - [Mettre à jour le dépôt](#mettre-à-jour-le-dépôt)
## Prélude
Ce dépôt Git est un dépôt sur les notes que je prends sur l'étude de la Bible, prédications et enseignements que j'assiste.

Comme vous le remarquez, ce n'est pas un format de note habituel. C'est parce que j'utilise le logiciel de notes **[Obsidian](https://obsidian.md/)** pour faire des liens entre mes notes. De ce fait, si vous voulez utiliser ces notes à but personnel, il vous faudra installer le [même setup que moi](#installation).

J'avais envie que mes notes sur mon téléphone et sur mon PC soient liés. Cependant, puisse que c'est compliquer d'installer `Git` directement sur Android, je me suis retrouvé à devoir installer [syncthing](https://syncthing.net/). Ce système fonctionne super bien, en vrai je suis content, mais je me suis dit qu'il serait intéressant de réaliser un dépôt `Git` pour pouvoir synchroniser mes notes avec mes autres appareils, ainsi que pourquoi pas le partager à ceux qui seraient intéressés. Ce qui a mené à la création de ce dépôt Github
## Version de la Bible utilisée
La version française de la Bible que je vais majoritairement utiliser est la **BDS (Bible du Semeur 2015)**.

Parce que j'ai commencé à segmenter les extraits de la Bible par celle ci, mon système ne peut être changé vers une autre version. Donc pour tout doute vis à vis de ce que j'ai recopié, je vous invite donc à vous référer à cette version
## Remarques et Disclaimer
Etant moi même un Homme, je ne suis donc par définition pas parfait et faillible. De ce fait, il se peut qu'il y ait des coquilles qui aient pu se glisser, que ce soit par rapport au recopiage de la Bible ou la retranscription des prédications, et dans ce cas là je m'en excuse d'avance.

Cela implique 2 choses :
- Ne prenez pas absolument tous mes écrits comme la vrai vérité
- Si vous remarquez des erreurs, que ce soit d'orthographes, de phrases, de numérotation de chapitres/versets/libres ou même des erreurs dans les définitions et propos, n'hésitez pas à **me contacter et faire une Issue sur Github** pour que je puisse corriger cette chose
> Par conséquent, **les seuls écrits qui doivent être pris comme vérité absolue doivent seulement être la Bible**
# Utilisation du dépôt
## Installation
Pour un développeur c'est assez classique, mais je me dois de donner une explication pour ceux qui n'ont pas l'habitude.

Suivez ces étapes :
- **Créez un dossier sur votre machine** dédié au téléchargement du dépôt Git
- Pour le téléchargement du dépôt Git, 2 options s'offrent à vous :
  - Téléchargez ce dépôt sur l'interface web en format `.zip`, et décompressez le dans le dossier dédié que vous avez créé précédemment -> **/!\ Vous n'aurez pas les mises à jours du dépôt**
  - Initialisez un dépôt `Git` local en exécutant `git clone [URL du dépôt distant]`
    - L'installation de [Git](https://git-scm.com/downloads) sur votre machine est nécessaire
    - Il y a plusieurs manières d'executer la commande `git clone`, que ce soit directement avec la console de commande de [Git](https://git-scm.com/downloads), ou alors en appuyant sur les boutons dédiés sur l'interface graphique d'un logiciel tiers comme :
      - [VSC](https://code.visualstudio.com/)
      - [GitHub Desktop](https://desktop.github.com/)
      - [JetBrains Softwares](https://www.jetbrains.com/fr-fr/)
      - Et bien plus encore. Donc cherchez par vous même sur internet comment faire ça
- **Installez [Obsidian](https://obsidian.md/) sur votre machine**
  - [Optionnel] : Paramètrez Obsdian selon vos préférences. Normalement cela ne devrait pas affecter les notes qui ont été prises
- **Ouvrez avec Obsidian le dossier** `Notes christ` que vous avez précédemment téléchargé
  - Lors de l'ouverture, vous devez accepter ce que vous demandera Obsidian. Cela installera le plugin pour mettre à jour votre dépôt local, et avoir un tri de couleur comme le miens pour le graph.
- Enjoy!
## Modifier les notes

Si vous n'avez pas l'habitude d'utiliser un dépôt Git mais que vous voulez tout de même apporter des modifications, je vous conseil de copier coller le dossier `Notes christ` dans un autre dossier de votre ordinateur, pour éviter des conflits quand vous voudriez mettre à jour votre dépôt local au dépôt distant.

Ce n'est évidemment pas la seule solution, donc si vous vous y connaissez faites comme vous le souhaitez.

## Mettre à jour le dépôt
> Lisez le segment à propos des modifications avant de lire ceci

Lors du téléchargement de ce dépôt, dès que vous appuirez sur la touche `F5` de votre clavier sur Obsidian, votre dépôt local se mettra automatiquement à jour.

> Si vous rencontrez des messages d'erreurs, c'est parce que vous avez apporté des modifications à votre dépôt

# Voilà !
C'était tout ce dont vous aviez normalement besoin de savoir. Si vous avez un soucis, ou que vous remarquez une erreur dans le dépôt, n'hésitez pas à me contacter !
