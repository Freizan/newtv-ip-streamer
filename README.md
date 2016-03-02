# newtv-ip-streamer
Package of applications that allow to stream video and inject eit in local network for testing 


Ce package d’outillage applicatif est destiné aux équipes de développement et de test dans le projet NewTV.
Il permet de streamer et manager des flux dans un réseau interne pour simuler les chaines IP de la PROD.

Une de ses fonctions principales est l’injection dynamique d’Eit dans ces flux, afin de pouvoir contrôler et prédire parfaitement un environnement de tests automatiques ou manuels.

Il est associé à une standalone qui simule et bouchonne tous les enablers nécessaires au fonctionnement d’une AR sur STB.

=========================================
Le package est composé de trois éléments
=========================================

- multicat-supervisor: lance les streams IP et injecte les eit définis en base de données
github: https://github.com/orange-tv-blagnac/multicat-supervisor.git

- stream-manager: GUI pour piloter le supervisor et alimenter la base de données
github: https://github.com/orange-tv-blagnac/stream-manager.git

- base de données Mysql: script de création dans stream-manager/scripts

=========================================
DOCUMENTATION
=========================================

/doc
	StreamManagerAdmin-1.1.pdf
	StreamManageUser-1.0.pdf
	