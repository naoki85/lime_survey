# Usage
After clone, you should check below.
## Install Docker
[https://docs.docker.com/engine/installation/](https://docs.docker.com/engine/installation/)
## Build

```
$ cd lime_survey
$ docker-compose build
```

## Access to contents

```
$ docker-compose up -d
```
After access "http://localhost", you can start "LimeSurvey".
## Stop docker

```
$ docker-compose stop
```
# Cautions
## Setting DB
You should fill "mysql" in "DB place".  
Because cannot access by "localhost".