# icecreamshopweb

Contains 2 sub repositories: icecreamshopapi made by Django, icecreamshopfront made by Angular.

## Deployment

git submodule init

git submodule update

cd icecreamshopapi

docker-compose up -d

the running docker containers:
- nginx
- django
- db

## To access the web

- By localhost:

  Use http://0.0.0.0:1337/

- By docker container ip address

  Get ip address of the nginx docker container using

  docker inspect {container-id}

  Then use http://{container-ip-addr}
  
  
