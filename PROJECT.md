# PROJECT

## Coding Rules
- Évitez de mixer les deux langues.
- Préférez l’utilisation des pixels pour les margins, les paddings et les pourcentages pour les widths.
- Utiliser les pixels et les pourcentages plutôt que les REM et les EM
- Naming Kebab case : .main-wrapper
- Privilégier Flexbox
- Il est important qu’aucun élément ne soit coupé, et que le texte ait une taille suffisante
- Breakpoints : 992 px pour les écrans d’ordinateurs et 768 px pour les tablettes

## ✅ Done
- [x] Création d'un dépôt sur github
- [x] VSCode + extensions vscode : auto rename tag, html end tag label, indent rainbow
- [x] Installation de l'extension Pixel Perfect sur Chrome
- [x] Mise en place de l'arborescence  : index.html, css/*.css, images/*.jpg
- [x] index.html : balises meta charset, viewport, description, open graph
- [x] index.html : liens css (normalize, google font, font awesome, styles.css, responsive)
- [x] Découpage desktop-first en .svg, .png
- [x] Découpage avec figma (plugin Measure) pour 1440px
- [x] Découpage mobile en .svg et .png : changements / desktop
- [x] Intégration HTML balises sémantiques
- [x] Création des trois profils dans les DevTools : desktop, tablet, mobile
- [x] Header - desktop : flexbox, blue border
- [x] Header - tablet & mobile
- [x] Création d'un fichier "components.html" pour tester les widgets
- [x] Components - search bar - desktop & tablet & mobile (display:none, border-radius, position absolute VS translateX())
- [x] Components - filters btn (flex in & out, margin/padding px, pas besoin responsive, partie gauche dépasse, :hover)
- [x] Components - filters icone infos
- [x] Layout Filters - desktop
- [x] Layout Filters - tablet & mobile
- [x] Components - accomodations card : taille fixe possible, image (border-radius), hover, cliquable
- [x] Components - popular accomodations card : idem
- [x] Layout Accomodations - desktop
    - [x] deux conteneurs 2/3 et 1/3, flex et %
    - [x] ajouter cartes dans chaque conteneur
- [x] Layout Accomodations - tablet & mobile : ordre, couleurs de fond
- [x] Components - activity card : position:absolute, object-fit:cover
- [x] Layout Activities - desktop : conteneur / activité + classe (hauteur)
- [x] Layout Activities - tablet & mobile
- [x] Layout Footer - desktop
- [x] Layout Footer - tablet & mobile
- [x] Fix card with a, flex accomodations
- [x] Images (responsive) "le format le plus adapté par rapport à la résolution et au temps de chargement."
- [x] Compatible pour Chrome et Mozilla
- [x] Validations W3C HTML et CSS : warning sections/header


## ❔ Questions

D'abord tout faire en html ? puis attenuer le css section par section ?

### GIT erreur quand je suis en terminal
emote: Support for password authentication was removed on August 13, 2021.
remote: Please see https://docs.github.com/en/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication.
fatal: Échec d'authentification pour 'https://github.com/jeromeabel/oc-p2-booki.git/'

### HTML
- Sections header : h2 tout seul ou dans un p ou dans une div ou dans un header
- Formulaire : balise form ou dans une div 
- Section hébergements populaires : section ou aside
- Footer : h2 ou p

### CSS
- Besoin de reset.css ?
- Google font : pourquoi aussi compliqué ? rel="preconnect" crossorigin
- Font awesome : cdn, kit ? Lien ne fonctionne pas :  https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@6.1.2/css/fontawesome.min.css
- * { box-sizing: border-box ; } ?
- id pour sections, même celles dans liens ?
- Unités px pour font, witdh, height, margin, padding ?
- header : Menu horizontal avec image logo : trop compliqué ? Alternative avec inline-table ?
- header : menu image dans une div ?
- header : menu li : border top et bottom : 3px solid white ?
- header : aucuns changements pour tablette
- form : positionnement absolu/relatif nécessaire (juste pour le logo "loupe" mobile ?) ? ou flex + vertical-align + line-height ?
- form : noms en cascade ? filters__form__logo
- Responsive Tablets ?
- Césure du texte notamment h1 filters ?
- icone : carré réduire, padding


## Resources
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
- flex : https://css-tricks.com/snippets/css/a-guide-to-flexbox/, https://la-cascade.io/flexbox-guide-complet/, https://1linelayouts.glitch.me/, froggy
- positionnement ! https://developer.mozilla.org/fr/docs/Web/CSS/position, https://openweb.eu.org/articles/initiation_absolue
- icon font awesome sur input submit : https://forum.freecodecamp.org/t/solved-adding-font-awesome-icons-to-an-input-button/74139/5
- overflow : https://developer.mozilla.org/fr/docs/Web/CSS/overflown https://www.alsacreations.com/tuto/lire/1038-gerer-debordement-contenu-et-cesures-css.html
- picture  : https://codepen.io/mahfoudh-arous/pen/VwXoVjM?editors=1000, https://web.dev/learn/design/picture-element/
- on positionne avec flex, on finalise avec margin/padding
- Reporter les dimensions des éléments en px pour 1400px de large (avec figma et plugin Measure)
- Travailler les dimensions des élements en live avec l'extension chrome perfectpixel, l'affichage responsive et l'inspecteur
- https://stackoverflow.com/questions/1827965/is-putting-a-div-inside-an-anchor-ever-correct
- https://stackoverflow.com/questions/39955839/how-to-show-middle-of-image-in-div-using-css
- card : https://www.gekkode.com/developpement/realiser-une-carte-en-css-card-ui-css/, https://www.w3schools.com/howto/howto_css_cards.asp
- mosaic : https://www.quackit.com/css/flexbox/examples/, https://tobiasahlin.com/blog/common-flexbox-patterns/#masonry-or-mosaic
- Structured Data Testing Tool : cherchez une page contenant des balises sémantiques et laissez Google vous afficher ce qu’il en a compris ;
- Schema creator : créez vos premières balises sémantiques grâce à un formulaire qui vous affichera le code HTML correspondant. 
- https://validator.w3.org/
- https://jigsaw.w3.org/css-validator/
