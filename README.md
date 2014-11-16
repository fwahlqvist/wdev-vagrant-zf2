wdev-vagrant-zf2
================

Vagrant, ZF2, Apigility and Angular.

 ## Dependencies

1) Virtual box
    Got to https://www.virtualbox.org and download and install your machine
2) Hostmanager
    This is needed for the DNS resolutions for virtual hosts.
    To install open command prompt and type
        "vagrant plugin install vagrant-hostmanager"
        


 ## Instalation

 1) Git clone git clone https://github.com/fwahlqvist/wdev-vagrant-zf2
 2) cd wdev-vagrant-zf2
 3) vagrant ssh
 4) cd /var/www 
 5) sudo ./bin/init-build

Go grab a coffee....

To access box use 
http://myapp.local

To access phpmyadmin use
http://phpmyadmin.local

To access phpmoadmin use
http://phpmoadmin.local

To test OAUTH 2.0 use (full insructios are avalible at https://apigility.org/documentation/auth/authentication-oauth2)
 - Request the authorization code
       - Web http://myapp.local/oauth/authorize?response_type=code&client_id=testclient&redirect_uri=/oauth/receivecode&state=xyz
       - SPA http://myapp.local/oauth/authorize?response_type=token&client_id=testclient&redirect_uri=/oauth/receivecode&state=xyz


