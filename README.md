# BIG-Data Poc

Analyser des Tweets en utilisant Flume, et Hadoop et Hive.

C'est quoi Hadoop ? 

Hadoop tout simplement un framework open source qui fournit une implémentation du MapReduce de google et de son système de fichiers distribué. Le MapReduce a été conçu pour faire
du traitement paralléle à l'aide d'un cluster. Haddop implémente bien ceci en facilitant la création d'application distribué au niveau du stockage et du traitement des données.


C'est quoi Flume ? 

 - Flume fait partie de l'ecosysteme Hadoop, il permet de créer des routes pour relier une source à une cible via un canal d'échange.
 - Le Channel utilisé par flume est une zone tampon qui permet le stockage des messages avant qu'ils soient consommés.
 - Le Sink : consomme  par lot les messages en provenance du Channel pour les écrire dans une déstination comme Hadoop (HDFS).
 
 
C'est quoi Hive ? 
 
Hive a été développé par FB pour la gestion de son réseau social, il s'agit d'une infrastructure informatique comparable au datawarehouse qui fournit
des services de requétes et d'agrégation de trés gros volumes de données stockés sur un système de fichiers distribué de type HDFS.
Hive est prés installé sur Hadoop





Comment procéder ? 

1 - Mettre en installer place Haddop
2 - Mettre en Place et installer en place Fulme
3 - Créer une application tweeter   "https://dev.twitter.com/apps/"
4 - Configurer Flume pour récupérer les donées de l'application Tweeter
5 - Configurer Flume pour en précisent l'emplacement du HDFS (Ou il va écrire les tweets)
6 - Démarer Flume et Tester si les données sont bien écrits sur HDFS
7 - Configurer Hive Pour faire l'analyse des données 
8 - Tenter de faire des requêtes sur les données (HiveQL, langage de rquéte basé sur SQL)
 



