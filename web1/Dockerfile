FROM php:8.1-apache
COPY ./src /var/www/html/
#COPY ./apache2/000-default.conf /etc/apache2/sites-available/000-default.conf
# Enable apache rewrite
#COPY mobile.conf /etc/apache2/sites-available/mobile.conf
#COPY slick.conf /etc/apache2/sites-available/slick.conf
#RUN a2dissite 000-default.conf
#RUN a2ensite mobile.conf
#RUN a2ensite slick.conf
#
#RUN chown -R www-data:www-data /var/www/html/
#CMD apachectl -D FOREGROUND
