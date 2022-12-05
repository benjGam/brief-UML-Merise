# Le diagramme d'Use case :

## Présentation

Le diagramme de cas d'utilisation ou Use Case est un diagramme à destination du client, c'est pourquoi, il doit resté le plus clair et conçis possible.

Afin d'écrire un diagramme de cas d'utilisation le plus clair possible il faut suivres quelques conseils :

- Écrire le diagramme de cas d'utilisation en fonction de ses lecteurs, il n'est pas forcément à déstination d'autres développeurs ou concepteurs, c'est pourquoi, il est plus intéressant de garder en tête lors de l'écriture du diagramme de cas d'utilisation, que ce dernier est amené à être consulté par des tiers n'étant pas forcément très familliarisé avec le domaine.

- Suivre le principe KISS (Keep It Simple, Stupid) en d'autres termes : Faire au plus simple. Les questions que vous pouvez vous posez lors de l'écriture du diagramme et après l'écriture afin de vérifier si ce principe est bien appliqué sont :
  
  - Ai-je trop détaillé mon diagramme ? Est-il compréhensible facilement ?
  
  - Mon diagramme n'est-il pas insuffisamment détaillé ? Devrais-je faire plusieurs diagrammes afin de détailler plus le fonctionnement de mon application ?



## Composition

Le diagramme de cas d'utilisation possède plusieurs composants, tels que les suivants :

- Le système : il est seul au sein du diagramme, et est représenté par un cadre ainsi que d'un titre.

- L'acteur : Qu'il s'agisse d'un être humain, une machine, un service, un acteur est un utilisateur direct ou indirect qui est impliqué dans le processus du système. 
  
  Il existe deux types d'acteurs  :
  
  - L'acteur principal : Il déclenche des cas d'utilisation au sein du système
  
  - L'acteur secondaire : Il est invoqué par le système

- Le cas d'utilisation : Le cas d'utilisation pourrait-être résumé par une action contenue au sein du système. Un cas d'utilisation à un début, un déroulement ainsi qu'une fin, il est visible par l'acteur principale et sert à décrire une action disponible pour ce dernier.

### Les relations

- La généralisation : Un acteur est au sein du diagramme de cas d'utilisation un objet, cet objet peut hériter d'un autre. On appelle ce concept "la généralisation" est peut-être appliqué lorsque l'on peut dire d'un acteur qu'il en est un autre. Prenons un exemple : Une voiture est un Véhicule, la Voiture peut-être généralisée vers le Véhicule. (Les cas d'utilisations sont aussi des objets généralisables)
  La généralisation se caractèrise par une flêche **inversée** se terminant par un triangle vide.

- La communication : La communication est un type de relation qui survient lorsqu'un acteur intéragit avec un cas d'utilisation, on dit alors que l'acteur (principal) déclenche un cas d'utilisation.

- L'utilisation : L'utilisation intervient lorsqu'un cas d'utilisation en appelle un autre, on dit que le cas d'utilisation A utilise le cas d'utilisation B.
  L'utilisation peut-être utile afin de factoriser le diagramme ou au contraire afin de décomposer un cas d'utilisation complexe afin de le rendre plus compréhensible.
  Ce type de relation est caractérisé par le terme "include" sur la relation.

- La possibilité : La possibilité intervient de la même façon que l'utilisation, cependant, la possibilité représente une option, là où l'utilisation est obligatoire.
  Le possibilité se caractérise par le terme "extend" sur la relation.



## Le complément textuel

Le complément textuel est comme son nom l'indique, un moyen de rendre plus complet le diagramme de cas d'utilisation, celui-ci n'étant pas suffisamment précis, il est possible d'ajouter des informations afin d'avoir une vue plus précise du diagramme et donc du fonctionnement du programme final.








