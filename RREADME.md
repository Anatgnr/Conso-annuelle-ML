# Projet de Machine Learning

## Démarche

Dans ce projet, on va essayer de prédire les résultats du second tour des éléction de 2022.
Pour commencer, on a importer le dataset des résultats du second tour qui nous permet d'avoir des éléments de comparaison.
On essaye ensuite de trouver des datasets pour permettre de faire des prédictions.
On a trouvé un dataset sur le prix des loyer par maison et par appartement en fonction des communes pour savoir si on pouvait trouver une corélation. On a également trouvé un dataset avec les coordonés géographiques des communes comme proposé dans le sujet.
On a une précision de 50%. On peut imaginer qu'il y a une corélation, mais elle n'est pas suffisante.
On pense qu'il faudrait compléter les prix des loyers avec un revenu moyen par habitant en fonction des communes.
On pense aussi qu'il faudrait trouver l'age moyen par communes.
On a également fait le choix de ne télécharger aucun dataset pour permetre un dépot plus simple du projet. Cela indique également directement les sources utilisées. Ce choix est purement pratique. Cela implique cependant un temps d'éxécution plus lent.

## Difficultés rencontrées

Le plus compliqué dans ce projet pour nous à été la recherche de datasets pertinents.
Il semble y avoir peu de datasets sur le thème qui nous intéresse d'explorer (age et situation finanvcière).
On a pu rencontrer quelques datasets aussi vraiment incomplets ce qui ne permettait pas de faire des prédictions sur un nombre suffisant de communes.
La fusion de plusieurs datasets etait aussi un obstacle assez conséquent surtout quand on a fait des moyennes de plusieurs datasets notement sur les loyers où on a fait une moyenne des loyers maison et appartement compris. On justifie ça par le prix du logement en général par ville. On aurait pu aussi simplement ne pas faire de moyenne mais cela me semblait plus cohérent dans le sens où l'on souhaite avoir d'autres données pour appuyer notre prédiction.
On sait que cela est dit dans le sujet, mais on a du mal a avoir une bonne précision sur notre modèle. On pense donc que nos datasets employés ne sont pas forcément pertinent pour déterminer un penchant politique de chaque commune.
