# learning-sass

# SASS
Le SASS (extension de fichier: scss ) est un outil de développement *frontend*, qui génère du css à partir d'un langage fait de CSS "amélioré". En rédigeant tes stylesheets en sass plutôt que directement en CSS, tu bénéficies de trucs sympas pouvant **diminuer ton temps de travail** (ton syndicat sera content), rendre ton **code plus réutilisable** d'un projet à l'autre (ton boss sera content), plus lisible aussi, grâce notamment à une syntaxe améliorée, à l'utilisation de **fonctions** (appelées des "mixin") et de **variables** (appelées des "variables". Ben oui).

Durée estimée de ce parcours : 1 journée.

## Initialisation
- [Slides d'intro au SASS](https://docs.google.com/presentation/d/1GFK1HjajFu8Hc3rLt9iIiv9hrgcVEEvTnFQmEporFxk/edit#slide=id.g35ed75ccf_057)
- official site: http://sass-lang.com 


## Setup
Pour faire du SASS, tu as besoin d'un logiciel qui tourne sur ta machine de développement, et qui va "observer" les fichiers sass. A chaque sauvegarde, le fichier css correspondant sera re-généré.

Voici quelques applications (gratuites et payantes): http://sass-lang.com/install

## Parcours 
- Crée un repos `learning-sass`
- Crée un fichier html basique `index.html`, histoire d'expérimenter avec sass.
- Crée un dossier `assets` pour y mettre tout fichier statique composant l'aspect visuel de ton interface: images, css, javascript... et fichiers sass (se terminant par .scss). A l'intérieur de ce dossier, crée un dossier pour chaque type de 
- Note que cette structure de dossier "assets" est conseillée simplement par le fait qu'elle est devenue une forme de convention chez les *frontend developers*. Libre à toi de t'en écarter, si tu aimes réinventer la roue.
- Crée un fichier `assets/scss/style.scss`  et configure ton application sass pour qu'elle génère le fichier  `assets/css/style.css` à chaque fois que le fichier "source" (style.scss) est modifié.
- Assure-toi que ton fichier html est bien lié à ton fichier css (et non au fichier scss).
