#  directory listing script with docker
- original directory listing script is developed by Evoluted and provided in [www.evoluted.net](https://www.evoluted.net/blog/development/php-directory-listing-script).
- [php-apache](https://hub.docker.com/layers/library/php/8.2-apache/images/sha256-0f3c1f8c21a44809c3fd3c10b6d8f296b65fd3bf514a41b9337a2cb809bff89e) docker image is used.
- [parsedown-extra](https://github.com/erusev/parsedown) developed by Emanuil Rusev is used.
  
## setup
1. put index.php, .htaccess, and module directory into the directory to be mounted.
2. fix volume and port in docker-compose.yml, if required.   
3. run ```docker compose up```
4. access http://localhost:8000
