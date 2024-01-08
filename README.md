This repository consists of nginx server which serves static thumbnails.

The server copies files in the thumbnails folder into its static web files folder.

## How to run

1. Create a docker image using Dockerfile
2. Run docker image

## Usage

To access a thumbnail:

    {ip}/thumbnails/{filename.extension}
