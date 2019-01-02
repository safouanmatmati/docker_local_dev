# Docker local images
### Goals
Have "ready in use" docker images for web development.

Images are pre-configured and easy to edit.

### Technologies
* [Docker](https://docs.docker.com/install/) : isolate environment manager

## Installation
### Requirements
* [Docker](https://www.docker.com/get-started)

### Step
First, open a terminal

#### Clone the repository

```
git clone https://github.com/safouanmatmati/docker_local_dev.git
cd project docker_local_dev/
```
#### Build all images
```
docker-compose build
```
#### Or a specific one
```
docker-compose build [name of the service]
```

## Usage

#### Run all images
```
docker-compose up
```

#### Or a specific one
```
docker-compose up  [name of the service]
```

That's it.
