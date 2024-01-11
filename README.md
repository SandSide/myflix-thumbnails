## Description 

A microservice apart of `Myflix` project created using Nginx sever to server static images as thumbnails.

## Features

 - **Serve Static Images**: Allows applications to access static images stored on the server.

## Usage

1. Place static videos inside `/thumbnails` folder.
2. Build and run docker image.
3. Access videos using `ip:port/thumbnails/{filename}`.

## Deployment

### Using Docker:

1. Create an docker image from `Dockerfile` in `/src` folder.

```bash
docker build -t {image-name} .
```

2. Run the docker image.

```bash
docker run -d -p 5000:5000 --name {container-name} {image-name}