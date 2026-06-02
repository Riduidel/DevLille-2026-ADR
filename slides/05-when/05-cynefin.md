## Cynefin (/kəˈ nɛvɪn/) peut nous aider .[fade-out animate]

<table>
<tr>
<td style="text-align:right; visibility: hidden;">ADR utiles mais de façon exploratoire / évolutive</td>
<td rowspan="2">
!image(../../images/cynefin.png, , 1000)
</td>
<td style="visibility: hidden;">ADR souvent utiles</td>
</tr>
<td style="text-align:right; visibility: hidden;">Post-Mortem / Décision immédiate</td>
<td style="visibility: hidden;">Best-practices, Gouvernance, Standard, Guidelines</td>
<tr>
</tr>
</table>

/*

Ce framework créé par Snowden et Boone (et je parle pas d'Edward et de Danny) proposent une classification en 5 domaines pour aider à la prise de décision.

<br/>

***Simple / Evident / Clair : C'est le domaine des "connus connus"***
> Imaginez une pièce avec un interrupteur et un ampoule.  
> Quand on intéragit avec l'interrupteur l'état de l'ampoule change.  
> Le comportement est attendu, stable et connu.  
- La relation de cause à effet est évidente et connue
- ==> sentir – catégoriser – réagir

<br/>

***Compliqué : C'est le domaine des "inconnus connus"***
> Imaginez maintenant une pièce avec 3 interrupteurs en va-et-vient étrange et une ampoule.  
> Avec suffisamment d’analyse ou l’aide d’un expert, on peut prédire le comportement.  
> Et, même une fois la connaissance acquise, parfois vous vous tromperez sans cet expert.  

- La relation entre cause et effet nécessite une analyse ou une expertise
- ==> sentir – analyser – réagir

<br/>

***Complexe : C'est le domaine des "inconnus inconnus"***
> Quand vous souhaitez, chez vous, couper une seule prise de courant au tableau électrique.  
> Qu'est ce vous faites en premier ?  
> Une personne se met à la prise de courant, une autre au tableau.  
> Et on pose la question "Et là, c'est coupé ? Et là ?". 

- La relation de cause à effet n’est pas prédictible à l’avance de manière fiable. Elle se comprend par expérimentation.
- ==> explorer – sentir – réagir
- Loop OODA ? Ce serait chouette de mettre l'image dans le quart "Complexe"

<br/>

***Chaotique :***
> Le quatrième domaine c'est une maison avec des ampoules dans chaque pièce mais un seul interrupteur centralisée.  
> A chaque fois que vous appuyez sur l'interrupteur, le comportement des ampoules semble incohérent et non maîtrisable.  
> Là on est clairement dans le chaos, même tenter d'apprendre comment il fonctionne est impossible.  

- Le premier objectif n’est plus de comprendre le système, mais de reprendre le contrôle
- Souvent en temps de crise
- ==> agir – sentir – réagir

<br/>

***Confusion :***
> Ce dernier domaine est une maison inconnue plongée dans le noir.  
> Vous entrez... Vous ne savez pas ce qu'il se passe !  
> Avant même de décider, il faut comprendre dans quel domaine on se trouve.  
- Quand ce n'est dans aucun des autres domaines
- Le problème n’est pas **encore** classifiable
- Une réponse apportée maintenant a de forte chance de ne pas convenir

*/

## En quoi Cynefin est utile ? .[fade-in animate]


<table>
<tr>
<td style="text-align:right">ADR utiles mais de façon exploratoire / évolutive</td>
<td rowspan="2">
!image(../../images/cynefin.png, , 1000)
</td>
<td>ADR souvent utiles</td>
</tr>
<td style="text-align:right">Post-Mortem / Décision immédiate</td>
<td>Best-practices, Gouvernance, Standard, Guidelines</td>
<tr>
</tr>
</table>

/*

{Logan}

Donc on se rend compte que finalement, ce n'est peut-être pas utile de faire un ADR dans toutes les situations.  
C’est surtout dans les domaines compliqués et complexe que les ADR apportent de la valeur.  
D'où l'importance de bien identifier la problématique à adresser.  

<br/>

Dans le domaine simple, les bonnes pratiques, les guidelines d'entreprise, les tech-radar prendront le pas. Il semble inutile que 200 équipes écrivent le même ADR en disant "Nous avons suivi la guideline".

<br/>

Dans le domaine du chaotique, une communication claire suffira surement car la situation ne sera pas durable et il y aura très probablement d'autres décisions ou un retour à la normale qui invalideront très rapidement les décisions prises dans le passé proche.

<br/>

Aussi, un ADR n'aura surement pas la même physionomie en fonction du domaine de classification Cynefin.
**Pour poursuivre, on va prendre l'exemple d'une problématique Compliqué qui nécessite une expertise.**

<br/>

{Nicolas} **TRANSITION** Maintenant qu'on a décidé qu'il était nécessaire de faire un ADR, et qu'on l'a classifié... **Comment on fait concrètement ?**

*/
