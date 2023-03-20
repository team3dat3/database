# database
MySQL Server

## Configuration

Configure the MySQL server using the file: [my.cnf](https://github.com/team3dat3/mysql/blob/main/my.cnf); and the [Dockerfile](https://github.com/team3dat3/mysql/blob/main/Dockerfile).

## Main branch
[![Build Docker Image](https://github.com/team3dat3/mysql/actions/workflows/main.yml/badge.svg)](https://github.com/team3dat3/mysql/actions/workflows/main.yml)

## Release branch
[![Build and Deploy Docker Image](https://github.com/team3dat3/database/actions/workflows/deploy.yml/badge.svg)](https://github.com/team3dat3/database/actions/workflows/deploy.yml)

# How to run image
```
 $ docker run -p 3306:3306 <insert-image-name>
```

## How to release
Merge 'main' into a branch called 'release' to start the deployment workflow.
