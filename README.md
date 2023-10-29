# Lamp-Wordpress

This Docker Compose file sets up three services:

    db: MySQL database container
    wordpress: WordPress container
    phpmyadmin : PHPMyAdmin container for database management

Create a Dir Wordpress ex: mkdir Wordpress
then
git clone https://github.com/shoponurl/Lamp-Wordpress.git

Run Docker Compose

docker-compose up -d

Access WordPress

When the services are up and running, visit http://localhost:8050 in your web browser to set up WordPress.

Access PHPMyAdmin
PHPMyAdmin on http://localhost:8282
