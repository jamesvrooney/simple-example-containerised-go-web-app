# Very simple containerised Go web application

### To create the docker image:
In project root directory, execute following command:
* docker build -t my-simple-example-go-app .
  
### To run the docker image
* docker run -p 8123:8080 -d my-simple-example-go-app
* In a web browser, go to localhost:8123

[Simple containerised Golang web app](https://tutorialedge.net/golang/go-docker-tutorial/)