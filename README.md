# docker-compose101
A repository to do quick training about docker-compose

## compose theory
* What is docker-compose ?
* A tool to define an application with several container composing it and their configuration and interaction
* [https://docs.docker.com/compose/overview/] (https://docs.docker.com/compose/overview/)

* Notions:
	* docker-compose yaml file
	* command line tool
	* functionalities

	
	
## compose practice

Install docker-compose on your machine: [https://docs.docker.com/compose/install/] (https://docs.docker.com/compose/install/)

Use this repository: [https://github.com/g-dury/docker-compose101] (https://github.com/g-dury/docker-compose101)


Latest docker-compose version: 1.24.0

1. Create our own docker-compose.yaml
	* look at `template.yaml` and unerstand the different notions:
		* version
		* services
		* image/port/environment
	* Add a service to this docker-compose file with image `hello-world` 
	* start it with `docker-compose -f template.yaml up`
	* understand the logs and what is happening
	* reference for all the possible options: [https://docs.docker.com/compose/compose-file/] (https://docs.docker.com/compose/compose-file/)

2. Docker-compose CLI
	*  Documentation: [https://docs.docker.com/compose/reference/overview/] (https://docs.docker.com/compose/reference/overview/)
	*  Notions:
		* `docker-compose up -d`
		* `docker ps -a` to see all the containers running
		* `docker-compose down`
		* `docker-compose build`

	* You can try the build command by using the default `docker-compose.yaml` file in the current folder, it will build the custom image necessary when you boot up the stack

	
	