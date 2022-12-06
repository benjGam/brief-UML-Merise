# Règles de gestions
>Les règles de gestion sont des règles qui permettent de définir des contraintes sur les données

- Un vol :
  - Un vol est créé par une compagnie aérienne

  - Il peut être ouvert et fermé à la réservation par la compagnie aérienne

  - Il peut être annulé par compagnie aérienne

  - Il peut comporter 0 à plusieurs escale(s)

  - Il dispose d'un nombre de places disponibles

  - Il dispose un aéroport de départ et d'arrivée

  - Il dispose une heure de départ et d'arrivée

  - Il dispose un numéro d'identification
  
  - Il dispose d'une liste de passager

  - Il est lié à un avion

  - Dispose d'une liste de passager

- Une escale :
  - Dispose d'une heure d'arrivée et de départ

  - Est liée à un aéroport

  - Est liée à un vol
  
  - Dispose d'une liste de passager

- Un aéroport : 
  - Se situe dans une ville

  - Héberge 1 à n compagnie(s) aérienne(s)

- Une réservation : 
  - Peut impliquer 1 à n vol(s)

  - Les informations du passager

  - Peut être annulée par le passager

  - Possède un numéro de siège

  - Possède un numéro d'identification

- Un passager :
  - Un passager possède 1 à n reservation(s)

  - Un passager peut annuler sa réservation

- Un client :
  - Peut faire 1 à n réservation(s)

  - Peut annuler la/les réservation(s) qu’il a réalisé