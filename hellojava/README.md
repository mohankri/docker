
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
