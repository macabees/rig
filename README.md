# RIG (Random Identity Generator)
The 'rig' command can be used for generating test user data for a database.

## RIG (Project Info)
[Website](http://rig.sourceforge.net/)

## Docker Hub
[Website](https://hub.docker.com/r/macabees/rig/)

## Build image
`$ docker build -t macabees/rig:latest .`

## Docker Push
`$ docker push -t macabees/rig:latest`

Note: requires `docker login`

## Run image
`$ docker run -it --rm macabees/rig`
