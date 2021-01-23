# Pushing to DockerHub
You need to have an account on <a href="https://hub.docker.com/">`DockerHub`</a>.

### Building docker for DockerHub:
Building for DockerHub requires you to build the project with name, tag and repo.<br>
> docker build -t < dockerhub-username >/< repo-name >[:< tag >] .

### Pushing to DockerHub:
You do `not` have to create your docker repo beforehand. Pushing to a repo that doesn't exist will create it.<br>
> docker push < dockerhub-username >/< repo-name >:< tag >

### Pulling from DockerHub:
This step is not required if you just want to run the image. Check Runnning image.
> docker pull < dockerhub-username >/< repo-name >:< tag >

### Running image:
You do not have to pull the docker image before running it. If you dont have the image locally docker will download it from DockerHub.<br>
> docker run < dockerhub-username >/< repo-name >:< tag >

