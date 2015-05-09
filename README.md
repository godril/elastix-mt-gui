# elastix-mt-gui - Elastix MT GUI



This code is distributed under the GNU LGPL v2.0 license.


## Introduction


## Installation

Install the git package and follow the instructions.


```bash
#System packages
yum -y install system-config-date system-config-firewall-base system-config-keyboard system-config-language system-config-network-tui system-config-users
#Packages for this implementation.
yum -y install dialog vim mc screen git nmap
#Packages for web server.
yum -y groupinstall "Web Server"
#Packages to the database.
yum -y install mysql-server mysql-connector-odbc
#Packages for php
yum -yinstall php php-cli php-common php-devel php-gd php-imap php-mbstring php-mcrypt php-mysql php-pdo php-pear php-pear-DB php-process php-soap php-xml

Cloning repository
cd /usr/src/
git clone https://github.com/elastixmt/elastix-mt-gui.git
```
