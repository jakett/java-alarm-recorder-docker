# java-alarm-recorder-docker
- Java recorder app use capillary to encrypt data, thus can decrypt on android and ios device
- Build java recorder app on docker, run app on docker container

- Clone project: https://github.com/jakett/java-alarm-recorder-docker.git
- Install docker, switch to linux container
- Build image: "docker build -t image-name ."
- Run container: "docker run -i -t -d --name container-name -p 8443:8443 image-name"
- Run android and ios client to received notification from recorder app