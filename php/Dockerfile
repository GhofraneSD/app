from ubuntu:16.04
WORKDIR /var/www/html
copy index.php index.php
copy config.php config.php
RUN apt-get update
RUN apt-get install -y mysql-server
RUN apt-get install apache2 php libapache2-mod-php php-mcrypt php-mysql php-curl php-xml php-memcached
RUN service apache2 restart