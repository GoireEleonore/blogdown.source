# Source pour mon site web professionnel

Ceci est la source [blogdown](https://bookdown.org/yihui/blogdown/) pour construire https://GoireEleonore.github.io avec [hugo](https://gohugo.io) dans le dépôt Github `GoireEleonore.github.io`.


## Procédure

(remplacer `GoireEleonore` par votre propre login Github)

- Faites un `Fork` du dépôt

- Clôner le dépôt `blogdown.source`dans le dossier **projects**

- Créer sur Github (https://github.com) un nouveau dépôt qui **doit** s'appeler `GoireEleonore.github.io`

- Le clôner également dans le dossier **projects**

- Ouvrir le projet `blogdown.source` dans RStudio

- Faire une recherche de toutes les occurences des trois mots suivants à remplacer dans tous les fichiers (`Edit -> Find in Files...`):
    * GoireEleonore, à remplacer par votre login Github
    * ELEONORE à remplacer par votre prénom
    * GOIRE à remplacer par votre nom de famille

- Aller dans les **Addins** de RStudio et lancer celui qui s'intitule `Serve Site`dans la section `BLOGDOWN`... Votre site doit apparaitre.

- Commitez vos changements dans `blogdown.source` dans l'onglet `Git` lorsque vous êtes satisfait de vos modifications.

- Commitez votre site depuis `GoireEleonore.github.io` (vous pouvez le faire très facilement depuis Github Desktop) 

- Editez votre site en commençant par `content -> post -> getting-started.md` puis `content -> project -> getting-started.md`

- Faites un `Commit` et `Push` de vos changements dans `blogdown.source` 

- Faites un `Commit` et `Push`  de votre site depuis `GoireEleonore.github.io` (vous pouvez le faire très facilement depuis Github Desktop)

- Vérifiez que votre site est bien en ligne en allant voir à l'adresse `https://GoireEleonore.github.io` depuis votre navigateur web préféré... et contemplez le résultat!
