# Spring-boot-docker-demo >> Please change the branch to "dev"
It's just a sample application, in which I have created a demo Spring-boot application and dockerized it with the help of the docker file and some commands.

# Docker Commands to remember:

// To build a docker image
1. docker build -f Dockerfile -t docker-spring-boot .
    >> "-f" to specify the docker location
    >> "-t" tag, the docker image name
    >> " . " it represents the current directory

// To run the docker image
2. docker run -p 8085:8085 docker-spring-boot
    >> " -p " port, specified in the "application.properties" file
    >> " docker-spring-boot " name of the docker image

3. If you change/add any method in the java application 
    >> rebuild the project
    >> maven "clean" and "install" run it
    >> run the Step1 in the terminal.
   

