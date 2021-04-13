HA Swarm and Docker Compose on GCP

Quick start
-------------------
Download and extract / git clone the files
Docker-Compose (Development used)
Run : docker-compose up -d
Docker HA Swarm with 3 Manager(Production used)
Run : docker swarm deploy -c docker-compose.yml -c docker-compose.prod.yml myweb-app


