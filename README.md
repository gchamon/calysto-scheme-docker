# calysto-scheme-docker

## Usage

`docker run -it --rm -p 8888:80 -v $(pwd):/app -u $(id -u $USER):$(id -g $USER) gchamon/calysto-scheme-alpine`
