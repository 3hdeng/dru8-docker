# dru8-docker
drupal8 docker try

https://bitbucket.org/pypdf/mydms

//===
https://www.howtoforge.com/tutorial/how-to-install-drupal-8-with-nginx-and-ssl-on-ubuntu-15-10/


//===
https://github.com/wadmiraal/docker-drupal


Nginx + PHP-FPM (FastCGI Process Manager)


//=== https://hub.docker.com/_/drupal/
The basic pattern for starting a drupal instance is:

$ docker run --name some-drupal -d drupal
If you'd like to be able to access the instance from the host without the container's IP, standard port mappings can be used:

$ docker run --name some-drupal -p 8080:80 -d drupal
Then, access it via http://localhost:8080 or http://host-ip:8080 in a browser.

MySQL
$ docker run --name some-drupal --link some-mysql:mysql -d drupal
Database type: MySQL, MariaDB, or equivalent
Database name/username/password: <details for accessing your MySQL instance> (MYSQL_USER, MYSQL_PASSWORD, MYSQL_DATABASE; see environment variables in the description for mysql)
ADVANCED OPTIONS; Database host: mysql (for using the /etc/hosts entry added by --link to access the linked container's MySQL instance)



