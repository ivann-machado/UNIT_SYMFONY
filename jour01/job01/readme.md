Etape 1
![alt text](/screenshot/jour01/job01/etape01.jpg?raw=true)

Etape 3
image: image utilisée
container_name: nom du container
working_dir: emplacement de l'application dans l'os de l'image
volumes: attribution des voluments aux emplacements/dossiers de l'image
networks: affiliation du network
ports: declaration des ports de sortie du container
depends_on: dépendance de services
environment: variables d'env
driver: type du driver de network, par defaut bridge, pour un network sur container dans une même machine

Etape 4
listen: port
root: racine de l'application
index: déclaration de noms de fichiers index
location /: match toutes les requêtes qui ne sont pas matcher par des "location" plus précises
try_files: fallback de la requête avec $uri: chemin de la requête., suivi du fichier php et de la query si présent
location ~ \.php$: match ce qui se termine par .php
fastcgi_pass: adresse du moteur php
fastcgi_params: instruction du fichier pour requêter le moteur php
location ~ /\.ht: match ce qui commence par .ht dans la requête
deny all: block les requêtes

Etape 5
FROM: image à fork
RUN 1: Mets à jour et install curl, git et unzip
RUN 2: Télécharge et installe composer

Etape 6:
![alt text](/screenshot/jour01/job01/etape06.png?raw=true)


Etape 7
![alt text](/screenshot/jour01/job01/etape07.jpg?raw=true)
![alt text](/screenshot/jour01/job01/etape07b.jpg?raw=true)
![alt text](/screenshot/jour01/job01/etape07c.jpg?raw=true)
exit

