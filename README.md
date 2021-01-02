# DockerTesting

Testing out docker containers for preparation of my move to K8s servers!


DockerHub: https://hub.docker.com/u/linusromland

DockerHub Test Repo (nodehello): https://hub.docker.com/r/linusromland/nodehello

# Notes for myself:

## Build and run:
### To build:<br>
Without name:<br>
> docker build .


With name:<br>
> docker build -t ImageName .

With name, tag and repo for use with DockerHub<br>
> docker build -t < hub-user >/< repo-name >[:< tag >] .

Running image:
> docker run -d -p [ExtPort]:[IntPort] NAME/ID

<br>

## Pushing to DockerHub
Pushing to DockerHub:<br>
> docker push < hub-user >/< repo-name >:< tag >

Pulling from DockerHub:
> docker pull < hub-user >/< repo-name >:< tag >

Running image (will download from DockerHub if not present locally):
> docker run < hub-user >/< repo-name >:< tag >

