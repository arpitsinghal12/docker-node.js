# Metrices Ingestion Server

Metrices ingestion server take input of the computer usage and then generate the report of the computer usage
## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. 

### Prerequisites

You need to have Docker up and running on your machine

```
```

### Installing

A step by step guide on how to install docker on ubuntu machine
```
sudo apt update
sudo apt install apt-transport-https ca-certificates curl software-properties-common
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu bionic stable"
sudo apt update
apt-cache policy docker-ce
sudo apt install docker-ce
```

## Running the docker scripts to up the server
change your directory to docker-compose file directory. ~/metrices-server/
```
docker-compose up --build
```

