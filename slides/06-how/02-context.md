## Clarifier le contexte .[fade-in fade-out hide-title]

<nav class="breadcrumbs">
  <a class="">Poser la question</a>
  <a class="is-active">Clarifier le contexte</a>
  <a class="">Explorer des alternatives</a>
  <a class="">Etudier ces alternatives</a>
  <a class="">Converger vers la décision</a>
  <a class="">Ecrire une décision claire</a>
  <a class="">Se préparer aux conséquences</a>
</nav>


* Exigences fonctionnelles
* Exigences non-fonctionnelles
* Contraintes de l'écosystème
* Principes de l'équipe

⚠️ Il faut autant que possible fournir les indicateurs mesurables associés

/*

{Logan} Le contexte d’un ADR regroupe tout ce qui **influence ou contraint une décision d’architecture**, mais qui n’est pas une décision elle-même : c'est l'ensemble des choses qu'on ne peut pas changer et avec lesquelles il va falloir composer.

On va naturellement y trouver différents éléments, qui méritent d'être traités dans cet ordre.

<br/>

En terme d'exigences fonctionnelles et non-fonctionnelles, est-ce que ton/ta PO ou ton/ta QA a exprimé des exigences ?

> Exigences fonctionnelles = Ce que le système doit permettre de faire
> Exigences non-fonctionnelles = Contraintes mesurable à respecter

<br/>

Concernant les ***Contraintes*** de l'écosystème ici **au sens large du terme**:
- des contraintes de règlementation (sécurité, RGPD, )
- des contraintes de l'entreprise (tech-radar)
- des contraintes contractuelles (tel éditeur est proscrit)
- des contraintes d'auditabilité
- etc.

> Contraintes = Éléments avec lesquelles tu **dois** composer, c'est une **obligation**

<br/>

Pour ce qui est des ***Principes***, là aussi, tu peux ratisser large :
- Principes du niveau de l'entreprise au niveau de l'équipe
- En passant par tous les niveaux intermédiaire possibles et immaginables

> Principes = Règles qui guide globalement les décisions mais qui peut être **transgressée de manière justifiée**.

<br/>

{Nicolas} **TRANSITION**

*/

## Exemple .[fade-in fade-out hide-title]

<nav class="breadcrumbs">
  <a class="">Poser la question</a>
  <a class="is-active">Clarifier le contexte</a>
  <a class="">Explorer des alternatives</a>
  <a class="">Etudier ces alternatives</a>
  <a class="">Converger vers la décision</a>
  <a class="">Ecrire une décision claire</a>
  <a class="">Se préparer aux conséquences</a>
</nav>

* Exigences fonctionnels
    * Indicateurs numériques multidimensionels et temporels (librairie, stars, téléchargements, questions, ...)
    * Comparaison par librairie et par Date (Courbes)
* Exigences non-fonctionnelles
    * 15.000 technologies actuellement
    * Récupération par API
    * Recherche par librairie
* Contraintes de l'écosystème
    * On ne déploie pas de solution conteneurisée
    * Le stockage doit être sur un cloud français
    * Ça doit être prêt pour la semaine prochaine
* Principes de l'équipe
    * Respect des 12 Factors
    * Utilisation des Enterprise Integration Patterns

/*
{Logan}
***"Récupération par API"***
> Attends, celle-là, je suis pas vraiment sur que ça va faire avancer la réflexion ça

<br/>

***"Contraintes de l'écosystème"***
> Simon Brown (papa de C4) disait : Plus le contexte est contraint plus la décision est simple.  
> Bon ça a des limites quand même.
> Quand aucune solution ne correspond à toutes les contraintes, il est temps de déroger à certaines.  

<br/>

***"Utilisation des Enterprise Integration Patterns"***
> Pour favoriser la découplage des flux de données.

*/
## Exemple .[fade-in fade-out hide-title]

<nav class="breadcrumbs">
  <a class="">Poser la question</a>
  <a class="is-active">Clarifier le contexte</a>
  <a class="">Explorer des alternatives</a>
  <a class="">Etudier ces alternatives</a>
  <a class="">Converger vers la décision</a>
  <a class="">Ecrire une décision claire</a>
  <a class="">Se préparer aux conséquences</a>
</nav>


* Exigences fonctionnels
    * Indicateurs numériques multidimensionels et temporels (librairie, stars, téléchargements, questions, ...)
    * Comparaison par librairie et par Date (Courbes)
* Exigences non-fonctionnelles
    * 15.000 technologies actuellement
    * Recherche par librairie
* Contraintes de l'écosystème
    * On ne déploie pas de solution conteneurisée
    * Le stockage doit être sur un cloud français
    * Ça doit être prêt pour la semaine prochaine
* Principes de l'équipe
    * Respect des 12 Factors
    * Utilisation des Enterprise Integration Patterns
