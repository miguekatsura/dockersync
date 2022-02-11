FROM php:7.4-apache
RUN apt update && apt-get install -y nano 
RUN apt-get install -y git
WORKDIR /var/www/html
RUN echo "SOY MIGUEL ANGEL BAUTISTA AGUILAR" > index.html
RUN echo "<?php phpinfo(); ?>" > info.php