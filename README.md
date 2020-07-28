# Docker Oracle

![Docker Cloud Build Status](https://img.shields.io/docker/cloud/build/comicrelief/node-oracle)
![GitHub](https://img.shields.io/github/license/comicrelief/docker-node-oracle)
![Docker Image Version (latest semver)](https://img.shields.io/docker/v/comicrelief/node-oracle)

Docker image to be used for building a container ready with Oracle instant client binaries and all necessary environment variables needed to use the primary Node.js Oracle Database driver libraries:

[strong-oracle](https://github.com/strongloop/strong-oracle)  
[node-oracledb](https://github.com/oracle/node-oracledb)


## Usage

Within your Dockerfile:

```
FROM comicrelief/node-oracle:{VERSION}
```


## Versions

Specify the Node.js version you would like to use in the above *{VERSION}*.  Check [the different branches available on this repo](https://github.com/comicrelief/docker-node-oracle/branches) to see available versions.

>If you would like to use a version that is currently not a branch of this repo, submit a PR with the updated Dockerfile with the edit too:

```
FROM node:{VERSION}
```

### :latest

Using "latest" (FROM comicrelief/node-oracle) as the version will use "FROM NODE:10" as it's base image.  It is recommended that you use a specific version (X.X.X) but if you only want the latest version of Node 10.X.X then latest will work.
