FROM php:7.4-apache
RUN apt update && apt-get install -y nano 
RUN apt-get install -y git
WORKDIR /var/www/html
RUN echo "MUY BUENOS DIAS, ME LLAMAN BAUTISTA" > index.html
RUN echo "<?php phpinfo(); ?>" > info.php