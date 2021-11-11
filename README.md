# docker-app-sample
Docker sample application

# build

```
docker build -t docker-app-sample:0.1.0 .
```

# look inside container

```
$ docker run -ti --rm docker-app-sample:0.1.0 ls -l    
total 28
-rw-r--r-- 1 root root   104 Nov 11 06:16 Dockerfile
-rw-r--r-- 1 root root 11357 Nov 11 06:03 LICENSE
-rw-r--r-- 1 root root   112 Nov 11 06:18 README.md
-rw-r--r-- 1 root root   104 Nov 11 06:17 app.py
-rw-r--r-- 1 root root    12 Nov 11 06:17 requirements.txt
```