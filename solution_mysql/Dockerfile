FROM mysql

RUN apt-get update
RUN apt-get install -y wget
RUN wget -c https://repo.mysql.com//mysql-apt-config_0.8.14-1_all.deb
RUN apt-get install -y lsb-release
RUN export DEBIAN_FRONTEND=noninteractive
RUN dpkg -i mysql-apt-config_0.8.14-1_all.deb
RUN apt-get update
RUN apt-get install -y mysql-shell
