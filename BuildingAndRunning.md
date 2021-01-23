# Build and run:
This is how you run & build images for locally. If you want to push your images to DockerHub. Check <a href="INSERT_LINK">`PushingToDockerHub.md`</a>
### To build:<br>
Without name:<br>
> docker build .

With name:<br>
> docker build -t ImageName .

### Running image:
> docker run -d -p [ExtPort]:[IntPort] NAME/ID

