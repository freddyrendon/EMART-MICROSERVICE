# EMART-MICROSERVICE

## Prerequisites
- Vagrant must be installed.

## Setup

### 1. Clone the source code of EMART_MICROSERVICE App:
```bash 
git clone https://github.com/freddyrendon/EMART-MICROSERVICE.git
ls
cd EMART-MICROSERVICE
```
### 2. Bring up the containers from the docker-compose file:
```
docker compose up -d
docker compose ps
docker ps -a
ip addr show
```
### 3. Access the Application:
Open your browser and navigate to:
```http://VM-Ip:80```

### 4. Cleanup
To delete and clean up, use the following commands:

```bash

docker compose down
docker system prune -a
exit
vagrant halt
vagrant destroy

```
