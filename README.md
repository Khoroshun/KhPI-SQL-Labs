# SQL labs

## Getting Started
### Install Docker (skip this step if you already have Docker)

Install [Docker](https://docs.docker.com/install/)

[How to install Docker on Ubuntu](https://docs.docker.com/engine/install/ubuntu/)

Create the docker group
```bash
sudo groupadd docker
sudo usermod -aG docker $USER
```
Reboot system to apply changes

## Install Docker Compose (skip this step if you already have Docker Compose)

Install [Docker Compose](https://docs.docker.com/compose/install/)

## Prepare

```bash
git clone git@github.com:Khoroshun/KhPI-SQL-Labs.git .
```

```bash
cat .env.example >> .env
```

Update variables to your needs.

## Install Project

Run your docker containers
```bash
docker-compose up -d
```

## Create local DB
Please log in as - [adminer](http://localhost:8080/?server=db&username=dbuser&db=mydb).

Authorization data from docker:

- System - MySQL
- Server - db
- Username - dbuser
- Password - dbpassword
- Database - mydb
