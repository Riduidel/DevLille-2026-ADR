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

DOUTE:Logan ==> Je suis pas sur de comprendre la partie "correspondent dans l'ordre aux points du contexte"
DOUTE:Logan ==> Du coup, je suis un peu perdu dans l'intention de cette slide.
DOUTE:Logan ==> Je pense que je n'arrive pas à avoir l'image mentale que tu essayes de projeter.

{Logan} Ça c'est la partie un peu créative que j'affectionne.

{Logan} C'est là qu'il va falloir imaginer des solutions qui respectent l'ensemble des éléments qui contraignent la décision d'architecture.

{Logan} Une des premières alternatives que j'aime bien poser en général, c'est : "NE RIEN FAIRE"

{Logan} Ne rien faire est souvent une option négligée et pourtant viable dans certains cas.

{Logan} Ça permet de mettre en évidence les "risques à ne pas faire".

{Logan} Une phrase que je répète souvent, c'est : "NE RIEN FAIRE EST TOUJOURS UNE OPTION".

{Logan} **TRANSISTION** Si on reprend l'exemple de ton besoin de stocker de l'information, tu explorerais quoi à peu prêt comme alternatives ?

DOUTE:Logan ==> Faut-il vraiment aller dans cette direction ici en-dessous ?
DOUTE:Logan ==> Quel serait la bonne orientation pour basculer de la théorie à la pratique ?

{Logan} Souvenez-vous, à la base, la question c'était "Quelle BDD choisir ?", on se retrouve, après avoir bien cadrer la décision à prendre, avec des considérations d'**indexation multi-dimensionnelle**, d'**agrégation de données**, de **timeseries** et du **pré-calcul ou calcul à la volée**.

{Logan} Donc il semblerait que la décision soit un poil plus large que le simple choix de la BDD.

<== DOUTE:Logan

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

{Nicolas} PostgreSQL et MongDB ... blabla ... pas de containerisation ... blabla ...

{Logan} Attends deux secondes, tu n'as pas mentionné cette contrainte là, d'où elle sort ?
{Logan} Et puis on pourrait avoir des BDD sur des services managés comme Aiven par exemple, non ?

{Nicolas} Ah oui, en effet, j'ai pas pensé à mettre ça dans le contexte. C'est important, je vais les ajouter.

META:Logan ==> Lien avec "outil vivant"
META:Logan ==> Lien avec "iterration"
META:Logan ==> Lien avec "expertise" (que ce serait-il passé si j'avais pas constaté le trou ?)

DOUTE:Logan ==> Pas sur qu'il faille garder la suite
{Logan} Par ailleurs, je vois apparaître PostgreSQL et MongoDB. Ca ne peut pas correspondre aux contraintes ? Ou alors tu as l'intention de faire du Aiven ?

*/