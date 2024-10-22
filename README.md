# freelance_platform

## Submodules
to add new subdirectory :
creeate a new repo 
go to main repo

```bash
 
git submodule add <repo link>
git add all 
git commit -m "message"
git push

```

to refresh the subdirectories's reference 
go to main repo
 
```bash
git submodule update --recursive --remote
git add all
git commit -m "message"
git push

```

to clone the projet with all the submodules
 
```bashgit submodule update --init --recursive

git clone --recursive <project url>

```

## Infrastructure setup

To start the projects you need to have mysql installed, that's why we are using docker to create a container with mysql image.

### Prerequisites

Create a docker volume
    
```bash
docker network create freelance-platform
```

To create the container you need to run the following command:

```bash
docker compose up -d
```

Now you can access the database using the following credentials:

```bash
host: localhost
port: 3306
user: root
password: 
```

You also have phpmyadmin running on port 9080, you can access it using the following credentials:

[http://localhost:9080](http://localhost:9080)
