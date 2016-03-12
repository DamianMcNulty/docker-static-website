# Docker Sandbox: Static Website

Sample [Docker](https://www.docker.com) build for a static website.

## How to run

On a terminal:

```
docker build -t aelesbao/static-website .
docker run -d -p 8080:80 aelesbao/static-website
```

If you are on a Mac OS, then just run:

```
open "http://`docker-machine ip`:8080"
```
