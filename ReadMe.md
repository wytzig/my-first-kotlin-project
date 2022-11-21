# My first kotlin project
with kotlin, docker and gradle



### project introduction
This project is intended to serve as a nice base from which 
kotlin applications could be easily derived. Nowadays it's not difficult to imagine a
wide application landscape with many microservices all doing their own thing.

This API template could be used to setup an REST API with a datasource (configured over docker).

This project won't have fancy deployment environments baked in; we also stay far away from
something like k8s, although that would be the preferred way of deploying on servers. 


### local development setup
For this project you'll need to get a few things installed first.
These being:


    - An IDE (i.e intellij)
    - Appropiate java version (SDK 16 or 1.6 should work. Tested with coretto16)
    - Gradle
    - Docker to run docker-compose; for windows users don't forget to setup WSL

