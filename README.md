docker-heritrix
===============

docker container with **3.4.0-SNAPSHOT**

# Run

```console
$ mkdir path/to/persistent/heritrix-data
$ docker build . -t heritrix
$ docker run -it -p 8443:8443 -v path/to/persistent/heritrix-data:/mnt/heritrix-data heritrix
$ curl https://heritrix:heritrix@localhost:8443
```
  
