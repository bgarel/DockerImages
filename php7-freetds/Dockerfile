FROM bgarel/php7
MAINTAINER Benjamin GAREL <bgarel@hotmail.com>

RUN apt-get update && apt-get -y install freetds-common freetds-bin tdsodbc && rm -rf /var/lib/apt/lists/*

EXPOSE 80 

CMD ["/usr/sbin/apache2ctl", "-D", "FOREGROUND"]

