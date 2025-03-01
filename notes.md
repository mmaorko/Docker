if i want to run the docker and nginx this is the command 
```
docker run -p 80:80 nginx (Basic command)
docker run -d -p 80:80 nginx (when we run the docker my terminal is busy other work is not possible that's why we use -d (which means deamon it is run Nginx in the foreground using the command line, use this command)
docker run --name=my-nginx -d  -p 80:80 nginx (if i want to add name)
docker run --name=my-nginx --restart=always -d  -p 80:80 nginx (when my server is shutdown nginx service are automatically off which is not automatically open every time manually on nginx if i need to automatic run using this command `--restart=always`)
```

if you want to check how many container is running `docker ps -a` and if you want stop and delete
```
docker stop container-id (for stop)
docker rm container-id(for remove)
docker 
```
If you want to check all docker image this command 
```
docker images (for check all docker images)
docker rmi REPOSITORY:TAG
docker pull software_name (if i want to download)
