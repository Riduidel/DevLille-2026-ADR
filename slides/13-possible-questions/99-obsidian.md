## Exemple liens ADRs dans Obsidian

!image(../images/decision_revision_impact.png, , , 400)

/*

La c'est une chaine de décision fictive.

- Le monolith a influencé :
    - l'utilisation de Spring Modulite
- L'utilisation de Kafka pour l'asynchrone a influencé :
    - Kafka pour exposer les evenements métiers
    - Kafka pour l'asychrone interne à l'application
    - Utilisation de la schema registry partout

Si je souhaite revoir ma stratégie monolithique, je sais qu'il est inutile de remettre en question l'utilisation de Kafka par exemple.
En revanche, je sais qu'il faut peut-être revoir l'adoption de Spring mondulith.

*/