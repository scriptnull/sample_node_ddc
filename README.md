### Overview
We will be deploying this sample application to [Docker Datacenter](https://www.docker.com/products/docker-datacenter) using [Shippable Pipelines](http://ship-docsv2.s3-website-us-west-2.amazonaws.com/pipelines_overview/).

[![Run Status](https://api.shippable.com/projects/572091c62a8192902e1e13bd/badge?branch=master)](https://app.shippable.com/projects/572091c62a8192902e1e13bd)

### High level workflow
There are two steps in this process.
- __Continous Integration__ -We will be testing our code with Shippable CI and once all the tests pass, we will build a docker image and push it to a docker registry.

- __Deployment__ - We will configure Shippable pipelines to automatically deploy to Docker Datacenter, whenever a newer version of image tag appears in the registry.

#### Requirements
- [Docker Datacenter](https://www.docker.com/products/docker-datacenter) - Universal Control Plane is mandatory, whereas you Docker Trusted Registry is optional. You can get an idea of how to install it from [here](https://docs.docker.com/ucp/evaluation-install/).
- [Shippable account](https://shippable.com/) - You need to have a [Github](https://github.com/) or [Bitbucket](https://bitbucket.org/) account for using Shippable.

### Instructions
Please read the documentation on [how to deploy containers to Docker Datacenter](http://docs.shippable.com/ht_docker_datacenter/) for detailed instrcutions.
