# Simple Fortune Cookie Frontend

Faaantastic frontend
Runs on port 8080 by default

**Will not be able to run before Backend is avaliable.**

Otherwise, same as the backend..

Go can be in version 1.18 up to at least 1.21.

## Environment Variables

`BACKEND_PORT` - Port of the backend. Default: 9000
`BACKEND_DNS` - DNS of the backend. Default: localhost

## SemVer and automation

This project uses [SemVer](https://semver.org/) for versioning.    
It is done through [semantic-release](https://github.com/semantic-release/semantic-release), and is automated with GitHub actions.

This project will have its Docker image built and pushed to the repository on every push to the `main` branch. This is automated, such that this only happens when changes has been made to the code in this project.
