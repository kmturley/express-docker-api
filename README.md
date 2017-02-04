# express-docker-api

Example sending messages between server and client using:
* ExpressJS
* Socket.io
* Docker

## Installation

Build using docker-compose:

    docker-compose build


## Usage

Run all the services together using:

    docker-compose up

Then visit the frontend service:

    http://localhost:3001/


## Docker (optional)

If you like, you can use docker directly using:

    docker build -t express-docker .
    docker run -it -p 8888:8080 express-docker

You can remove all previous images using:

    docker images -q | xargs docker rmi -f


## Directory structure

    backend/                        --> Backend Messages API
    frontend/                       --> Static frontend files


## Contact

For more information please contact kmturley