
# Create Dockerfile
```
FROM openjdk
CMD  java -version
```

# Build Docker Image
```
docker image build -t hellojava .
```
# List Docker Image
```
docker image ls
```
# Run docker image
```
docker container run hellojava
```

#Image reduction
```
Follow hub.docker.com openjdk and it's tags
Specify the tags with the least size in  Dockerfile to create image from

FROM openjdk:jdk-alpine
```
