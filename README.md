# DockerCourse

## Commands

docker build -t hello-docker .

docker images

docker run hello-docker

docker run -it hello-docker -sh

docker build -t react-docker .

docker run react-docker

docker run -p 5173:5173 react-docker

docker ps -a

docker container prune

added --host next to "dev": "vite" inside of package.json "scripts"
