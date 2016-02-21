To build the image run the command:

sudo docker build -t nabil/tomcat .

stART network:
sudo docker network create mynetwork

To start the container run the command:

sudo docker run -p 8080:8080 --net=mynetwork nabil/tomcat


