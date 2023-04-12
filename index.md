[Accéder à mes TP 3 et 5](https://github.com/ydroo/tp3).

# TP 5 : Comment créer un site Web sur GitHub pages

## Lors de ce tp5 nous avons abordé : 

1.  Créer un site Web pour un référentiel existant
2.  Ajouter du contenu à l’aide de Markdown et HTML
3.  Créer un site Web pour la SAE 2.03

##  Compte rendu TP 5: 

* Pour importer un "style" Jekyll (ici Cayman) :

remote_theme: pages-themes/cayman@v0.2.0
plugins:
- jekyll-remote-theme # add this line to the plugins list if you already have one

* Pour avoir un site comme celui-ci, il faut mettre notre répertoire distant (ici tp3) en **public**
* On se rend ensuite dans le menu "Pages" et on commence à paramétrer notre futur site.
* On choisit la branche sur laquelle le site va se baser (gh-pages sera le plus courant pour la suite de nos projets)

Une fois tout cela fini, un ou deux fichiers entrent en jeu :
- **\_config.yml**
- index.md

Ce dernier n'est pas nécessaire, notre page se basera alors sur un autre md, un README.md par exemple.
Le config.yml nous permettra d'importer un thème à notre page, la rendant personnalisée et donc différente des autres. Ce fichier est l'équivalent d'un canevas d'un style.css bien élaboré.

> Chaque modification de page peut prendre du temps avant de prendre forme ! Il faudra surement attendre 10 minutes par exemple pour que la page GitHub apparaisse, le site au début ne sera pas reconnu.

### Mon équipe 14 pour cette SAE :

| Prénom       | Nom               | Groupe |
|:-------------|:------------------|:-------|
| Trystan      | Baillobay         | B      |
| Maxime       | Lemoine           | B      |
| Mattéo       | Sa                | B      |

