# spinnaker-halyard

github addr [https://github.com/kubernets/spinnaker-halyard](https://github.com/kubernets/spinnaker-halyard)

docker hub addr [https://hub.docker.com/u/kubernets](https://hub.docker.com/u/kubernets)

get shell script to pull docker image and replace origin tag

    > wget https://github.com/kubernets/spinnaker-halyard/raw/master/get-spinnaker-halyard-image.sh

## Arch and Version

- [**all** 1.9.1-20180830145737](https://hub.docker.com/r/kubernets/spinnaker-halyard)

    > docker pull kubernets/spinnaker-halyard:1.9.1-20180830145737

    > docker tag kubernets/spinnaker-halyard:1.9.1-20180830145737 gcr.io/spinnaker-marketplace/halyard:1.9.1-20180830145737 

    > docker rmi kubernets/spinnaker-halyard:1.9.1-20180830145737
