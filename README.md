## Build docker image
`docker build . -t simple-docker`
## Run docker container
`docker run -p 8050:80 simple-docker` and Navigate to `http://localhost:8050/`

## Development server
Run `yarn start` for a dev sever. Navigate to `http://localhost:3000/`

## Build
 * Run `yarn build` to build the project. The build artifacts will be stored in the `build/` directory.
