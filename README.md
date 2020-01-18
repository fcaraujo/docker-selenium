# docker-selenium
Easy way to run side files by selenium-side-runner using docker. Inspired by nixel2007/docker-selenium-side-runner.

## Quick start

* install docker `choco install -y docker-desktop` 
* ensure docker is up and running with `docker version`
* enable drive sharing in `settings > shared drives > C:` 
* copy your `side`'s in `./sides` directory
* run `docker-compose up`
* get result from console and `./out` directory (in json-format)
