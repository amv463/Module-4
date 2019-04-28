# Choice of Docker Compose

#Status: accepted

#Context:

Docker Compose is a popular alternative to tradictional Docker that is used for 
defining and running multi-container Docker application. In addition, you can 
define multiple services in a single YAML file.

#Decision:

Due to the ease of use for deploying applications through the use of the two 
commands 'docker-compose up -d' and 'docker compose down', I chose to convert
a shell script with Docker commands to Docker Compose.

#Consequences:

Any machine that wishes to run applications using this software can be deployed 
without having to install specific software components. 

