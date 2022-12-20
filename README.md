## :rocket: ds-project-template

*One liner describing the main idea behind the repository.*

## :pencil: Authors

- [Jaroslav Bezdek](https://www.github.com/jardabezdek)

## :construction_worker_man: Setup

### Local development

In order to create a working environment, the [docker](https://www.docker.com/)
is used. To start it, please, follow the next steps.

1. Launch the docker daemon.
1. Get to the repository root folder: `cd ~/projects/ds-project-template/`
1. Build the docker image with a proper tag: `docker build -t ds-project-template:latest .`
1. Run docker container: `docker run -it -p 8888:8888 -v $(pwd):/usr/src/app ds-project-template:latest /bin/bash`
1. Run notebook inside the docker container: `jupyter notebook --ip 0.0.0.0 --no-browser --allow-root`

### Data download

*This section describes how the data is obtained.*
