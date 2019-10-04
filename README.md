This repository allows to deploy a very simple nginx webserver and a nginx proxy which authenticate request by using basic .htpasswd based authentication, and redirects them through the webserver.

## Modify the .htpasswd file in /data if you want to add more credentials
Currently, the only credentials added are user1: pass1

## Run the webserver and the proxy
`docker-compose up`
`docker-compose -f docker-compose-auth.yml up`

## See them in a web browser
http://localhost:8080
http://localhost:8081
