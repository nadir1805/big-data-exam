# Big Data exam: 
### Supervised by: Pr. Hajji Mohammed and Pr. AIT BAHA Tarik
### Realised by: EL BOUANANI Nadir

Description des étapes nécesaires pour la réalisation de notre tableau de bord  en temps réel.</br></br>
 Les étapes architecture :</br>
1- Generation des données et envoie aux topics MQTT</br>
2-  Réception des données sur un broker MQTT</br>
3- node red: prend les données du MQTT et envoi ces dernier à influxdb</br>
(source de données de grafana)</br>
4- Tableau de bord grafana.</br>

### Architecture

![alt text](https://github.com/nadir1805/big-data-exam/blob/main/architecture%20examen.png)

### Simulation de données avec python

J'ai utilisé une script avec python (producer.ipynb) pour la génération de données en temps à la place des capteurs, données génerer: AIR & Process Temperature, Rotaion, tool ...</br>

![alt text](https://github.com/nadir1805/big-data-exam/blob/main/simulation.PNG)

### MQTT

![alt text](https://github.com/nadir1805/big-data-exam/blob/main/MQTT.png)

### Node-red

![alt text](https://github.com/nadir1805/big-data-exam/blob/main/Node-Red.png)

### InfluxDB(source de données pour grafana)

##### choisir les données a mettre en grpaphique 

![alt text](https://github.com/nadir1805/big-data-exam/blob/main/InfluxDB.png)

##### géneration du code graphique

![alt text](https://github.com/nadir1805/big-data-exam/blob/main/InfluxDB2.png)

### Tableau de bord grafana

Règles de génération du dashboard:

1- choix d'une structure(squelette) adapté et clair
2- Placement des données en haute vers le bas( du général au détail) et les données importants du coin gauche à la droite
3- double de margin 
4- couleur adapté aux niveau de chaque variable


![alt text](https://github.com/nadir1805/big-data-exam/blob/main/GRAFANA.png)
