### Create and Dockerize a Go application

### Prerequisite


* Docker installed
* Go installed


To install **go** refer to the below – https://www.educative.io/edpresso/how-to-install-go-on-ubuntu

### **Creating a Go Application**

* To start below first run the below command:-

```
go mod init
```

* To run the go file first install the **gorilla/mux package** and declare the path. To install the package run the below command:

```
go get github.com/gorilla/mux
```

* To run the application:

```
go run main.go
```

### **Dockerizing a Go Application**

* Make a Dockerfile in the same directory 

* Run the Dockerfile by running the following command:

```
docker build -t mygo .
```

* To run the image created by the Dockerfile run the command:

```
docker run -d -p 8081:8081 mygo:latest
'''


Now we have successfully created and deployed the Go Application