#  directory listing script with docker
- original directory listing script is developed by Evoluted and provided in [www.evoluted.net](https://www.evoluted.net/blog/development/php-directory-listing-script).
- php-apache docker image is used.
- [php-markdown](https://github.com/michelf/php-markdown) developed by Michel Fortinis used.
  
## setup
1. put index.php and .htaccess into the directory to be mounted.
2. fix volume and port in docker-compose.yml  
3. run ```docker compose up```
