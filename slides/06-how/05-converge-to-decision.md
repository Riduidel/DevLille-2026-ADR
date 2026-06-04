## Converger vers une décision  .[fade-in fade-out hide-title]

<nav class="breadcrumbs">
  <a class="">Poser la question</a>
  <a class="">Clarifier le contexte</a>
  <a class="">Explorer des alternatives</a>
  <a class="">Etudier ces alternatives</a>
  <a class="is-active">Converger vers la décision</a>
  <a class="">Ecrire une décision claire</a>
  <a class="">Se préparer aux conséquences</a>
</nav>

<iframe src="https://fr.wikipedia.org/wiki/M%C3%A9thode_de_Delphes" width=1280 height=800>
</iframe>

/*

Au début j'étais complexé de lire des ADR ultra complet.  
Je ne me sentais pas à la hauteur de produire de tel artefact.  
Mais les ADR sont en fait un process itératifs et parfois long (quand on a le temps).  
Un peu comme une architecture finalement, elle ne se construit pas en 1 jour.

DOUTE:Logan ==> Je sais que c'est un aspect hyper important de l'ADR mais si on le met dans la partie contexte, il va devenir obèse.
DOUTE:Logan ==> Je sais pas trop où le mettre, donc je le pose là pour l'instant.
DOUTE:Logan ==> Est-ce qu'il faut le split en deux : 1 en fin de context et 1 en début de décision.
DOUTE:Logan ==> Voire même en 3 : + 1 sur chaque alternative
DOUTE:Logan ==> Grand question ?

Autre point important, la convergence vers une décision nécessite de poser les critères de décision.
Personnellement, j'aime bien les poser juste avant l'exploration des alternatives pour qu'ensuite sur chaque alternative on voit l'adéquation avec les critères de décision.

Et on peut reprendre toute cette information de façon syntétique juste avant de prendre la décision.
Ça donne une synthèse pour montrer l'évidence de la décision.

<== DOUTE:Logan

*/

## Exemple .[fade-in fade-out hide-title]

<nav class="breadcrumbs">
  <a class="">Poser la question</a>
  <a class="">Clarifier le contexte</a>
  <a class="">Explorer des alternatives</a>
  <a class="">Etudier ces alternatives</a>
  <a class="is-active">Converger vers la décision</a>
  <a class="">Ecrire une décision claire</a>
  <a class="">Se préparer aux conséquences</a>
</nav>

Au vu du contexte, Google BigQuery est la seule solution valable.

/*

{Nicolas} On pensait avoir le choix, et en fait on ne l'a pas tant que ça.
{Nicolas} Ca peut aussi être une découverte d'un ADR.

PROPOSITION:Logan ==>
{Logan} Oui, en effet, c'est Simon Brown qui disait que "plus le contexte est contraint plus la décision devient évidente". Tu tombe pile dans ce cas.

{Logan} Mais attends, si Big Query est autorisé, pourquoi ne pas explorer la piste des services managés de Azure, AWS, OVH ou Scaleway par exemple ?

{Nicolas} Ah effectivement, ce sont des contraintes que je n'ai pas explicitées dans le contexte.
<== PROPOSITION:Logan
*/
