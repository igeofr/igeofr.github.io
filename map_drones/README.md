## Les exploitants en activités particulières au moyen d'aéronefs télé-pilotés

[Exemple de carte localisant les exploitants en activités particulières au moyen d'aéronefs télé-pilotés.] (http://igeofr.github.io/map_drones/map.html)

## Téléchargement
Le fichier des exploitants en activités particulières au moyen d'aéronefs télé-pilotés est disponible au format .geojson

- [Fichier créé à partir de la liste du 15/11/2014](https://github.com/igeofr/igeofr.github.io/blob/master/map_drones/201411/20141115_exploitants.geojson)
- [Fichier créé à partir de la liste du 18/09/2014](https://github.com/igeofr/igeofr.github.io/blob/master/map_drones/201409/20140918_exploitants.geojson)
- [Fichier créé à partir de la liste du 02/07/2014](https://github.com/igeofr/igeofr.github.io/blob/master/map_drones/201407/20140702_exploitants.geojson)

## Les champs du fichiers

- NOM : Correspond au nom de la société ou de l'exploitant ayant reçu une autorisation
- CODE_P : Code postal de l'exploitant
- VILLE : Ville de l'exploitant
- PAYS : Pays de l'exploitant
- WEB : Adresse web
- AGR : Les traitements agricoles, phytosanitaires ou de protection sanitaire et les autres opérations d’épandage
sur le sol ou de dispersion dans l’atmosphère
- FOR_AGR : Formation à l’activité AGR
- LRG : Le largage de charges de toutes natures
- FOR_LRG : Formation à l’activité LRG
- PUB : Le remorquage de banderoles ou toute forme de publicité
- FOR_PUB : Formation PUB
- OBS : Les relevés, photographies, observations et surveillances aériennes, qui comprennent la participation aux
activités de lutte contre l’incendie
- FOR_OBS : Formation à l’activité OBS
- AUT : Toute autre activité nécessitant une dérogation aux règles de l’air
- FOR_AUT : Formation à toute autre activité nécessitant une dérogation aux règles de l’air
- S1 : Scénario S1 autorisé
- S2 : Scénario S2 autorisé
- S3 : Scénario S3 autorisé
- S4 : Scénario S4 autorisé
- FPDC : Membre de la Fédération professionnelle des drones civils

## Source des données
- France
Les données sont issues de la liste gérée par la DGAC et disponible [ici] (http://listedrones.dsac.fr).

Cette liste est régulièrement [publiée en pdf] (http://www.developpement-durable.gouv.fr/Effectuer-des-activites) sur le site du ministère de l'écologie, du développement durable et de l'énergie.

La Fédération Nationale du Drone Civil m'a mis à disposition le listing de ses membres de manière à ajouter un champ supplémentaire.

- UK (Civil Aviation Authority)
Liste du 23/03/2015 : http://www.caa.co.uk/docs/1995/23Mar15%20RptUAVcurrentDates.pdf

## Licence
La donnée est disponible sous licence [CC BY-SA 3.0 FR]
(http://creativecommons.org/licenses/by-sa/3.0/fr/).

##Création du fichier initial

- Téléchargement du dernier fichier mis à disposition par la DGAC (fichier du 02/07/2014)
- Export du fichier PDF en tableur  
- Nettoyage du fichier et vérification d'un maximum d'adresses (+ajout des sites internet)
- Géocodage avec le plugin QGIS [MMQGIS](http://michaelminn.com/linux/mmqgis/)

## Mise à jour du fichier
Les difficultés :
- extraire les informations de la DGAC dans un tableur

Une piste : Suite à la découverte de ce lien : [http://listedrones.dsac.fr] (http://listedrones.dsac.fr) il serait peut être plus simple d'utiliser [cet outil](http://www.convertcsv.com/html-table-to-csv.htm) (html table to csv) ou bien [celui-ci](https://import.io) pour récupérer le listing.  
- identifier facilement les changements dans le fichier de la DGAC
- modifier l'emplacement d'un point lorsque l'adresse évolue (en utilisant les lat-long)

##Le mot de la fin
Si vous avez des propositions d'améliorations ou si vous êtes motivés pour participer à ce projet alors n'hésitez pas à me contacter ([@iGeoFlo](https://twitter.com/iGeoFlo)).
