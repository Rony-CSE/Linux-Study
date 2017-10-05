start apache2:

#$ sudo /etc/init.d/apache2 start

stop apache2:

#$ sudo /etc/init.d/apache2 stop

restart apache:

#$sudo /etc/init.d/apache restart



start mysql:

#$ sudo start mysql
or,
#$ sudo service mysql start
or,
#$ sudo /etc/init.d/mysql start

stop mysql:

#$ sudo stop mysql
or,
#$ sudo service mysql stop
or,
#$ sudo /etc/inid.d/mysql stop 

restart mysql:

#$ sudo restart mysql
or,
#$ sudo service mysql restart
or,
#$ sudo /etc/init.d/mysql restart


PROBLEM:
The requested URL /phpmyadmin was not found on this server

SOLUTION:

#$ sudo ln -s /usr/share/phpmyadmin /var/www/html/phpmyadmin
#$ sudo /etc/init.d/apache2 reload






