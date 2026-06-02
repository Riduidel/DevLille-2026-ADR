## ACED peut nous aider .[full-size-iframe]

![aced](https://acedmodel.com/images/ACED-graph-plots-web.webp)

/*

{Nicolas} On voit plusieurs choses dans ce schéma.<br/>
D'abord, comment le contexte définit le design a niveau de l'entreprise.<br/>
Puis comment l'architecture fonctionnelle influence le design des systèmes.<br/>
<br/>
Notez que dans ce schéma, les sous-systèmes et modules peuvent être remplacés par des conteneurs et composants au sens C4.<br/>
<br/>
Mais aussi comment l'architecture d'un systèmle définit l'engineering d'un système, ou comment l'engineering d'un module peut impact l'architecture d'un sous-système.<br/>

* Un architecte fonctionnel peut prendre une décision concernant l'architecture de systèmes.
* Un architecte de système peut définir l'implémentation d'un sous-système.
* Et un développeur peut réclamer la ré-archiecture d'un sous-système.
<br/>
<br/>

{Logan} Ah oui, comme par exemple quand je constate en tant que développeur qu'un échange asynchrone n'offre pas les garanties de synchronisation dont j'ai besoin.<br/>
<br/>
**TRANSITION** Maintenant qu'on sait évaluer si une décision porte sur l'architecture ou pas, on va pouvoir classifier par niveaux de complexité pour savoir quelle approche utiliser.<br/>
Toutes les décisions ne nécessitent pas d'ADR comme les décisions les plus simples par exemple.<br/>
Mais comment évaluer la complexité d'un problème à résoudre ?<br/>
Pour ça, je vous propose qu'on s'appuye sur le framework Cynefin.<br/>

*/