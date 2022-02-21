# node-ts-template
Simple and unopinionated Node Typescript template, set up for hot reload on docker.

# Dependencies
- Typescript
- Nodemon
- That's it

# How to run
```sh
docker-compose -f ./docker-compose.development.yml up --build
```
Simplest command, will run the docker compose file for development (hot reload set up already)

```sh
docker-compose -f ./docker-compose.development.yml up --build -d
```
Same as above, but will run the command detached, will require more experience with docker to handle along with `docker-compose down`.

Author: Alejandro Fabian Campos <camposalejandrofabian@gmail.com>
