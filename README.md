# docker-setup-example
This repository is an example of setting up the containers for running the romenext rev3 app. There are three containers to set up: the mysql container, the neo4j container and a custom wildfly container running the romenext app.Setup instruction files are included in each folder. Please try to set up the environment using the txt instruction files from scratch. The existing conf folder and data files are just provided as the examples. 

Updates:

I have uploaded the custom image to build the romenext app container to docker hub, so there is no need to follow the instructions in wildfly_docker_workspace to rebuild the image. Please take a look at romenext_app_container_setup to pull the image and run the container instead. 
