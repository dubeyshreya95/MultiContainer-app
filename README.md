# MultiContainer

# Dockerrun.aws.json:
in case of only one dockerfile present, elastic beanstalk can create a container using that file but in case of multicontainer app there are multiple dockerfiles and it gets confused. For multi container app we need to create a Dockerrun.aws.json which is used by ECS(elastic cloud service). Here we specify how it needs to create container, here we can provide image names that it can pull from docker hub to create containers.
