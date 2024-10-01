Steps:

## Install git-core if not installed in your system
=> sudo yum install git-core -y

## Download the repo folder from github 
=> cd /etc/
=> git clone https://github.com/sajib-saiful/docker-monitoring.git

# Go to the repo folder
=> cd docker-monitoring/

# Run the docker-compose.yml
=> docker compose up -d

# Check the containers
=> docker ps -a

