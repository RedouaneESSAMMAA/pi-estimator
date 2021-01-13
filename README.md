# pi-estimator
Ce calcul est basé sur l'heuristique suivante: Par définition 𝜋 est l'aire 𝐴(Cercle) d'un cercle de rayon 𝑟 = 1 (𝐴(Cercle) =  𝜋⋅𝑟2 est l'aire d'un cercle de rayon 𝑟).
On circonscrit alors ce cercle unité par un carré dont l'aire vaut 𝐴(Square) = 4. Le rapport de ces deux zones est donc égal à 𝐴(Circle)/𝐴(Square) = 𝜋/4 et donne la probabilité géométrique d'un point à l'intérieur du carré de se trouver à l'intérieur du cercle.
Supposons maintenant que nous choisissons un nombre énorme de points au hasard à l'intérieur du carré circonscrit, par exemple, en lançant des fléchettes ou en laissant tomber des gouttes de pluie dessus. Un certain nombre de ces points se retrouvera à l'intérieur de la zone décrite par le cercle tandis que le nombre restant de ces points se trouvera à l'extérieur (mais à l'intérieur du carré). Ainsi 𝑛(in) + 𝑛(out) = 𝑛 et la probabilité d'un point situé à l'intérieur de l'aire du cercle est 𝑛(in).


<img src = "Images/Enoncé.PNG">


Heuristiquement, on a 𝐴(Circle)/𝐴(Square)≈ 𝑛(in)/𝑛  et donc 𝜋≈4 𝑛(in)/𝑛. 
Il va sans dire que cet algorithme n'est pas déterministe et que les résultats changeront probablement à chaque exécution. 
Soit la fonction suivante qui permet de simuler un point p avec deux coordonnées x et y pour déterminer si le point simulé est à l’intérieur ou à l'extérieur du cercle.


# Résultats :


<img src = "Images/Comparaison.PNG">
