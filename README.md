# Bibles Notes
- Speaking languages supported : `French FR`
- Software supported : `Obsidian`
- Main files format : `markdown : .md`
- OS supported : `Linux`, `Windows`, `MacOS`
## Prélude
Ce dépôt Git est un dépôt sur les notes que je prends sur l'étude de la Bible.

Comme vous le remarquez, ce n'est pas un format de note habituel. C'est parce que j'utilise le logiciel de notes **[Obsidian](https://obsidian.md/)** pour faire des liens entre mes notes. De ce fait, si vous voulez utiliser à but personnel ces notes, il vous faudra installer le même setup que moi : explications plus bas dans ce `README`.

J'avais envie que mes notes sur mon téléphone et sur mon PC soient liés. Cependant, comme il n'est pas possible d'installer Git directement sur Android, je me suis retrouvé à devoir installé [syncthing](https://syncthing.net/). Ce système fonctionne super bien, en vrai je suis content, mais je me suis dit qu'il serait intéressant de réaliser un dépôt Git pour pouvoir le partager à ceux qui seraient intéressés.
> Seul **moi** (c'est à dire Zratex sur Github) sera authorisé à push
## Installation
Pour un développeur c'est assez classique, mais je me dois de donner une explication pour ceux qui n'ont pas l'habitude.

Suivez ces étapes :
- Créez un dossier sur votre ordinateur dédié au téléchargement du dépôt Git
- Pour le téléchargement du dépôt Git, 2 options s'offrent à vous :
  - Téléchargez ce dépôt sur l'interface web en format `.zip`, et décompressez le dans le dossier dédié que vous avez créé précédemment -> **/!\ Vous n'aurez pas les mises à jours du dépôt**
  - Initialisez un dépôt `Git` local en exécutant `git clone [URL du dépôt distant]`
    - L'installation de [Git](https://git-scm.com/downloads) sur votre machine est nécessaire
    - Il y a plusieurs manières d'executer la commande `git clone`, que ce soit directement avec la console de commande de [Git](https://git-scm.com/downloads), ou alors en appuyant sur les boutons dédiés sur l'interface graphique d'un logiciel tiers comme :
      - [VSC](https://code.visualstudio.com/)
      - [GitHub Desktop](https://desktop.github.com/)
      - [JetBrains Softwares](https://www.jetbrains.com/fr-fr/)
      - Et bien plus encore. Donc cherchez par vous même sur internet comment faire ça
- Installez [Obsidian](https://obsidian.md/) sur votre machine
  - [Optionnel] : Paramètrez Obsdian selon vos préférences. Normalement cela ne devrait pas affecter les notes qui ont été prises
- Ouvrez avec Obsidian le dossier `Notes christ` que vous avez précédemment téléchargé
- Enjoy!
## Modifier les notes

Si vous n'avez pas l'habitude d'utiliser un dépôt Git mais que vous voulez tout de même apporter des modifications, je vous conseil de copier coller le dossier `Notes christ` dans un autre dossier de votre ordinateur, pour éviter des conflits quand vous voudriez mettre à jour votre dépôt local au dépôt distant.

Ce n'est évidemment pas la seule solution, donc si vous vous y connaissez faites comme vous le souhaitez.

## Mettre à jour le dépôt
> Lisez le segment à propos des modifications avant de lire ceci

Pour mettre à jour de dépôt, assurez vous que vous n'avez réalisé aucunes modifications.

Ensuite, il existe 2 méthodes pour mettre à jour votre dépôt :
#### Via Git bash
Ensuite, avec le même outil où vous avez initialement réalisé la commande `git clone` pour récupérer mes notes sur votre machines, executez la commande `git pull` (Si vous utilisez un logiciel dédié, cherchez sur internet comment **pull** avec votre logiciel)
#### Via Obsidian
- Installez le plugin `Obsidian Git` dans les plugins communautaires (accessible depuis les paramètres du logiciel)
- Activez le plugin
- Allez dans la catégorie "Hotkeys" dans les paramètres d'Obsidian
- Dans la barre de recherche, cherchez `pull`
- Attribuez une touche à cette commande en appuyant sur le bouton **+** : pour moi par exemple c'est `F5`
- Pressez votre touche, et sélectionnez `origin` puis ensuite `origin/main` pour mettre à jour votre dossier

Désormais, à chaque vous que vous voudriez mettre à jour votre dépôt, il vous suffira d'appuyer sur votre bouton de prédilection.
> Si vous rencontrez des erreurs, c'est parce que vous avez apporté des modifications à votre dépôt

# Voilà !
C'était tout ce dont vous aviez normalement besoin de savoir. Si vous avez un soucis, ou que vous remarquez une erreur dans le dépôt, n'hésitez pas à me contacter !