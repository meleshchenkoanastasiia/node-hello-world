# Node Hello World

Simple node.js app that servers "hello world"

Great for testing deployment process

## Run It

`npm start`

## Dockerfile
building the image: 
```
docker build -t hello-world .
```
running the image:
```
 docker run -p 3000:3000 hello-world
```
