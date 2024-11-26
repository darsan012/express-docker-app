# Trying out dockerization of the node application
## To create the docker image
```bash
docker build -t <folder name> .
```

## Running the docker image
```bash
docker run -p 3000:3000 <folder name>
```

### Your app is running on localhost:3000

## Stopping the app
 - First find out the process name of the docker image
 ```bash
 docker ps
 ```
 - Stop the application
 ```bash
 docker stop <CONTAINER_ID_OR_NAME>
 ```
