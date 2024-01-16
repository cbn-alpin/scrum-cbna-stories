# scrum-cbna-stories
Ce dépôt sert à rassembler et organiser les stories du Scrum multi-projets du service SI du CBNA.

## Procédure

### Comment saisir un nouveau ticket ?
1. S'identifiez sur Github
1. Rendez-vous sur la [page de gestion des tickets de ce dépôt Github](https://github.com/cbn-alpin/scrum-cbna-stories/issues) et ouvrez un nouveau ticket (bouton "*New issue*").
1. Saisissez un titre court ("*Title*") et représentatif de la story
1. Saisissez une description plus détaillée sur le modèle: En tant que *utilisateur*, je peux *fonctionnalité* afin de *répondre à un besoin* en *comment*.
1. Dans la colonne de droite, sélectionnez un label de type **projet** préfixé par **p:**.
1. Sélectionner éventuellement d'autres labels.
1. Valider l'ajout de votre story avec le bouton "*Submit new issue*".

### Comment surveillez les nouvelles stories ?
1. S'identifiez sur Github
1. Se rendre sur [le dépôt cbn-alpin/silene-geonature](https://github.com/cbn-alpin/scrum-cbna-stories/)
1. Cliquer sur le bouton "Watch" en haut à droite de la page.


## Gestion des labels

Nous utiliserons les labels suivant :

- Type
- Projets
- Status
- Effort
- Audience
- Info

Il est possible de consulter le nombre de tickets associé à chaque label sur [la page dédiée](https://github.com/cbn-alpin/silene-geonature/labels). Cette page permet aussi d'accèder aux tickets liés à chaque label.

### Type [t] (#bfe5bf)

Permet d'indiquer le type de story.
Les labels disponibles sont :
- **t:fonctionnalite** : ajout d'une nouvelle fonctionnalité nécessitant du développement.
- **t:amelioration** : modification d'une fonctionnalité existante nécessitant du développement.
- **t:bug** : correction d'un mauvais fonctionnement nécessitant du développement.
- **t:tache** : modification/amélioration/travail ne nécéssitant aucun développement (paramètrages, rédaction, ...).

### Projets [p] (#c7def8)

Permet d'indiquer le projet concerné par la story :
- **p:sialp** : projet SIALP
- **p:shalp** : projet SHALP
- **p:sylvalp** : projet SYLVALP
- **p:resto** : projet Restauration du service Conservation.
- **p:floresent** : projet Flore Sentinelle et ces modules GeoNature.

### Statuts [s]

Permet d'indiquer l'état d'une story à un moment donné.
Les labels disponibles sont :
- **s:bloquant** (#e11d21): le problème décrit dans la story/ticket bloque le fonctionnement normal du système. Intervention immédiate nécessaire.
- **s:complement** (#b58a1e) : la story nécessite un complément d'information pour être traité.
- **s:discussion** (#fbca04) : le story nécessite un choix qui doit être discuté.

### Effort [e] (#d4c5f9)

Permet d'indiquer le temps nécessaire pour fermer le ticket. Une note de 1 (faible) à 3 (important).
Les labels disponibles sont :
- **e:0,5** : 0,5 point d'effort.
- **e:1** :  1 point d'effort.
- **e:2** : 2 points d'effort.
- **e:3** : 3 points d'effort.
- **e:5** : 5 points d'effort.
- **e:8** : 8 points d'effort.
- **e:12** : 12 points d'effort.
- **e:20** : 20 points d'effort.

### Audience [a]

Permet d'ajouter des informations concernant le type d'utilisateur concerné par le ticket.  


### Info [i]

Permet d'ajouter des informations complémentaires au ticket.  
Non utilisé pour l'instant.


## Gestion des Milestones

Nous utiliserons les millestones pour rassembler les tickets finis lors d'un sprint.
Le format des nom des millestones sera : "Sprint #<num> du <date-fin>". Ex.: "Sprint #1 du 2023-01-15".lonne dans le projet semble plus pratique pour gérer ce status de ticket. Nous n'utiliserons pas ce label.

## Sources
[How to manage a project using Github](http://blog.zot24.com/how-to-manage-a-project-using-github/)
