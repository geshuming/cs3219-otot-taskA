# Dockerizing nginx reverse proxy server 

## Setup and running the server
1. Build the docker image with the following command:
```
docker build --tag cs3219-otot-nginx .
```

2. Run the image with the following command:
```
docker run --publish 8080:80 cs3219-otot-nginx
```

3. Access the nginx web server through http://localhost:8080