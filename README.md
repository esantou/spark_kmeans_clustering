# Exécution du programme

- Le fichier data comprend la base de donnée bristol-city-bike.json

- Le fichier exported comprend le ficher exporté fiited sans la colonne features

- Le fichier config est composé des différents chémins d'accès aux différents dossiers

- bristol.ipynb est le script python

# spark_kmeans_clustering

- Ce projet consiste à réaliser un clustering à l'aide de la méthode de Kmeans.
- On disposons des données concernant l'emplacement des vélos dans la ville Brisbane.

Ce tableau montre les trois prémières observations de notre base de donées
------------------------------------------------------------------------
|             address|  latitude| longitude|                name|number|
|:--------------------|:----------|:----------|:--------------------|:------|
|Lower River Tce /...|-27.482279|153.028723|122 - LOWER RIVER...|   122|
|Main St / Darragh St| -27.47059|153.036046|91 - MAIN ST / DA...|    91|
|Sydney St Ferry T...|-27.474531|153.042728|88 - SYDNEY ST FE...|    88|
------------------------------------------------------------------------

- Pour réaliser le clustering, on a utilisé les variables Longitude et Lattitude


- Ci dessous les moyennes de latitude et longitude par groupe cluster
---------------------------------------------------
|prediction|      avg(latitude)|    avg(longitude)|
|:----------|:-------------------|:------------------|
|         1|-27.460240636363633|153.04186302272726|
|         2| -27.47255990624999|   153.02594553125|
|         0|-27.481218536585374|153.00572882926832|
---------------------------------------------------
