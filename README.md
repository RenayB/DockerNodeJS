#Dockerizing a Node.js Web Application Example 

An example of how to get a Node.js application into a Docker container. 

##How to Run
	1. If you don't have Docker,  install it first.  https://docs.docker.com/get-started/
	2. Navigate to the project .
	3. Build the docker image using the following command `docker build .`
	4. Run the image using 'docker run -p 49160:8080'
	5. Call the app using 'curl -i localhost:49160'