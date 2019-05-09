## Managing Images through the Docker Client
`docker image ls`

To delete any image, simply run `docker image rm [IMAGE_NAME]:[IMAGE_TAG]`. If no tag is provided, Docker will assume `latest`

To download (or pull) an image from Docker Hub, run `docker image pull [IMAGE_NAME]:[IMAGE_TAG]`

## Docker Login

We can log in to Docker through the Docker Client using your Docker ID `docker login`

## Creating Images
Build your image into a container with: `docker image build -t [image_name]:[tag] [directory]`

Run the newly created image with command: `docker container run -it [image_name]:[tag]`
