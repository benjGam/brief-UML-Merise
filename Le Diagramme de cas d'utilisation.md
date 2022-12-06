# Le Diagramme de cas d'utilisation

## Scénario  :

- Use case = Scénario : on prend le point du vue de l'utilisateur en partant d'une projection 

- but : se mettre a la place du client

- Utiliser le principe KISS (Keep it simple, stupid) , Ne pas trop faire complexe 
  
  - faire le diagramme pour le client pas le développeur 

## Le système

- Pour chaque système il n'existe que 1 seul diagramme.

- Un système est représenté par un cadre et un titre, le cadre matérialise la frontière. à l'extérieur, les acteurs et les cas d'utilisation sont liés entre eux par des relations.

## Les acteurs

- L'acteur est l'utilisateur de l'application (humain, une machine, un processus métier,... )

- Un acteur principal est un acteur qui définit les cas d'utilisation (il agit sur le système)

- Le cas d'utilisation s'appuient sur d'autre acteur pour obtenir un résultat (c.a.d il agit sur le système).

## Le cas d'utilisation

- un cas d'utilisation est une interaction qui permet à l'utilisateur d'atteindre son objectif (c'est une fonctionnalité visible de l'extérieur) .

- Un cas d'utilisation est déclenché par un acteur principal, il a un déroulement et une fin. (Le cas d'utilisation se représente par une ellipse et son nom)

- Se nom permet de décrire précisément l'interaction de l'utilisateur avec le système

## Les relations

### La généralisation

- Un acteur est un objet qui a la capacité d'hériter 

- la généralisation entre deux acteurs( Visiteur ⬅️Client) , le client est un visiteur)

### La communication

- C'est une relation entre un acteur est un cas d'utilisation 

- Un acteur principal déclenche un cas d'utilisation, un cas d'utilisation peut invoquer un acteur secondaire ( relation acteurs/cas d'utils ) 

### L'utilisation

C'est une relation entre deux cas d'utilisation, nous parlons aussi de relation d'inclusion (**include**)
On utilisera cette relation pour factoriser/décomponser un cas d'utilisation complexe (on atomise).

### La possibilité

La possibilité est un cas d'utilisation qui n'est pas inhérent à un cas d'utilisation, il peut en découler,<br>
mais ce n'est pas strictement obligatoire, à l'inverse de l'utilisation. La possibilité se caractèrise par<br>
le mot clè **extend**

### Le complément textuel

Le complément textuel est un moyen d'apporter plus d'informations concernant le diagramme de use-case<br>
se pourrait-être apparenté à un lexique du diagramme de use-case, ou bien une extension, le complément<br>
textuel, permet comme son nom l'indique d'apporter un complément au diagramme de use case.<br>