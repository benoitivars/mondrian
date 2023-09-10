# Mondrian

## Plan d'attaque

Là, on attaque du lourd ! J'ai réfléchi avec une feuille de papier :

J'ientifie 9 ensembles.

Je me vois répartir 
 * sur une grille de 5 colonnes sur 5 rangées
 * avec 9 éléments

### Plan revu

Après m'être pété la tête sur une feuile quadriée, 

* je vais partir sur du 8 colonnes sur 7 rangées, 
* avec 20 éléments, 
* que je pourrais répartir en six classes pour les couleurs  

### Après deux nuits de réflexion

En fait, il y a deux approches,

* Soit je une grille de 8*7  
    * où je mets des items partout
    * de toutes les couleurs
    *et on a dont on va étirer/sqizer toutes les cases

* Soit on met une grille de 4*3 
    * où on déforme à balle les items, 
    * on met des gaps 
    * et un fond de couleur 

Je push ça, et en rentrant fait un push témoin pour "mesurer" le temps que ça me prendra !

UPDATE : 20h35 : je tente ma chance !

### FEEDBACK

J'y suis arrivé ! J'ai eu une seule difficulté : j'ai bataillé pour tenter de modifier la hauteur des deux rectangles en bas de la dernière colonne, ce qui donnait sous le rectangle bleu un espace noir immense... jusqu'au rectangle blanc cassé qui lui sortait alègrement d emon carré et partit vivre sa vie.

L'astuce a été alors de fusitonner ces deux rectangles en un seul item dans kequel j'ai mis deux classes, une pour le rectangle bleu et une pour le rectangle blanc cassé. EN renvanche, je dois avouer que là, sur la fin, j'ai bidouillé manu militari, entrant des ordres de gandeur à la main pour "bourrer" les pixels manquants pour faire un carré harmonieux. 

Je pense avoir saisi le grid !