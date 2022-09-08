# ❔ Questions

? tablette

? 1440px
? 375pix mobile
Logo paddint-left ?
nav centrage vertical ? pas pixel perfect padding: 55px 0; /* alignement vertical */
donner une taille à une image : pourquoi l'image est bizarrement coupée ?


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
- header : Menu horizontal avec image logo : trop compliqué ? Alternative avec inline-table ?
- header : menu image dans une div ?
- header : menu li : border top et bottom : 3px solid white ?
- header : aucuns changements pour tablette
- form : positionnement absolu/relatif nécessaire (juste pour le logo "loupe" mobile ?) ? ou flex + vertical-align + line-height ?
- form : noms en cascade ? filters__form__logo
- Responsive Tablets ?
- Césure du texte notamment h1 filters ?
- icone : carré réduire, padding