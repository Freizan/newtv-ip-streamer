# newtv-ip-streamer
Package of applications that allow to stream video and inject eit in local network for testing 


Ce package d’outillage applicatif est destiné aux équipes de développement et de test dans le projet NewTV.
Il permet de streamer et manager des flux dans un réseau interne pour simuler les chaines IP de la PROD.
Une de ses fonctions principales est l’injection dynamique d’Eit dans ces flux, afin de pouvoir contrôler et prédire parfaitement un environnement de tests automatiques ou manuels.
Il est associé à une standalone qui simule et bouchonne tous les enablers nécessaires au fonctionnement d’une AR sur STB.
