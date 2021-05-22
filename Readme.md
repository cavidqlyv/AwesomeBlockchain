# P06	Blockchain as distributed system

## Joining the blockchain

 1. Install [Docker](https://www.docker.com/)
 2. Install [Docker-Compose](https://docs.docker.com/compose/)
 3. `docker-compose up`

Setup will spin of next services:
- http://localhost:8000/node.html -- User interface   
- http://localhost:8080 -- LoadBalancer
- http://localhost:5001 -- Blockchain
- http://localhost:5002 -- Blockchain
- http://localhost:5003 -- Blockchain

Stop all containers: `docker ps -aq | xargs docker stop`


This repo is not fully developed, if you have some questions contact with us.
