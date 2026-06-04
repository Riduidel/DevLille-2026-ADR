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
* Ordre de grandeur des volumes
* Contraintes de l'écosystème
* Principes de l'équipe
* Décisions précédentes

⚠️ Il faut autant que possible fournir les indicateurs mesurables associés

/*

{Logan} Le contexte d’un ADR regroupe tout ce qui **influence ou contraint une décision d’architecture**, mais qui n’est pas une décision elle-même (ex: `Synchronisation nocturne`, `Historisation des indicateurs`).
C'est l'ensemble des choses qu'on ne peut pas changer et avec lesquelles il va falloir composer.

On va naturellement y trouver différents éléments, qui méritent d'être traités dans cet ordre.

<br/>

> Exigences fonctionnelles = Ce que le système doit permettre de faire
> Exigences non-fonctionnelles = Contraintes mesurable à respecter

En terme d'exigences fonctionnelles et non-fonctionnelles, est-ce que ton/ta PO ou ton/ta QA a exprimé des exigences ?

<br/>

Alors attention au exigences non-fonctionnelles, elles n'ont souvent de signification qu'au regard d'un volume.
Que ce volume représente une charge, un nombre d'utilisateur, une quantité de données, il est indispensable de le formaliser pour cadrer ces éxigences.
Si une des exigences est de répondre à l'utilisateur en moins de 1 seconde, ça ne peut être inconditionnel.
Vous vous doutez bien que pour 1 millards d'éléments avec une charge de 3000 utilisateurs simultanés, on mettra pas les même moyens en œuvre que pour 100 elements avec 5 utilisateurs simultanés.

Donc précisez bien les volumes attendus.
En ordre de grandeur, c'est le nombre de 0 qui compte, pas le nombre exacte.
> Vous savez c'est quoi la différence entre 1,000 et 10,000 ? bah c'est presque 10,000.

<br/>

> Contraintes = Éléments avec lesquelles tu **dois** composer, c'est une **obligation**

Concernant les ***Contraintes*** de l'écosystème ici **au sens large du terme**:
- des contraintes de règlementation (sécurité, RGPD, )
- des contraintes de l'entreprise (tech-radar)
- des contraintes contractuelles (tel éditeur est proscrit)
- des contraintes d'auditabilité
- etc.

<br/>

> Principes = Règles qui guident globalement les décisions mais qui peut être **transgressée de manière justifiée**.

Pour ce qui est des ***Principes***, là aussi, tu peux ratisser large :
- Principes au niveau de l'entreprise
    - ex: Découplage des sytèmes
    - ex: Éviter la duplication de données entre systèmes
    - ex: Zero-trust everywhere
- Principes au niveau de l'équipe
    - ex: Asynch everywhere
    - ex: 

<br/>

DOUTE:Logan ==> Je ne sais pas s'il faut le mettre en dernier.

Si, parce que c'est le moins dur à bouger.

DOUTE:Logan ==> Mais je sais que c'est une excellente idée.

> En en petit bonus, j'ajouterais les décisions en amont de la prise de décision actuelle.

C'est un outil puissant qui vous permettra de faire une chaine de remise en question.
Imaginez, vous revenez sur une décision précise, vous rendez donc l'ADR obsolète.
Cet ADR était mentionné comme point de départ de 2 ADRs en aval.
Vous avez maintenant la capacité de revoir également ces décisions pour en évaluer l'impact et ainsi de suite.
Vous maitrisez maintenant les impacts décisionnels en chaine.

Et si on pousse le vice encore plus loin, certains outils documentaire comme Obsidian offre une représentation graphique des liens entre documents.

<== DOUTE:Logan

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

META:Logan ==> Là on montre un anti-pattern, c'est cool

{Logan}
***"Récupération par API"***
> Attends, celle-là, je suis pas vraiment sur que ça fasse avancer la réflexion ça
> Et puis ça ressemble quand même déjà à une décision on dirait

<br/>

***"Utilisation des Enterprise Integration Patterns"***
> Pour favoriser la découplage des flux de données.

<br/>

{Nicolas} **TRANSITION** ok, donc j'enlève et je reformule ?
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
    * Comparaison par librairie et par date (Courbes)
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

/*

{Logan} Décompléxez vous quant à la pertinence de ce context.

{Logan} Je vous rassure, personnellement, je n'arrive jamais à construire le contexte du premier coup.

{Logan} Il y a toujours des éléments que j'oublie ou que je sous-estime sur l'instant.

{Logan} C'est au fil de discussions et d'exploration d'alternatives que j'arrive à identifier les éléments qui participe vraiment à la prise de décision.

{Logan} On y reviendra un peu dans la suite.

{Nicolas} Bon, maintenant j'imagine qu'il faut que je décide ?

{Logan} **TRANSITON** Si on essaye d'avoir une approche expérimentale, il faut d'abord que tu explores des alternatives

*/