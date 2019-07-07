# Node-Docker-Test 

----
## Build Docker Image
> $ docker build -t <your username>/node-web-app .

## Run the image
> $ docker run -p 49160:8080 -d <your username>/node-web-app

# Get container ID
>$ docker ps

# Print app output
>$ docker logs <container id>

# Example
Running on http://localhost:8080

#Test
>$ curl -i localhost:49160
*navigate to localhost:49160 on your browser
