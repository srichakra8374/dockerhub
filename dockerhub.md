## Docker hub

1. created a docker hub account .

2. created a new repository in docker hub.

3. used tag command to tag my image to the "dockerhub" repository.
```commandline
   DOCKER TAG <IMAGE_NAME>
   eg : docker tag myflaskapp
   ```

4. Pushed the changes to docker repository
```commandline

   DOCKER PUSH <NAMESPACE/REPOSITORY:TAG>
   eg : docker push srichakra769/dockerhub:latest
```
5. Pushed image from user bobby to my local
```commandline
    docker pull <NAMESPACE/REPOSITORY:TAG>
    eg : docker pull bojyanath/dockerrepo:latest
```


