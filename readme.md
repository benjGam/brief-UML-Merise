# Règles de gestions

- Un vol est ouvert à la réservation et refermé sur ordre de la compagnie.
- Un vol peut être annulé par la compagnie
- Un client peut réserver un ou plusieurs vols, pour des passagers différents.
- Une réservation concerne un seul vol et un seul passager.
- Une réservation peut être annulée ou confirmée.
- Un vol a un aéroport de départ et un aéroport d’arrivée.
- Un vol a un jour et une heure de départ, et un jour et une heure d’arrivée.
- Un vol peut comporter des escales dans des aéroports.
- Une escale a une heure d’arrivée et une heure de départ.
- Chaque aéroport dessert une ou plusieurs villes.
- Des compagnies aériennes proposent différents vols.

​

- Un Vol :
  
  - est fermé ou ouvert  a la réservation par la compagnie 
  
  - un vol peut être annuler pas la compagnie
  
  - un vol peut comporter  0 ou plusieurs escales dans des aéroports 
  
  - un vol a un liste de passager 
  
  - a un aéroport de départ et d'arriver 
  
  - une heure de départ et d'arriver 
  
  - numéro de vol
  
  - peux etre reservé par une agence
  
  - a une c

- Une escale 
  
  - a une heure d'arrivé et de départ 
  
  - un aéroport 
  
  - elle a un vol attribué 

- Un aéroport 
  
  - dessert une ou plusieurs ville 
  
  - a une liste de compagnie attribué 
  
  - une ville dans la quel il est situé 

- Une réservation 
  
  - Contient au moins 1 vol
  
  - information d'un passager
  
  - un confirmation ou une annulation 
  
  - un prix

  - un numéro de siege
  
  - un numéro de réservation

---------------------------------------------------

- Un vol :
  - Un vol est créer par une companie aérienne

  - Il peut être ouvert et fermé à la reservation par la companie aérienne

  - Il peut être annulé par companie aérienne

  - Il peut comporter 0..n escale(s)

  - Il dispose d'un nombre de place disponibles

  - Il a un aéroport de départ et d'arrivée

  - Il a une heure de départ et d'arrivée

  - Il a un numéro d'identification

  - Il est lié à un avion

- Une excale :
  - Dispose d'une heure d'arrivée et de départ

  - Est liée à un aéroport

  - Est liée à un vol

- Un aéroport : 
  - Se situe dans une ville

  - Heberge 1 .. n companie aérienne

- Une réservation : 
  - Possède 1 .. n vol

  - Les informations du passager

  - Peut-être annulé par le passager

  - Possède un numéro de siège

  - Possède un numéro d'identification

- Un passager :
  - A 1 .. n reservation(s)

  - A 1 passe-port (des informations)

- Un client :
  - Peut faire 1 .. n reservation(s)