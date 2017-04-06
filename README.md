OpenCompose Examples
====================

open-gitlab.yml
---------------
* docker-compose file is [here](https://github.com/kubernetes-incubator/kompose/blob/master/examples/docker-gitlab.yml)
* `depends_on` key removed as not supported
* raised issue for `restart` and `command` support
    - https://github.com/redhat-developer/opencompose/issues/90
    - https://github.com/redhat-developer/opencompose/issues/91
    
* `temp12` is assigned for blank environment variable as opencompose don't permit it 

open-counter.yml
---------------
* docker-compose file is [here](https://github.com/kubernetes-incubator/kompose/blob/master/examples/docker-compose.yml)
* `links` key removed as not supported