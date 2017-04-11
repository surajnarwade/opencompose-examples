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
----------------
* docker-compose file is [here](https://github.com/kubernetes-incubator/kompose/blob/master/examples/docker-compose.yml)
* `links` key removed as not supported

open-voting.yml
---------------

* docker-compose file is [here](https://github.com/kubernetes-incubator/kompose/blob/master/examples/docker-voting.yml)
* raised issue regarding port mapping
    - https://github.com/redhat-developer/opencompose/issues/93

open-guestbook.yml
------------------

* docker-compose file is [here](https://github.com/kubernetes-incubator/kompose/blob/master/examples/docker-guestbook.yml)

open-meanstack.yml
------------------

* Example reference: https://kubernetes.io/docs/getting-started-guides/meanstack/

open-phabricator.yml
--------------------

* Example reference: https://github.com/kubernetes/kubernetes/tree/master/examples/phabricator
