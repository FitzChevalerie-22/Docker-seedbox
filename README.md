# Docker-seedbox
An other configuration for make a simple seedbox with Traefik, Rutorrent, Emby and monitoring.

You need some subdomain for the project. 
One for 

# Traefik configuration

$ sudo mkdir /opt/traefik
$ cd /opt/traefik/
$ sudo touch 600 acme.json

Create your user/password with HTPASSWORD for docker-compose.yaml

$ sudo apt-get install apache2-utils -y
$ sudo echo $(htpasswd -nbB user "password") | sed -e s/\$/\$\$/g



