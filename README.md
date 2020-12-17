# Exercice WorkFlow Git et Processus équipe

### Principe

Vous êtes les lutins qui vont préparer les commandes du père noël.
Chez les lutins, pas de chef, la clef c'est la motivation, la responsabilité partagée,
l'engagement et la qualité du travail bien fait.
Le père noël est là pour être facilité le travail des lutins et les aider dans
ce processus de construction de cadeau de préparatif de noël.

### Buts et objectifs

Le but de l'exercice est de travailler sur la manipulation de Git.
On va s'abstraire de la technique afin de se focaliser sur des problèmatiques de
travail en équipe. On va travailler sur le workflow Git, les pull requests et le management
visuel des taches à faire.
Nous allons travailler via GitHub, avec les tableaux de type "Projet"

### Les taches des lutins

Les taches des lutins se découpent en différentes étapes:

##### Lecture du courrier
Les lutins doivent lire le courrier des enfants afin de récupérer le besoin,
comprendre les envies et lister l'ensemble des différents cadeaux à faire
pour satisfaire la lettre. Les lettres arrivent progressivement avant noël.

##### La construction des jouets
Après avoir compris les spécifications des jouets, les lutins construisent les
jouets demandés.

##### Emballage des jouets
Les lutins vérifient que les jouets sont cohérents. Si c'est le cas, ils emballent
le cadeau. Après avoir emballé les cadeaux, on ne peux plus modifier le jouet.

##### Rassemblement dans le sac
Les lutins regroupent les différents jouets d'une lettre et les mettent dans un sac
afin que le père noêl puisse descendre dans la cheminée avec uniquement les jouets
de la personne de la lettre.

##### Empaqueter dans le traineau
Chaque sac de jouet doit être trié par rapport à la ville de destination, afin de faciliter
le père noël pour retrouver rapidement ces sacs pendant le jour de noël. Ainsi

##### Asynchronisation et priorisation des taches
Le travail d'équipe est important pour les lutins, tout le monde met la main dans le cambouie.
Tout le monde travail sur toutes les taches.
Chaque lettre sera priorisé par leur ordre d'arrivée. On priorisera le fait de terminer une
lettre avant de commencer une nouvelle.
Le meilleur moyen de vérifier que le travail est bien fait, c'est de vérifier à plusieurs.
Pour un jouet donné, chaque tache devra être fait par un lutin différent.

### Mise en place

On va travailler sur git, via le site GitHub. On va partager un repository.
On va travailler tout ensemble sur le même repository.

La branche master est l'image de l'existant.
A chaque tache, on devra construire une branche, un push et une pull request.
Il est INTERDIT de travailler directement sur la branche master.

Chaque pull request devra être validé par au moins une personne.

### Détails: Lecture du courrier

Les lettres des enfants arrivent sur le dossier boite_aux_lettres.
Dans chaque lettre, on a le prénom, l'age et la ville de l'enfant.
On a aussi la liste des cadeaux que l'enfant désirent.

Le lutin qui lie une lettre doit trouver les informations de la lettre
et découper cette lettre avec les différentes taches à faire. Il devra mettre à jour
le tableau des taches, en rajoutant les nouvelles taches.

### Détails: La construction des jouets

La construction d'un jouet sera matérialisé par un fichier. Ce fichier se trouvera dans
le dossier atelier_jouet.
Il faudra décrire l'ensemble des actions nécessaire afin de construire ce jouet.
Pour construire un jouet, il faut suivre les instructions se trouvant dans les manuels.
La construction des jouets peuvent varier par rapport au prénom, à l'age et à la ville
de l'enfant.

Les manuels ont été écrits par des lutins, ce qui ne veut pas dire qu'ils ne sont pas
forcément clairs et facile à comprendre.
Comme une recette de cuisine, il y a le matériel neccessaire et les étapes de la fabrication.
Certaines fabrications sont farfelues, la position des mots du fichier peut avoir
une importance.

### Détails: Emballage des jouets

Des que le jouet est construit, un lutin doit l'emballer. Il doit déplacer le jouet
de l'atelier du jouet (dossier "atelier_jouet") à l'atelier d'emballage
(dossier "atelier_emballage")

Le lutin emballe le jouet en rajoutant un carrée de caractère autour des instrctions
de la construction du jouet. Il faut au moins 3 caractères différents pour faire
cette emballage, les caractères doivent chaque fois varier.

IL EST INTERDIT DE FAIRE UN EMBALLAGE AVEC UNE ASSOCIATION DE CARACTERES QUI A DEJA
ETE FAITE.

### Détails: Rassemblement dans le sac

Des que tous les jouets d'un enfant sont emballés, on les met dans un sac.
Un sac est un fichier qui rassemble l'ensemble des cadeaux emballés d'un enfant.

Pour mettre un jouet dans un sac, la donnée du fichier de jouet se trouvant
dans l'atelier d'emballage se met dans le fichier du sac. Le fichier de l'atelier
est ensuite supprimé.

### Détails: Empaqueter dans le traineau

Il reste à mettre le sac dans le traineau. Le traineau se trouve dans l'hangar, via
le fichier "traineau.txt".

Le traineau a différents étages de cadeau. Chaque étage doive être à peut prêt
équilibré au niveau poid et espace afin que le traineau soit stable. Du coup
On ne peux pas avoir une différence de 2 avec le nombre de sac par étage.

Chaque sac doit être ordonné dans le traineau afin de faciliter la livraison des
cadeaux le jour J de noël.

Le père noel va livrer en premier les sacs qui se trouvent au dessus du traineau
(étage 4 puis étage 3 puis ...).

Les sacs doivent être trié par continent (Amérique -> Afrique -> Europe
-> Océanie -> Asie). Pour chaque continent, les sacs doivent être ensuite être
trié par ville, par ordre alphabétique.






