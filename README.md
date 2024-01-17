# scrum-cbna-stories
Ce dépôt sert à rassembler et organiser les stories du Scrum multi-projets du service SI du CBNA.
Il est en lien avec le projet [Scrum CBNA SI](https://github.com/orgs/cbn-alpin/projects/12).

## Procédure

### Comment saisir un nouveau ticket ?
1. S'identifiez sur Github
1. Rendez-vous sur la [page de choix d'un modèle de ticket de ce dépôt Github](https://github.com/cbn-alpin/scrum-cbna-stories/issues/new/choose) et choisir "Story" en cliquant sur le bouton `Get started`. 
1. Remplir le modèle de story. Obligatoirement la section "But".
1. Dans la colonne de droite, sélectionnez un label de type **projet** préfixé par **p:**.
1. Sélectionner éventuellement d'autres labels.
1. Associer la story au Projet "*Scrum SI CBNA*"   
1. Valider l'ajout de votre story avec le bouton `Submit new issue`.

### Comment surveillez les nouvelles stories ?
1. S'identifiez sur Github
1. Se rendre sur [le dépôt cbn-alpin/silene-geonature](https://github.com/cbn-alpin/scrum-cbna-stories/)
1. Cliquer sur le bouton `Watch` en haut à droite de la page.


## Gestion des labels

Nous utiliserons les labels suivant :

- Type
- Projets
- Info
- Audience

Il est possible de consulter le nombre de tickets associé à chaque label sur [la page dédiée](https://github.com/cbn-alpin/scrum-cbna-stories/labels). Cette page permet aussi d'accèder aux tickets liés à chaque label.

Les informations de type "Status" et "Effort" sont disponibles via les champs personnalisables du projet "*Scrum SI CBNA*".

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

### Info [i]

Permet d'ajouter des informations complémentaires au ticket :  
- **i:bloquant** (#e11d21): le problème décrit dans la story/ticket bloque le fonctionnement normal du système. Intervention immédiate nécessaire.
- **i:complement** (#b58a1e) : la story nécessite un complément d'information pour être traité.
- **i:discussion** (#fbca04) : le story nécessite un choix qui doit être discuté.

### Audience [a]

Permet d'ajouter des informations concernant le type d'utilisateur concerné par le ticket.  


## Gestion des Milestones

Nous utiliserons les millestones pour rassembler les tickets finis lors d'un sprint durant la retrospective.
Le format des nom des millestones sera : "Sprint #<num> du <date-fin>". Ex.: "Sprint #1 du 2023-01-15".

## Sources
[How to manage a project using Github](http://blog.zot24.com/how-to-manage-a-project-using-github/)
