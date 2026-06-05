## Tester les alternatives .[fade-in fade-out hide-title steps]

<nav class="breadcrumbs">
  <a class="">Poser la question</a>
  <a class="">Clarifier le contexte</a>
  <a class="">Explorer des alternatives</a>
  <a class="is-active">Etudier ces alternatives</a>
  <a class="">Converger vers la décision</a>
  <a class="">Ecrire une décision claire</a>
  <a class="">Se préparer aux conséquences</a>
</nav>

Créer des expériences reproductibles vérifiant comment les alternatives implémentent les critères mesurables

/*

{Nicolas}
Comment tester ?
En réalisant des expériences c'est-à-dire en testant la question pour une alternative
Reproductible au cours du temps (parce que les alternatives peuvent évoluer)
Et ne vérifiant **que** le fait que l'alternative réponde à la question.

**TRANSITION** Dans notre cas

*/


## Exemple .[fade-in fade-out hide-title]

<nav class="breadcrumbs">
  <a class="">Poser la question</a>
  <a class="">Clarifier le contexte</a>
  <a class="">Explorer des alternatives</a>
  <a class="is-active">Etudier ces alternatives</a>
  <a class="">Converger vers la décision</a>
  <a class="">Ecrire une décision claire</a>
  <a class="">Se préparer aux conséquences</a>
</nav>

Expérience à mener

* Stocker les 15.000 librairies et leurs indicateurs dans chacun des systèmes
  * PostgreSQL chez Aiven
  * MongoDB chez Aiven
  * Google BigQuery
* Mesurer le temps de réponse de la lecture des indicateurs d'Angular, React

Aiven ne correspond pas aux règles de déploiement locales.

Donc MongoDB et PostrgeSQL sont éliminées.

/*

{Nicolas} Dans notre cas, si on veut évaluer les solutions, on met ces indicateurs dans nos bases, et on récupère les valeurs.
Lorsqu'on a tenté cette expérience, la DSI nous a indiqué qu'Aiven n'était pas un fournisseur autorisé.

Ca élimine donc PostgreSQL et MongoDB alternatives et on se retrouve avec un choix facie, puisqu'on n'a plus qu'un candidat.

**TRANSITION** Et choisir parmi un candidat, c'est facile.

*/
