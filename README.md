Practice HA Swarm and Docker Compose on GCP

Quick start
-------------------
- Download and extract / git clone the files
- Docker-Compose (Development used) chcon -R system_u:object_r:admin_home_t:s0 docker-elk/
- Run : docker-compose up -d
- Docker HA Swarm with 3 Manager(Production used)
- Run : docker swarm deploy -c docker-compose.yml -c docker-compose.prod.yml myweb-app


