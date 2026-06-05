## Explorer des alternatives .[fade-in fade-out hide-title]

Ces alternatives correspondent dans l'ordre aux points du contexte

<nav class="breadcrumbs">
  <a class="">Poser la question</a>
  <a class="">Clarifier le contexte</a>
  <a class="is-active">Explorer des alternatives</a>
  <a class="">Etudier ces alternatives</a>
  <a class="">Converger vers la décision</a>
  <a class="">Ecrire une décision claire</a>
  <a class="">Se préparer aux conséquences</a>
</nav>

/*

{Logan} Ça c'est la partie un peu créative que j'affectionne.

{Logan} C'est là qu'il va falloir imaginer des solutions qui respectent l'ensemble des éléments qui contraignent la décision d'architecture en utilisant une technique de l'entonoir.

{Logan} Une phrase que je répète souvent, c'est : "NE RIEN FAIRE EST TOUJOURS UNE OPTION".

{Logan} Ne rien faire est souvent une option négligée et pourtant viable dans certains cas.

{Logan} Ça permet de mettre en évidence les "risques à ne pas faire".

{Logan} **TRANSISTION** Si on reprend l'exemple de ton besoin de stocker de l'information, tu explorerais quoi à peu prêt comme alternatives ?

*/


## Explorer des alternatives - exemple .[fade-in fade-out hide-title #split]

<nav class="breadcrumbs">
  <a class="">Poser la question</a>
  <a class="">Clarifier le contexte</a>
  <a class="is-active">Explorer des alternatives</a>
  <a class="">Etudier ces alternatives</a>
  <a class="">Converger vers la décision</a>
  <a class="">Ecrire une décision claire</a>
  <a class="">Se préparer aux conséquences</a>
</nav>

[[left]]

!image(https://www.ml4devs.com/images/illustrations/sql-vs-nosql-cheatsheet.webp, , , 750px, , 'Source: https://www.ml4devs.com/articles/datastore-choices-sql-vs-nosql-database/')

[[/left]]

[[right]]

* Ne pas ajouter de base de données
* PostgreSQL
* MongoDB
* Google BigQuery

[[/right]]

/*

{Nicolas} Donc on sait qu'on veut stocker des indicateurs de popularités de librairies open-source. Ca veut dire qu'on a des données relationnelles, liées essentiellement par une clé.
L'avantage de ce genre de question, c'est qu'il y a un diagramme de décision.
Quand je le regarde je me dis que Postgres ou MongoDB sont de bonnes solutions

{Logan} Candidats, pour l'instant

{Nicolas} Je me dis aussi que Google BigQuery conviendrait bien, parce qu'il n'y a pas de conteneurs à déployer, à opérer ...

{Logan} Attends deux secondes, ça ressemble à un principe ou une contrainte, non ?

{Logan} Et puis on pourrait avoir des BDD sur des services managés comme Aiven par exemple, non ?

{Nicolas} **TRANSITION** Ah oui, en effet, j'ai pas pensé à mettre ça dans le contexte. C'est important, je vais les ajouter.

*/


## Exemple .[fade-in fade-out hide-title]

<nav class="breadcrumbs">
  <a class="">Poser la question</a>
  <a class="">Clarifier le contexte</a>
  <a class="is-active">Explorer des alternatives</a>
  <a class="">Etudier ces alternatives</a>
  <a class="">Converger vers la décision</a>
  <a class="">Ecrire une décision claire</a>
  <a class="">Se préparer aux conséquences</a>
</nav>


* Exigences fonctionnels
    * Indicateurs numériques multidimensionels et temporels (librairie, stars, téléchargements, questions, ...)
    * Comparaison par librairie et par date (Courbes)
* Exigences non-fonctionnelles
    * 15.000 technologies actuellement
    * Recherche par librairie
* Contraintes de l'écosystème
    * Ça doit être prêt pour la semaine prochaine
* Principes de l'équipe
    * Respect des 12 Factors
    * Utilisation des Enterprise Integration Patterns
    * **On ne veut pas opérer de systèmes**

/*

{Nicolas} OK, maintenant, on a assez d'informations pour choisir ?

{Logan} **TRANSITION** Non, maintenant il faut évaluer.
*/