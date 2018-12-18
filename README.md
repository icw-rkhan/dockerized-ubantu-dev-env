# Dockerized dev env on Ubuntu 16.04 LTS
##### Dockerized dev env with tools e.g. java 8, maven, git, mysql, node etc on Ubuntu 16.04 LTS

###### Shared volume:
	> c:/qlogic-projects:/qlogic-projects)


#### Build/Run Docker Image
	$ docker build -t rk-ubantu-env .
  
#### Build/Run Docker Image
	$ docker run -v c:/qlogic-project:/qlogic-projects -ti rk-ubantu-env 
