# docker_spring_petclinic
Image docker for running a simple spring java application sample

Spring petclinic running on Tomcat.
Available at: http://localhost:8080/petclinic/

Construction of the image:
Build the docker image:
sudo docker build -t springclinic .

Run the image:
sudo docker run -p 8080:8080 firwayer/docker_spring_petclinic

Access to the container:
sudo docker ps ==> got an ID
sudo docker exec -it ID bash

