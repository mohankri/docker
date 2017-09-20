
# Create Dockerfile
```
FROM ubuntu
CMD  echo "hello world"
```

# Build Docker Image
```
docker image build -t helloworld .
``
# List Docker Image
```
docker image ls
```
# Run docker image
```
docker container run helloworld
```
