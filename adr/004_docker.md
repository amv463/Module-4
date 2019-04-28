# Choice of Docker containers

#Status: accepted

#Context:

Docker is a application that packages applications with needed components and 
deploys them with the use of containers, allowing for applications to be 
effortlessly sent to various machines or deployed to them. 

#Decision:

Docker allows for the application to be quickly configured, isolated in 
containers and rapidly deployed. Furthermore, it has the ability to effortlessly
provide available images from the Docker Hub instead of having to install and 
configure specific software for the web server. 

#Consequences:

Any machine that wishes to run applications using this software can be deployed 
without having to install specific software components. 
