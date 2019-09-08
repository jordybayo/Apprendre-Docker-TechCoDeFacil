FROM youngdevps/apache-ubuntu
ADD . /var/www/html
RUN apt-get update
RUN apt-get install apache2
ENTRYPOINT apachectl -D FOREGROUND
ENV name youngdevpsProject

