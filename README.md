Ce projet de visualisation montre l'évolution des caractéristiques du parcours du Tour de France de sa première édition en 1903 à 2017.
Le parcours est représenté par les villes visitées, les étapes, les types d'étapes (montagne, plat, contre la montre), le nombre d'étape et leur distance.

Notre production finale se compose de 3 graphiques:
  - évolution du nombre et du type d'étape au cours du temps
  - évolution de la distance par étape (en fonction du type d'étape) et de la distance totale du Tour
  - carte des villes visitées et du nombre d'étapes entre deux villes avant et après 1945

Notre jeu de données intial a été remanié pour construire l'ensemble des graphiques.
Pour la construction de la carte, il a fallu aller chercher les coordonnées GPS des villes étapes et arrivées à l'aide de l'API openstreetmap. Le  nouveau jeu de données formé s'appelle stages_TDFcoord2.csv. Par la suite ce jeu de données à été transformé de deux façons:
  - pour obtenir les informations sur les villes (coordonnées et nb de fois à la ville à accueilli le Tour) : le data frame COuntVille
  - pour obtenir les informations sur les étapes (coordonnées villes d'arrivé et de départ et nb de fois où les villes ont été relié) : dataframe Count_Etape
 
  
