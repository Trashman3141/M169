# Basisimage: Apache + PHP (falls du mal PHP brauchst, sonst nur HTML geht auch)
FROM php:8.2-apache

# Kopiere den kompletten HTML-Ordner ins Webserver-Verzeichnis
COPY html/ /var/www/html/

# Port freigeben
EXPOSE 80

# Apache starten
CMD ["apache2-foreground"]
