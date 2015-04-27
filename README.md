# dashing-docker-bootstrap
A simple bootstrap package for Dashing on Docker with Docker-compose

## To get started:
- Install a docker-environment (such as boot2docker) and docker-compose (https://docs.docker.com/compose/install/)
- Start the container: ```docker-compose up```
- Dashing will be running on port 8080 in your docker-environment (if using boot2docker, use ```boot2docker ip``` to find out where)
- The directories ```dashboards```, ```jobs```, ```config```, ```widgets``` and ```public``` have been mounted, and you can start modifying them to your taste!

Based on frvi's dashing-docker container from here: https://registry.hub.docker.com/u/frvi/dashing/ .
