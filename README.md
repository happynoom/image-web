# image-web
Docker image with java 8 and tomcat 8.

# Usage
Build a new image

```
$ git clone https://github.com/happynoom/image-web.git
$ sudo docker build -t image-web ./
```

We can now start a new container based on this image:
```
$ sudo docker run -d -p 8090:8080 image-web
```

view web page by open `http://localhost:8090`