# discovery-server


Default port for config server is 8761

**Below mentioned is the command to identify the IP address of the Eureka server**

D:\Intellj\workspace\GITHUB-Microservices-shweta>docker inspect -f '{{range.NetworkSettings.Networks}}{{.IPAddress}}{{end}}' discovery-server

**Below menitoned is the command to check the connectivity from other container to see if the connectivity exists**

curl -X GET http://172.17.0.3:8761

docker ps
docker run --help
