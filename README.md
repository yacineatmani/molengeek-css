# molengeek-css
Introduction
Qu’est-ce que les CSS ?
Le langage CSS est destiné à gérer le contenu et la structure d’une page web. Il est techniquement possible de faire de la mise en forme en HTML, mais les possibilités restent très limitées. Le langage CSS est donc là pour étendre considérablement les possibilités graphiques.

Le sigle CSS signifie Cascading Style Sheet autrement dit en français, feuille de styles en cascade. Cela indique bien que les CSS permettent de styler, de mettre en forme une page web. Le mot cascade, quant à lui, fait référence à une notion importante que l’on appelle l’héritage et sur laquelle nous reviendrons plus en détail dans la suite de ce cours.

Si vous utilisez les styles sur un logiciel de traitement de texte et/ou de PAO, vous verrez que les similarités sont nombreuses.

CSS va donc nous permettre de gérer la mise en forme du contenu d’une page. Nous allons pouvoir mettre en forme le texte (couleur, taille, graisse, casse, etc.) mais CSS va également nous permettre de dimensionner et positionner tous les éléments dans la page web et même de gérer des animations.

Quels avantages pour le développement ?
Il est aujourd’hui impensable de ne pas utiliser des CSS pour la mise en forme d’une page web tellement les avantages sont nombreux :

Rapidité de mise en forme : la mise en forme étant traitée par lot (par exemple tous les titres <h1> du document), le travail est donc considérablement plus rapide que lorsque l’on effectue de la mise en forme directe en HTML.
Facilité de mise à jour : sur le même principe de traitement par lot, il n’est pas nécessaire de reprendre tous les éléments dont on souhaite mettre à jour la mise en forme mais uniquement le CSS correspondant.
Possibilités graphiques : les possibilités de mise en forme en HTML sont extrêmement pauvres par rapport à celles offertes par le langage CSS.
Lisibilité du code : le code HTML sera plus léger et donc beaucoup plus lisible sans le verbiage de la mise en forme directe.
Les principes du langage CSS
Séparation de la forme et du contenu
Le premier principe est au cœur de la philosophie des styles. Il s’agit de distinguer clairement le code correspondant au contenu (structure de la page, texte de la page, sémantique) du code correspondant à la mise en forme (couleurs, positionnement). Ces deux aspects étant gérés respectivement par les langages HTML et CSS.

Le projet  CSS Zen Garden est un bon moyen pour illustrer ce principe. L’idée de ce site est de proposer aux internautes d’effectuer la mise en page d’une page web fournie en utilisant uniquement CSS. Il est donc interdit de modifier le code HTML. Ainsi, les trois pages web pour lesquelles vous avez un aperçu ci-dessous ont toutes les trois exactement le même code HTML et se distinguent donc uniquement par leur code CSS (ainsi que des images ajoutées via CSS).
