# docker
Docker with Common Development Profiles

**Java**

docker build -t myjava .

docker run --rm myjava

**Node.js**

docker build -t mynode-server .

docker run --rm -it -p 8087:80 mynode-server

**PHP**

docker build -t myphp-server .

docker run --rm -it -p 8090:80 myphp-server

**Python**

docker build -t mypython-server .

docker run --rm -it -p 8089:5000 mypython-server
