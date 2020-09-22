# Spin up SONARQUBE using docker-compose

## Increase the virtual memory for Elastic Search
sudo sysctl -w vm.max_map_count=262144


## To start SonarQube server
Run `./start-sonar.sh`

Default login:
	Username: admin
	Password: admin


## Access the Jenkins CI server
Navigate to `http://localhost:9000`


## To stop SonarQube server
Run `./stop-sonar.sh`