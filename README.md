# Créer des îcones facilement avec iconmoon

[https://lucilev.github.io/icones/](https://lucilev.github.io/icones/)

[icomoon.io](icomoon.io)



![icomoon](https://i1.wp.com/www.tidev.io/wp-content/uploads/2014/03/icomoon-featured.jpg?fit=720%2C340)
 * Il y a *5500 icones gratuites* pour animer vos sites.
 * Mais surtout créez vos propres icones vectorielles: Il est très facile d’en changer la taille et la couleur en CSS car cela revient à charger une font. (Exemple : logo Be-code). Les zones « blanches » du logo doivent être sur fond transparent.
 Comme à votre habitude, pour changer la taille, utiliser : font-size et pour changer la couleur de fond : background-color.


## Attention : Utiliser une image SVG uniquement
Si vous n'utilisez pas Illustrator, il existe des convertisseurs de formats (exemple [https://image.online-convert.com/fr/convertir-en-svg](https://image.online-convert.com/fr/convertir-en-svg) )

Soit on utilise l'application en ligne, accessible sur la home du site.
On télécharge le pack généré avec la nouvelle icone sur son site comme une librairie.

Ou on utilise le lien au CSS en ligne, type : link rel="stylesheet" href="https://i.icomoon.io/public/temp/5367053304/UntitledProject/style.css

#### Exemple de balise Iconoom: < span class="icon-ico_Becode icon10 CornflowerBlue iconBlanche >

Acticle sur [alsacreations.com](https://www.alsacreations.com/tuto/lire/1547-police-font-icone-vectorielle-webdesign.html)

---------------------------------------------------------------------------------
## Librairies d'îcones vectorielles
![font-awesome](https://www.vectorlogo.zone/logos/font-awesome/font-awesome-card.png)
Vous trouverez facilement différents packs d’icônes comme [Font Awesome](http://fontawesome.io/) mais également en créant votre propre pack en piochant dans d’autres librairies sur [Fontello](http://fontello.com/). Dans ces deux cas il vous suffira de récupérer les polices créées et copier/coller la classe de l’icône que vous souhaitez utiliser.


#### Exemple de balise FontAwsome : < i class="fa fa-camera-retro fa-5x" >


---------------------------------------------------------------------------------
# Utiliser une font personnalisée
![Dafont](https://www.dafont.com/img/dafont.png)
Nous ne sommes plus limités aux polices disponibles sur les ordinateurs. Nous pouvons choisir une autre typographie dans la mesure ou elle est libre de droits ou achetée.

Vous trouverez un tas de fonts et d'inspiration ici:
[https://www.dafont.com/fr/](https://www.dafont.com/fr/) (attention aux droits)
[Google font](https://fonts.google.com/) (gratuit)


Importer la font choisie dans le *"GENERATOR"*
[https://www.fontsquirrel.com/](https://www.fontsquirrel.com/)
Puis télécharger le kit généré et coller-le dans le dossier "font" de votre site.
Ajouter le link jusqu'à cette nouvelle font et modifier le CSS en ajoutant en haut :

#### Exemple: 
     > @font-face {
     >       font-family: 'enchanting_celebrations';
     >       src: url('fonts/enchanting_celebrations-webfont.woff2') format('woff2'),
     >            url('fonts/enchanting_celebrations-webfont.woff') format('woff');
     >       font-weight: normal;
     >       font-style: normal;
     >
     >    }

Ensuite ajouter la *font-family* à la balise que vous souhaitez modifier :
#### Exemple:      
     >  H1 {
     >       font-family: 'enchanting_celebrations';
     >      }


Have fun!
