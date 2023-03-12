# nodejs-docker-example

build docker image:

#### `docker build . -t nodejs-docker`

run the container in detached mode:
#### `docker run -p 49160:3000 -d nodejs-docker`

You will see the result typing in your browser: `localhost:49160`