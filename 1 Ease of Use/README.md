# Running a container
```sh
docker run -d -p 80:80 docker/getting-started

```
# Viewing the image
```
docker images --all
```

# Viewing the container
```
docker ps -a
```
# Logs
``` 
docker logs [☢️️name of container️️️️️️️️☢️]
```
# Inspect
``` 
docker inspect [☢️️name of container️️️️️️️️☢️]
```
# Stats
``` 
docker stats [☢️️name of container️️️️️️️️☢️]
```
# Exec
``` 
docker exec -it [☢️️name of container️️️️️️️️☢️] /bin/sh
```
# Stop 
``` 
docker stop [☢️️name of container️️️️️️️️☢️]
```
# start 
``` 
docker start [☢️️name of container️️️️️️️️☢️]
```
# Restart 
``` 
docker restart [☢️️name of container️️️️️️️️☢️]
```
# Kill 
``` 
docker kill [☢️️name of container️️️️️️️️☢️]
```


# remove container 
``` 
docker rm [☢️️name of container️️️️️️️️☢️]
```

# remove image 
``` 
docker rmi [☢️️name of image☢️]
```