# CHANGELOG


## V0.1 
- Basic Vagrant box
    - Puphpet
    - http://192.168.56.101:9002
    - http://myapp.local:9002
    - PHP 5.6.1-1~dotdeb.1 (cli)  (to verify in comand line use "php -v")
    - Mysql-server-5.6 and Mysql-client-5.6 
    - MogoDB

## V0.2
- Backend administrations for DB
    - phpmyadmin for MySql
    - phpMoAdmin for MongoDB

## v0.3
- Frontend tools tools, packagemanagers and scripts
    - node.js installed via vagrant
        - Packages are
            "bower": "^1.3.12",
            "grunt": "^0.4.6",
            "grunt-bower-requirejs": "^1.1.0",
            "grunt-contrib-requirejs": "^0.4.4",
            "load-grunt-tasks": "^01.0.0",
            "requirejs": "^2.1.15"
    - Bower
        -   Packages are 
            "angular": "1.3.*",
            "jquery": "~2.1.1",
            "bootstrap-sass-official": "~3.2.0",
            "requirejs": "~2.1.15",
            "angular-bootstrap": "~0.11.2"

## v0.4
- ZendFramework 2 and tools and related dependencies
    - ZendFramework 2
    - Doctorine
    - Doctorine / MongoDB
    - Apiglity Skeleton
    - ZfcUser // Defalt configuration
    - Hybridauth 
    - Scn-Social-Auth // Dummy facebook configuration

## v0.5
- Updated ports for vhost, HostManager plugin is now a dependency (https://github.com/smdahlen/vagrant-hostmanager)
    - myapp.local (www.myapp.local) for main application
    - phpmyadmin.local (www.phpmyadmin.local) for phpMyAdmin interface for mySql
    - phpmoadmin.local (www.phpmoadmin.local) for phpMoAdmin interface for Mongo, this inlcudes coping over the .htaccess file

## v0.6
- Updated installation instructions and builds


## v0.7
 - Added Swagger format for API documentation
    - T o access documentation use http://myapp.local/apigility/swagger
