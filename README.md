# docker-setup-example
This repository is an example of setting up the containers for running the romenext rev3 app. There are three containers to set up: the mysql container, the neo4j container and a custom wildfly container running the romenext app.Setup instruction files are included in each folder. Please try to set up the environment using the txt instruction files from scratch. The existing conf folder and data files are just provided as the examples. 

I have uploaded the custom image to build the romenext app container to docker hub. Please take a look at romenext_app_container_setup to set up the wildfly container running the romenext app. 

Updates in May:
I have updated romenext to work with Neo4j 4.2. To set up a neo4j 4.2 container with configurations that work with romenext, please take a look at the folder docker_neo4j_4.2. The set up of the mysql container remains unchanged. 

The docker images would be updated in docker hub. Use the tag "yourname4.2". For example, docker pull emptylot/romenext_rev3:betty4.2 will pull an image use betty's ip and it's compatiable with neo4j 4.2. 
