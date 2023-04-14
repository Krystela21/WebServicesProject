# WebServicesProject
Web Services &amp; Service Oriented Architectures: Projects // Universities Management Service + Maps 

Introduire
Project: Service de gestion d’ Universités + Service Maps

Présentation des membres de l’équipe
Membre: 
Nom:Christella ARISTOR  Email:aristorchristella@gmail.com
Nom:Qinyu ZHANG  Email:83279528@qq.com 

Introduction décrivant l'objectif général du projet
Créer un système de gestion universitaire et connecter des services cartographiques externes. Le client 
se compose de fonctions d’interface et de fonctions qui interagissent avec le serveur.

Le projet est une application de gestion universitaire qui permet à l'utilisateur de récupérer, 
ajouter et supprimer des universités, ainsi que de rechercher des filières proposées par une 
université en particulier. Le package "university.management.client" contient l'implémentation
 de l'application  client.

L'objectif principal de cette application est de faciliter la recherche d'universités et de filières, 
en offrant un accès convivial aux informations les plus pertinentes. En utilisant une API web RESTful, 
l'application permet à l'utilisateur de récupérer les données sur les universités, de filtrer par filière 
et de récupérer des détails tels que l'adresse et la localisation.

The code provided seems to be a Java program that acts as a client for a web service. 
The client interacts with the web service using RESTful APIs provided by the web service.

description：
getUniversity: checks if a university offers a specified major and prints its name, address, and location
getAllMajors: retrieves all majors offered by a university
addMajor: adds a major to a university
add: adds a university to the system
delete: deletes a university from the system
get: retrieves a university from the system
getAll: retrieves all universities from the system
The code uses the Apache CXF framework to create a web client and interact with the web 
service using RESTful APIs. The code also uses the JAXB API to serialize and deserialize Java 
objects to and from XML, which is the data format used by the web service.
