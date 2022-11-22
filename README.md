## Docker-Compose for spinning two containers with a network

### How to use this template?
For using this docker compose, you should have two services atleast and this docker compose will connect those services to each other through a docker network. 
You just have to mention the image name (from you local or from docker hub) in place of `<Image-name>`. Then you have to give the container name in place of `<desired-container-name>`. If you have any env variable you can define them using `<env-var>` & `<env value>`. Then you have to map the ports here in place of `<host-machine-port>` & `<container-port>`. 

For running the template, you just have to type `docker compose up`.