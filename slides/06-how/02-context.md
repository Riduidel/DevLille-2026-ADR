## Clarifier le contexte

* Exigences fonctionnels
* Exigences techniques
* Contraintes de l'écosystème
* Principes de l'équipe

/*

{Logan} Le contexte, c'est l'ensemble des choses qu'on ne peut pas changer.
On va naturellement y trouver différents éléments, qui méritent d'être traités dans cet ordre.

TODO:Logan Approfondir les contraintes de l'écosystème et les principes de l'équipe

*/

## Clarifier le contexte - exemple

* Exigences fonctionnels
    * Indicateurs numériques multidimenssionnels (techno, editeur, stars, téléchargements)
    * Comparaison par Techno et par Date (Courbes)
* Exigences techniques
    * 15.000 technologies actuellement
    * Récupération par API
    * Ségrégation par Techno
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

***"Contraintes de l'écosystème"***
> Simon Brown (papa de C4) disait : Plus le contexte est contraint plus la décision est simple.  
> Bon ça a des limites quand même.
> Quand aucune solution ne correspond à toutes les contraintes, il est temps de déroger à certaines.  

***"Utilisation des Enterprise Integration Patterns"***
> Pour favoriser la découplage des flux de données.

*/
