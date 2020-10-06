# My docker environment

## Python

Basic python environment.

```
$ cd python/base
$ docker build -t <image name> .
$ docker run -it --name <container name> <image name>
```

Data science environment.

```
$ cd python/data-science
$ docker-compose up -d
```

## C++

C++ environment.

```
$ cd cpp
$ docker-compose up -d
```
