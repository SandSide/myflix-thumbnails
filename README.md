This repository consists of nginx server which serves static thumbnails.

The server copies files in the thumbnails folder into its static web files folder.

## How to run

1. Go to /src folder.

2. Create a docker image using Dockerfile.

        docker build -t {name} .

3. Run docker image.

        docker run -d -p {port:port} --name {container-name} {image-name}

## How to use

To access a thumbnail:

    {ip}/thumbnails/{filename.extension}
