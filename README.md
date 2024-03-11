# ELK-Portable-Edition
Une version portable (Windows) d'ELK, minimaliste, pour être utilisée pendant un cours, une formation, ou pour un usage ponctuel... sans installation préalable, tournant avec [Java Runtime Environment](https://www.java.com/fr/download/manual.jsp)

Permet d'utiliser un ELK tout frais en moins de 10 secondes !

![image](https://github.com/artafak/ELK-Portable-Edition/assets/38442391/8a3e5bdb-0c90-4a5c-bda4-c42670c41193)





# Contenu
L'archive contient les éléments suivants :
- cerebro 0.8.1
- elasticsearch 6.4.3
- kibana 6.4.3
- logstash 6.4.3

D'autres éléments ont été ajoutés, pour le côté confort :
- curl 7.62
- Cmder 1.3.12.915

Le tout est utilisable sans installation, directement en version portable. 
Il est nécessaire que JavaRE soit installé sur le système
_un package installable de Jre est contenu dans l'archive, prêt à être déployé (droits d'admin requis)_




# Usage
Décompressez l'archive, et exécutez **launcher.bat**
Le script Batch exécutera en mode fenêtré les instances d'_Elasticsearch_ et de _Kibana_ en mode local, sur votre poste
![image](https://github.com/artafak/ELK-Portable-Edition/assets/38442391/72f91404-5758-44e0-a457-948202a343a8)



# Usage pédagogique et exemples
Un dossier _examples_ à la racine de l'archive contient 3 exercices très simples pour apprendre à utiliser ELK.

## Exercice 1
**SNCF non conformités** est un fichier CSV (Microsoft Excel) listant les anomalies constatées dans les gares sur le réseau SNCF. 
Ce sont des données d'exemple, fournies avec le fichier de configuration en YAML pour appréhender l'usage des filtres avec Logstash


## Exercice 2
**Serveur Web de la NASA**
le but est d'utiliser la fonction de mapping/géolocalisation de Logstash pour extraire les adresses IP contenues dans un fichier LOG sous format Apache, pour les afficher et les géolocaliser sur une carte du monde.


## Exercice 3
**Load balancing**
Fichier de journalisation d'un [HAProxy](https://www.haproxy.org/), pour effectuer de la recherche d'adresse de sites web suspects à travers le dashboard de Kibana




# Ressources et téléchargement

Pour télécharger l'archive, et accéder aux exercices, utilisez [ce lien pour accéder à Google Drive](https://drive.google.com/drive/folders/1LAawIGqgRaiMHCMxinBVgDI-iB-wzL8t?usp=sharing).
