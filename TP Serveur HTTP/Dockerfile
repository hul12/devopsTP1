# Utilise l'image de base httpd:2.4 (Apache HTTP Server)
FROM httpd:2.4

# Copie le fichier index.html dans le dossier racine du serveur web
COPY ./index.html /usr/local/apache2/htdocs/
COPY ./httpd.conf /usr/local/apache2/conf/httpd.conf

# Expose le port 80 pour accéder au serveur web
EXPOSE 80
