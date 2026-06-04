## Cynefin (/kəˈ nɛvɪn/) peut nous aider .[fade-out animate]

<table>
<tr>
<td style="text-align:right; visibility: hidden;">ADR utiles mais de façon exploratoire / évolutive</td>
<td rowspan="2">
!image(../../images/cynefin.png, , 800)
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
- La relation de cause à effet est évidente et connue (d'où le **C** et le **E** dans le diagramme)
- ==> sentir – catégoriser – réagir

<br/>

***Compliqué : C'est le domaine des "inconnus connus"***
> Imaginez maintenant que votre chaudière ne fonctionne plus
> Il peut y avoir plusieurs causes possibles
> 2 possibilités :
> - vous tentez des choses vous-même (quite à empirer le problème)
> - vous appeler le plombier
> La prochaine fois que ça arrive vous ferez ce qu'a fait le plombier mais sans vraiment savoir si ça va avoir le même effet

- La relation entre cause et effet nécessite une analyse ou une expertise
- ==> sentir – analyser – réagir

<br/>

***Complexe : C'est le domaine des "inconnus inconnus"***
> La météo est un système complexe par excellence
> On connait globalement les variables qui influencent la météo (pression, température, vent)
> Mais à situation de départ et à variables équivalentes, la météo évoluera différemment
> On a bien des modèles de prédiction mais impossible de prédire avec exactitude même en faisant appel aux plus grands experts

- La relation de cause à effet est instable et difficile à prévoir. Elle se comprend par expérimentation.
- ==> explorer – sentir – réagir
- Loop OODA ? Ce serait chouette de mettre l'image dans le quart "Complexe"

<br/>

***Chaotique :***
> Imaginez que vous êtes en train de cuisiner et que l’huile dans la poêle prend feu.
> À ce moment-là :
> - vous n’analysez pas les causes
> - vous ne cherchez pas la meilleure théorie
> - vous n’appelez pas un expert pour diagnostiquer
> Vous agissez immédiatement :
> - couper le feu
> - mettre un couvercle
> - éloigner ce qui peut brûler

- Le premier objectif n’est plus de comprendre le système, mais de reprendre le contrôle
- Souvent en temps de crise
- ==> agir – sentir – réagir

<br/>

***Confusion :***
> Ce dernier domaine est une maison inconnue plongée dans le noir.  
> Vous entrez... Vous ne savez pas ce qu'il se passe !  
> Avant même de décider, il faut comprendre dans quel domaine on se trouve.  

- Quand ce n'est dans aucun des autres domaines
- Le problème n’est **pas encore** classifiable
- Une réponse apportée maintenant a de forte chance de ne pas convenir

*/

## En quoi Cynefin est utile ? .[fade-in animate]


<table>
<tr>
<td style="text-align:right; vertical-align:top">ADR utiles mais de façon exploratoire / évolutive</td>
<td rowspan="2">
!image(../../images/cynefin.png, , 800)
</td>
<td style="vertical-align:top">ADR souvent utiles</td>
</tr>
<td style="text-align:right; vertical-align: bottiom;">Post-Mortem / Décision immédiate</td>
<td style="vertical-align: bottiom;">Best-practices, Gouvernance, Standard, Guidelines</td>
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

{Nicolas} **TRANSITION** Maintenant qu'on a décidé qu'il était nécessaire d'entrer dans un processus de décision d'architecture, et qu'on l'a classifié... **Comment on fait concrètement ?**

*/
