# PHP MySQL Apache PHPMyAdmin Dockerized

This is a start point to begin a docker-hosted development for a PHP Mysql application.

# how to setting

Default:

- Apache 8000 Port
- PhpMyAdmin 8001 Port
- VSCode 8002 port
  - default password : 92e75b24ac898c56bae737fe20438dca3951ab31103311abf60f044e2648f678

How to modify:

- Find the .env file and change the numbers below.

```md
APACHE_PORT=8000
PHPMYADMIN_PORT=8001
VSCODE_PORT=8002
```

- How to change the vscode password

Modify password value in .config/code-server/config.yaml

## For more information

[visit this post](https://ayoubb.com/technology/dockerize-apache-mysql-php-stack/)

## License

[MIT](https://choosealicense.com/licenses/mit/)
