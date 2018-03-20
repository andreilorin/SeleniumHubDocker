# Selenium Hub Setup for Docker

![gif](dockergif.gif)

Copy the [dockerfile](docker-compose.yaml) to your machine and from the same folder run
`docker-compose up`
this will download the images and run the containers for the hub and nodes.

If you want to create more instances out of the same image
`docker-compose up --scale chrome_node=4`

To stop and remove the containers(the images will not be removed by these commands)
```
ctrl + c
docker-compose down
```

