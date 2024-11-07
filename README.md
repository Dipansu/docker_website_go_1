# Created a Docker image for a website using golang

The templates folder carries your index.html files and the images which are refered in the html file


# Docker commands
 ```bash
 docker build -t dw10:1 .
 docker run dw10:1
 docker run -p 80:80 dw10:1 # to run the website on port 80
 docker run -p 5000:80 dw10:1 # to run the website on port 5000
 docker login
 docker tag dw10:0.1 dipansus/dw10:0.1
 docker push dipansus/dw10:0.1
```