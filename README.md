# EMART-MICROSERVICE

# Must have Vagrant Installed

# Clone source code of EMART_MICROSERVICE App
git clone https://github.com/freddyrendon/EMART-MICROSERVICE.git
ls
cd EMART-MICROSERVICE

# Bring up the containers from docker-compose file
docker compose up -d
docker compose ps
docker ps -a
ip addr show

# Go to browser enter http://VM-Ip:80

# Delete 
docker compose down
docker system prune -a
exit
vagrant halt
vagrant destroy 