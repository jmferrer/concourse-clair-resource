# Concourse Clair Resource

Uses [clair](https://github.com/quay/clair) and [klar](https://github.com/optiopay/klar) to check vulnerabilities in containers.

This resource uses a [container with klar](https://hub.docker.com/repository/docker/jmferrer/klar) and receive as parameters:

- docker_user: 
- docker_password: 
- image: 
- clair_output: 
- clair_endpoint:  
