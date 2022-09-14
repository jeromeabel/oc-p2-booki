# oc-p2-booki
Projet Booki : transformer une maquette en site web avec HTML &amp; CSS

Booki, une petite entreprise propose un outil de planification de vacances. Créer un prototype en intégrant la maquette en HTML et CSS.

## Livrable
- Zip : Dupont_Jean_1_code_012022.zip

1440px


## ❔ Diff
- Logo position
- Components - search bar : flex au lieu de position:absolute
- Components - filters btn : besoin de responsive, tailles, padding, font-size
- Components - card : flex au lieu de position:absolute
- Layout - accomodation : ?? flex au lieu de width %, gap au lieu de margin

## Méthodes
- Pixels : figma/measure, inkscape, pixel perfect extensions
- Inspecteur d'éléments
 
## Ressources
- Menu bar (ul li a) : https://dev.to/nicm42/links-inside-li-that-take-up-all-the-space-4c37, https://juliencrego.com/astuces/creer-un-menu-horizontal-simplissime-en-css/
- Google Fonts : https://developers.google.com/fonts/docs/getting_started, https://www.w3schools.com/css/css_font_google.asp
- Icones : https://www.w3schools.com/icons/icons_reference.asp, https://cdnjs.com/libraries/font-awesome
- Découper et intégrer une maquette : https://openclassrooms.com/fr/courses/3504431-decoupez-et-integrez-une-maquette, https://www.youtube.com/watch?v=_SEwzS1vG28
- Balises sémantiques : https://ronan-hello.fr/series/html/balises-semantiques-html
- Css selectors : https://www.w3schools.com/cssref/css_selectors.asp
- Flex : https://flexboxfroggy.com/#fr
- Normalize.css : https://www.hideout-lastation.com/using-normalize-css
- Meta : https://www.pierre-giraud.com/html-css-apprendre-coder-cours/meta-viewport/, https://developer.mozilla.org/fr/docs/Web/HTML/Viewport_meta_tag
- Box-sizing : https://la-cascade.io/articles/box-sizing-pour-les-nuls
- meta mnimal template : https://github.com/celine-m-s/metatags-101/blob/master/minimal_template
- https://www.abondance.com/20140627-14046-faut-il-integrer-les-balises-semantiques-schema-org-ses-pages.html
- flex : https://css-tricks.com/snippets/css/a-guide-to-flexbox/, https://la-cascade.io/flexbox-guide-complet/
- positionnement ! https://developer.mozilla.org/fr/docs/Web/CSS/position, https://openweb.eu.org/articles/initiation_absolue
- icon font awesome sur input submit : https://forum.freecodecamp.org/t/solved-adding-font-awesome-icons-to-an-input-button/74139/5
- overflow : https://developer.mozilla.org/fr/docs/Web/CSS/overflown https://www.alsacreations.com/tuto/lire/1038-gerer-debordement-contenu-et-cesures-css.html
- picture : picture : https://codepen.io/mahfoudh-arous/pen/VwXoVjM?editors=1000 
- on positionne avec flex, on finalise avec margin/padding
- Reporter les dimensions des éléments en px pour 1400px de large (avec figma et plugin Measure)
- Travailler les dimensions des élements en live avec l'extension chrome perfectpixel, l'affichage responsive et l'inspecteur
- https://stackoverflow.com/questions/1827965/is-putting-a-div-inside-an-anchor-ever-correct
- https://stackoverflow.com/questions/39955839/how-to-show-middle-of-image-in-div-using-css
- card : https://www.gekkode.com/developpement/realiser-une-carte-en-css-card-ui-css/, https://www.w3schools.com/howto/howto_css_cards.asp
- mosaic : https://www.quackit.com/css/flexbox/examples/, https://tobiasahlin.com/blog/common-flexbox-patterns/#masonry-or-mosaic


Structured Data Testing Tool : cherchez une page contenant des balises sémantiques et laissez Google vous afficher ce qu’il en a compris ;

Schema creator : créez vos premières balises sémantiques grâce à un formulaire qui vous affichera le code HTML correspondant. 

validator W3C html+css


# ❔ Questions


    /* ? ajouter une classe menu ou nav ul li a */



? tablette

? 1440px
? 375pix mobile
Logo paddint-left ?
nav centrage vertical ? pas pixel perfect padding: 55px 0; /* alignement vertical */
donner une taille à une image : pourquoi l'image est bizarrement coupée ?

responsive logo : 3x srcset

? boutons avec cercle icone qui passe devant : translateX ou overflow (notes techniques)?
Filtres - boutons - desktop & mobile (idem ?) : flex out+in, icone/cercle (dépasse légèrement avec overflow ? carré+padding), survol, attention à padding/margin

D'abord tout faire en html ? puis attenuer le css section par section ?

card hover ancre ? <a href="#" title="Ouvrir"><div></div><div></div></a>


image object-fit: contain + width:100% ou height:100% (horizontal/vertical)

popular : position étoile ? absolute ou div/flex encore ?

Trop de règles !!!
DRY ??

## GIT erreur quand je suis en terminal
emote: Support for password authentication was removed on August 13, 2021.
remote: Please see https://docs.github.com/en/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication.
fatal: Échec d'authentification pour 'https://github.com/jeromeabel/oc-p2-booki.git/'

## HTML
- Sections header : h2 tout seul ou dans un p ou dans une div ou dans un header
- Formulaire : balise form ou dans une div 
- Section hébergements populaires : section ou aside
- Footer : h2 ou p

## CSS
- Besoin de reset.css ?
- Google font : pourquoi aussi compliqué ? rel="preconnect" crossorigin
- Font awesome : cdn, kit ? Lien ne fonctionne pas :  https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@6.1.2/css/fontawesome.min.css
- * { box-sizing: border-box ; } ?
- id pour sections, même celles dans liens ?
- Unités px pour font, witdh, height, margin, padding ?
- header : menu horizontal avec image logo : trop compliqué ? Alternative avec inline-table ?
- header : menu image dans une div ?
- header : menu li : border top et bottom : 3px solid white ?
- header : aucuns changements pour tablette
- form : positionnement absolu/relatif nécessaire (juste pour le logo "loupe" mobile ?) ? ou flex + vertical-align + line-height ?
- form : noms en cascade ? filters__form__logo
- Responsive Tablets ?
- Césure du texte notamment h1 filters ?
- icone : carré réduire, padding