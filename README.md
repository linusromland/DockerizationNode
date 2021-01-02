# DockerTesting

Testing out docker containers for preparation of my move to K8s servers!


# Notes for myself:

to build:
(without name)
docker build . 
(with name)
docker build -t ImageName .

to run:
docker run -d -p [EXTERNAL PORT]:[INTERNAL PORT] IMAGE NAME/ID