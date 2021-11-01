![Drag Racing](aix.png)


                           
                            
                            
                            
                            
                            
                            
                            
                            
----------
                            louai.kassa-baghdouche@etu.univ-amu.fr
                            ali.chemkhi@etu.univ-amu.fr
----------


Dans ce présent travail on va implémenter l'algorithme sur des données artificielles : une matrice de taille 6x6 qui représente 6 sites web qu'on nommera, par example, (*Facebook, YouTube, LinkedIn, Google, Twitter, Wikipédia*), afin de disséquer l'algorithme en plusieurs étapes et jouer avec les diffèrents paramètres. 

**Objectif:**

Les diffèrents étapes que nous allons réaliser sont représentés comme suit: 

* la transformation de l'algorithme PageRank sous un problème d'algèbre linéaire 
 
* Introduction du *Dumping-facteur*

* Implémentation de l'algorithme (simplifé) 

* Implémentation de l'algorithme (Version optimisé) sur des données réeles



# Implémentation de l'algorithme (Version optimisé) sur des données réeles

## Data ##
The input file `data/routes.csv` contains 59036 routes between 3209 airports on 531 airlines spanning the globe from http://www.openflights.org. The file contains two data fields: 3 letter IATA code for an origin airport and for a destination airport. Routes are directional: if an airline operates services from A to B and from B to A, both A - B and B - A are listed separately.

## Requirements ##
* Language : Python 3.8
* Libraries : NetworkX, Pandas, Datetime, CSV, Operator
    
## How to run ##
* Run `src/PageRank.py`
* Specify the full path to the input file `routes.csv`

