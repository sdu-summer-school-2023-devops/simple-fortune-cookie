# Simple Fortune Cookie Backend

use `go build` to build code and `go run <app>` afterwards

If redis is not running, you will get a `connection refused` error, don't worry about it ;)

> note for next dev on this project: remember that `redigo` should be in version `v1.8.5` , that worked on my laptop at the time of writing this. Go can be in version 1.18 up to at least 1.21. 

## Environment Variables

`REDIS_DNS` - DNS name of the redis server

## SemVer and automation

This project uses [SemVer](https://semver.org/) for versioning.    
It is done through [semantic-release](https://github.com/semantic-release/semantic-release), and is automated with GitHub actions.

This project will have its Docker image built and pushed to the repository on every push to the `main` branch. This is automated, such that this only happens when changes has been made to the code in this project or to the kubernetes deployment files.

