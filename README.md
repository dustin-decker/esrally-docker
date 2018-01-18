# esrally-docker
elasticsearch rally / esrally in Docker

``` bash
docker run --rm -it dustin-decker/esrally --help 
```

``` bash 
docker run --rm -it dustin-decker/esrally --track noaa --target-hosts elastic1:80,elastic2:80 --pipeline=benchmark-only
```