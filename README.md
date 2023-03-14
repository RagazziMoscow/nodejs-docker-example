# nodejs-docker-example

You can only type `docker-compose up` in the project directory or build the image manually

1. build docker image:

#### `docker build . -t nodejs-docker`

2. run the container in detached mode:
#### `docker run -p 49160:3000 -d nodejs-docker`

You will see the result typing in your browser: `localhost:49160`