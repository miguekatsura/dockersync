FROM php:7.4-apache
RUN apt update && apt-get install -y nano 
RUN apt-get install -y git
WORKDIR /var/www/html
RUN echo "SOY MIGUEL ANGEL DE SEGUNDO DE ASIR" > index.html
RUN echo "<?php phpinfo(); ?>" > info.php