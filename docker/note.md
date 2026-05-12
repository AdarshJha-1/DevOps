- This is all for my underdstanding not meant to teach anyone anything

# docker network

- Host
- Bridge (default)
- User defined Bridge (Custom)
- None

- MACVLAN (docker swarm)
- IPVLAN
- Overlay

## handson

- 2 tier application
- flask app (docker container) <-> MySQL (docker container) -> communication b/w them via docker network

## networking use in docker from my underdstanding

- Use for making containers communication with each other like if i backend application want to talk to running db on docker container, to enable communication we can create a separate network for them and set at the first running time of that containers as --netwrok my_network

## Volumes and storage

- For persesting data
- we can use default place to store the data like /va/lib/docker/volume/mysql-data/\_data
  or we can use a custom folder on any where on machine and link it as volume

## Docker compose

- tool to make things automatic
- YAML -> KEY : VALUE
- help in creating 1 or more containers
- configure all setting in one file only
