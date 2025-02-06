# 2025-02-04-dockerfile


this whole thing is with Chapter 12 from the lecture notes.
the      
```
username: ${{ secrets.DOCKER_USERNAME }}
password: ${{ secrets.DOCKER_PASSWORD }}
```
requires you to add docker username and password to the github actions' secrets

```bash
docker run \
 --rm\
-it \
-e PASSWORD = "password"\
-p 8787:8787 \
-v /$(pwd) :/home/rstudio/work \ 
rocker/rstudio:4.4.2
```

```bash
docker run \
 --rm\
-it \
-e PASSWORD = "password"\
-p 8787:8787 \
-v /$(pwd) :/home/rstudio/work \ 
rocker/rstudio:4.4.2
```


```
docker build --tag mycontainer .
```

```
docker login -u <USERID>
```


