***********************************Ohmyfood-projet-4

Ohmyfood-projet-4 est un projet de site web de commande de repas en ligne, basé sur l'architecture 5-1 pour l'organisation des fichiers SCSS. Il met en avant l'utilisation de Sass pour faciliter le développement des styles, ainsi que différentes fonctionnalités techniques telles que les animations et le positionnement BEM dans les pages des restaurants.

***********************************Organisation du projet

Le projet est organisé en utilisant l'architecture 5-1, qui consiste en cinq dossiers principaux et un dossier partiel :

base/ : Contient les styles de base tels que la réinitialisation (_reset.scss), la typographie (_typography.scss), et d'autres styles communs utilisés à travers le site.
components/ : Contient les styles spécifiques aux différents composants de l'interface utilisateur. Les animations des boutons sont définies dans _buttons.scss, tandis que l'aspect des boutons est géré dans _icons.scss.
layout/ : Contient les styles liés à la structure globale de la page, tels que l'en-tête (_header.scss), le pied de page (_footer.scss), et le contenu principal des pages (_main-pages.scss).
pages/ : Contient les styles spécifiques à chaque page du site. Le fichier _index.scss gère les styles de la page d'accueil, tandis que _pages.scss est utilisé pour les autres pages.
utils/ : Contient des fichiers utilitaires tels que des mixins (_mixins.scss) et des variables (_variables.scss) utilisées à travers le projet.

**************************************Compilation des styles

Pour compiler les styles SCSS en CSS, tu peux utiliser différentes méthodes, telles que :

Live Sass Compiler (extension pour Visual Studio Code) :
Assure-toi d'avoir l'extension Live Sass Compiler installée dans Visual Studio Code.
Ouvre le fichier style.scss dans l'éditeur.
Clique avec le bouton droit de la souris dans l'éditeur et sélectionne "Watch Sass" pour démarrer la compilation automatique des fichiers SCSS en CSS.
Commande de ligne Sass :
Assure-toi d'avoir Sass installé sur ton système.
Dans le terminal, navigue jusqu'au répertoire du projet contenant les fichiers SCSS.
Utilise la commande suivante pour compiler les fichiers SCSS en CSS : sass input.scss output.css --watch.
Outils en ligne :
Il existe également des outils en ligne tels que SassMeister (https://www.sassmeister.com/) où tu peux coller ton code SCSS, le compiler et récupérer le CSS résultant.

******************************************Animation et positionnement BEM

Le projet Ohmyfood-projet-4 utilise des animations pour améliorer l'expérience utilisateur. Les animations des boutons sont spécifiées dans le fichier _buttons.scss du dossier components/. Le positionnement BEM (Block-Element-Modifier) est également utilisé dans les pages des restaurants pour organiser et structurer les différents éléments de l'interface.

N'hésite pas à explorer les différents fichiers SCSS du projet pour découvrir comment les animations, les styles et le positionnement BEM ont été implémentés dans chaque partie du site.

Note : Assure-toi d'avoir les dépendances nécessaires installées et les outils de compilation configurés avant de commencer à travailler sur le projet.