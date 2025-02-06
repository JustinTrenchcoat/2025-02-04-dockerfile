# 2025-02-04-dockerfile

```bash
docker run \
 --rm\
-it \
-e PASSWORD = "password"\
-p 8787:8787 \
-v /$(pwd) :/home/rstudio/work \ 
rocker/rstudio:4.4.2
```
