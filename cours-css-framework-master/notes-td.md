# Bootstrap

Il est issu du travail des équipes de Twitter et est certainement le premier framework CSS à s'imposer. Il en est à sa version 4 qui est actuellement en bêta et sur laquelle nous nous essaierons. Il fonctionne avec deux fichiers bien distincts : ses modules CSS, qui correspond à sa base, et ses modules javascripts, qui sont optionnels. Leur inclusion dans une page est très simple : il suffit soit de les intégrer directement dans le head et body de votre HTML à travers leur liens vers des hébergeurs centralisés, ou bien il suffit de les copier dans votre dossier de travail et de faire un lien relatif vers eux.

A noter que le javascript de bootstrap en version 4 nécessite l'inclusion de deux autres librairies pour le faire tourner : jQuery et Popper. jQuery est sans aucun doute la plus vieille librairie en javascript à être encore mise à jour aujourd'hui. Nous en reparlerons à la fin de notre cours sur les applications web.

## Le système de grille

Le système de grille se base sur deux fondamentaux : un système de conteneur qui s'adapte à la taille de l'écran, un système de colonne.

Le système de colonne fonctionne comme suit : l'espace du conteneur est divisé en 13 bornes et donc 12 intervalles sur lesquelles les colonnes réelles demandées par l'utilisateur se figent.

## Quelques éléments pratiques

Pour utiliser bootstrap, il n'y a pas de miracle : il faudra lire la documentation. Je ne peux pas lire cet ensemble pour vous et bien qu'il puisse être utile de naviguer sur le site de bootstrap pour en découvrir les différents objets, il est certain qu'il vous faudra souvent revenir sur le site et regarder leur documentation.

Je vais cependant vous présenter quelques objets.

### Les tables

L'un des objets les plus pratiques car leur design est bien fait est l'objet table de bootstrap. Il propose plusieurs classes de bases dont .table-bordered qui introduire une belle bordure pour les lignes du tableau.

Les seuls paramètres à fournir ici à votre html serait donc les classes table et table-bordered

### Les figures

Les images ont un ensemble de classes plutôt pratiques, allant de classes permettant d'adapter automatiquement les images en largeur à la classe .rounded-circle qui permet de découper une image en cercle.

Ici, on note l'exemple de l'utilisation de balises sémantiques HTML5 pour la description d'une figure et les classes CSS fournies par Bootstrap. La classe `.img-fluid` adapte la taille de l'image en largeur, `rounded` arrondi ses angles. `text-right` aligne le texte à droite. Les autres classes permettent de faire fonctionner l'ensemble.

### Les boutons

Les classes de boutons permettent de réaliser de sympathiques interfaces d'application et de site web en général. Elles sont disponibles à la fois pour des objets de type button en html et pour des liens (donc des balises `<a>`).

On remarque l'utilisation constante de la class `btn` puis d'une classe qui spécialise son aspect.

### Les formulaires

https://getbootstrap.com/docs/4.0/components/forms/

Enfin, je tiens à attirer l'attention sur les composants de formulaires qui sont très variés et extrêmement utiles. Par exemple, il est très facile de faire avec bootstrap des formulaires alignés horizontalement.

### Exercice 1

Le faire ensemble, recopier les fichier, faire un dossier correction dans le repository git. Jouer avec la taille de la fenêtre et conteneur fluid ou fixe.

### Exercice 2-5

En solo, possibilité de correction par email.