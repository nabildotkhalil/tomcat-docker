# tomcat-docker

0. To build the image run the command:
```
sudo docker build -t nabil/tomcat .
```
0. Start network:
```
sudo docker network create mynetwork
```
0. To start the container run the command:
```
sudo docker run -p 8080:8080 --net=mynetwork nabil/tomcat
```
