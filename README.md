# Dockerfile for bionode-watermill-tutorial

This is a dockerfile for using with bionode-watermill-tutorial. Here you will
 have all the dependencies installed and you can run the example 'two-mappers' 
 within this docker container, as well as the bionode-watermill-tutorial.
 
## Build this docker on your local machine

#### Using Git Hub

* `git clone https://github.com/tiagofilipe12/docker-watermill-tutorial.git`
* `docker build . bionode-watermill`

or

#### Using Docker Hub

* `docker pull ...`

## Running the docker container
* `docker run -it bionode-watermill zsh`

## Running bionode-watermill two-mappers example
* `cd examples/pipelines/two-mappers`
* `node pipeline.js`

or
* `node pipeline_lazy.js` (this one is still not ready!)